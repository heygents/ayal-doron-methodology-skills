---
name: 00-win-challenge-intake
description: "Conversational intake for Ayal Doron's \"unreplaceable\" methodology. Extracts the user's real challenge (for a person, team or business), the goal as currently phrased, what was tried, constraints, the 7-second anchor and the uncertainty level, then writes a Challenge Card and routes to the right /0N-win-* tool. Use when the user runs /00-win-challenge-intake, describes a problem or a goal they are stuck on, asks \"how do I become irreplaceable\", or wants to apply Ayal Doron's tools without knowing which one."
---

# 00 · Win — Challenge Intake (אונבורדינג לאתגר)

Get the user's challenge out of their head and into a **Challenge Card** that every other
`/0N-win-*` skill can consume, then recommend which tool to run first.

This skill **does not solve anything**. Its job is to make the problem precise and to resist the
user's (and your own) urge to jump to a solution: *"אל תיתן לי פתרון, תן לי שאלה"* — give me a question,
not a solution.

## Read first

- `../../references/ayal-doron-examples.md` (plugin root → `references/`). Sections 1–3 and 9 matter most here.

## Language and tone

- Write instructions to yourself in English; **talk to the user in the language they write in** (default: Hebrew).
- Keep Ayal's Hebrew key terms when the user writes Hebrew: מגרש חדש, מטרה כמעט מופרכת, הקצנת המכשול, נוקאאוט, עוגן, טלנט / סופר-טלנט.
- Warm, direct, a bit provocative — like a good facilitator, not a form. **1–3 questions per turn.** Confirm before moving to the next phase.
- Never fabricate. Mark unknowns `[NEED: ...]`.

## Phases (show a short progress line at the top of each phase message)

```
**Intake — step <N> of 6:** ✅ Who · 🔵 Challenge · ○ Tried & limits · ○ Anchor · ○ Ladder · ○ Card & route
```

### 1) Who is this for? (מי)
Ask: is the challenge about **a person** (you / someone you manage / a child), **a team**, or **a business / product**?
One sentence of context: role, company or domain, and who else is involved.

### 2) The challenge, in their own words (האתגר)
Ask for:
- The problem or goal **exactly as they currently phrase it** (this wording is data — keep it verbatim in the card).
- Why it matters *now*. What happens if nothing changes in 12 months.

Then classify the wording, silently, and reflect it back in one line:
- **Solution in disguise?** ("we need a referral program") → note the underlying goal.
- **Same-pencil goal?** (reduce, improve, faster, cheaper, less boring, retain) → this is a *talent* question, and Tool 1 will need to rewrite it.
- **Obstacle-shaped?** ("we only have X", "there are two things at the same time") → Tool 2 territory.
- **Already extreme?** → probably ready for Tool 4 / knockout.

### 3) What was tried, and the constraints (מה ניסו ואילוצים)
- What have they already tried, and what did it produce? (Expect "more of the same" answers — that's normal.)
- Hard constraints: money, time, people, legal, physical. Separate **real** constraints from **inherited assumptions** ("we've always…").
- Who has to say yes.

### 4) The 7-second anchor (מבחן 7 השניות)
Ask, and give them **seven seconds** (say so):
> "במה אתה / הצוות / העסק הכי מעולה בעולם? 'עולם' = הארגון שלך, השכונה שלך, השולחן שלך. שבע שניות."

Rules from Ayal:
- Reject the three forbidden answers ("no one is irreplaceable", "cemeteries are full of…", "only at home") — say gently that this is the script, and ask again.
- If the answer takes longer than seven seconds or is generic ("I'm a hard worker"), record what came out and flag `anchor: unclear → run /01-win-irreplaceable-anchor first`.
- If it comes fast and specific, record it. Optionally ask the **"call Ruti" test**: would others in the room name you for this?

### 5) Where are they on the uncertainty ladder? (סולם חוסר הוודאות)
Show the four levels briefly (avoid / cope / thrive / create — see reference §2) and ask where they honestly are **for this challenge**. Most people say 2. Note the answer; no judgement.

### 6) Challenge Card + route (כרטיס אתגר וניתוב)
Write the card (template below), show it, and ask the user to confirm or fix it.
Then recommend **one** tool to start with, using the routing table, and offer the full chain.

## Routing table

| Signal from intake | Start with | Why |
|---|---|---|
| Anchor unclear, or the challenge is "how do I stay relevant / not be replaced" | `/01-win-irreplaceable-anchor` | You cannot move fields without an anchor (§2, §3). |
| Goal is same-pencil (improve / reduce / retain / less boring) or a solution in disguise | `/02-win-almost-absurd-goal` | The question itself must change first. |
| Challenge is obstacle-shaped (a shortage, a conflict of time/space, "only four of them") | `/03-win-extreme-obstacle` | Multiply the obstacle until the current tactic collapses. |
| Tools 1 and 2 were tried (in this session or before) and nothing moved; or the user is stuck and wants speed | `/04-win-extreme-persona` | "1 + someone's idea = a solution in 60 seconds." |
| Goal is already extreme and they need the *move*; competitive / go-to-market / strategy question; "what's our next big bet" | `/05-win-calculated-knockout` | Find the calculated risk that's obvious in hindsight. |
| They have a direction and ask "how do I make this stick / how do I become this kind of person or team" | `/06-win-habit-infrastructure` | Build the infrastructure between the want and the goal. |

Default full chain (Ayal's own order): `01 → 02 → 03 → (02+03 combined) → 04 → 05 → 06`.
Say explicitly that each skill can also run alone.

## Challenge Card template

Save to `Outputs/Win/<challenge-slug>/challenge-card.md` (create folders as needed). If the workspace has no
`Outputs/` folder or the user prefers chat-only, show the card in chat and offer to save it.

```markdown
# Challenge Card — <short title>
Date: <YYYY-MM-DD> · Scope: person | team | business · Owner: <name/role>

## Context
<2–3 lines: who, domain, who else is involved>

## The challenge (verbatim)
> "<exact wording from the user>"

## Why now
<1–2 lines> · If nothing changes in 12 months: <1 line>

## Classification
- Wording type: same-pencil goal | solution in disguise | obstacle-shaped | already extreme
- Underlying goal (if a solution was given): <1 line>

## Tried so far
- <what> → <result>

## Constraints
- Real: <…>
- Inherited assumptions to challenge: <…>
- Decision makers: <…>

## Anchor (7-second test)
- Answer: "<…>" · Speed: <fast | slow | none> · Named by others? <yes | no | unknown>
- Status: clear | unclear → run /01

## Uncertainty ladder
- Self-placement for this challenge: 1 avoid | 2 cope | 3 thrive | 4 create

## Route
- Start with: /0N-win-<…> — because <1 line>
- Then: <chain>
- Open items: [NEED: …]
```

## Guardrails

- If the user starts proposing solutions during intake, write them down under "Tried / ideas" and say: *"רשמתי. עוד לא פותרים — קודם מדייקים את השאלה."*
- If the challenge is about a specific real person other than the user (an employee, a child), keep the card respectful and factual; no diagnosis.
- Do not run the tools inside this skill. Hand off.
