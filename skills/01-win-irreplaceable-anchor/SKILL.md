---
name: 01-win-irreplaceable-anchor
description: "Ayal Doron's anchor tool — find what a person, team or business is \"the best in the world at\" (במה אני הכי מעולה בעולם) with the 7-second test, the \"call Ruti\" test and a weekly sharpening ritual, so they can jump from coping with uncertainty to thriving on it. Use when the user runs /01-win-irreplaceable-anchor, asks how to be irreplaceable / not replaceable by AI, what their unique strength or the business's unique force is, or when the Challenge Card says anchor is unclear."
---

# 01 · Win — The Irreplaceable Anchor (העוגן: במה אני הכי מעולה בעולם)

> "Whoever thinks they are replaceable is the first to be replaced in a world where a machine replaces.
> Whoever searches for what they are irreplaceable in walks a different path on the same time and effort."

Find the **anchor** (עוגן): the one thing this person / team / business is the best in the world at,
where "world" means their organization, neighborhood or market — then make it nameable in seven seconds,
recognized by others, and sharpened every week. The anchor is what lets someone jump from **level 2
(copes with uncertainty)** to **level 3 (thrives on it)**.

## Read first

- `../../references/ayal-doron-examples.md` §1–3 (thesis, ladder, anchor examples, forbidden answers).
- `Outputs/Win/<slug>/challenge-card.md` if it exists (from `/00-win-challenge-intake`). If not, ask the
  two minimum questions: **who is this for** (person / team / business) and **what is the context**.

## Language

Talk to the user in their language (default Hebrew); keep the Hebrew key terms. Direct, warm, provocative.

## Workflow

### 1) Ask the question, enforce the seven seconds
> במה אתה / אתם / העסק הכי מעולים בעולם? "עולם" = הארגון, השכונה, השולחן. יש לך שבע שניות.

- Record what comes out **and how fast**. Speed is the signal: the co-founders answered in seven seconds.
- If they give one of the **three forbidden answers** (no one is irreplaceable / cemeteries are full / only at home),
  name it as the script we were taught, explain that humility means staying curious and in proportion — not
  ignoring your distinct strength — and ask again.
- If they answer with a job title or a generic virtue ("hard-working", "professional"), push: *that is what
  you do, not what you are the best at.*

### 2) Collect candidates from three angles (if step 1 was slow or generic)
Ask one at a time; aim for 5–8 raw candidates:
1. **The room:** what do people call you for? Finish the sentence *"רגע, אם זה על ___, תקרא ל<שם>"*.
2. **The pattern:** what happens repeatedly around you that doesn't happen around others? Use Ayal's list as prompts —
   gives the insight that changes the picture · makes things happen · solves the unsolvable · infects everyone
   with optimism · brings courtesy into every room · reaches the people nobody else can talk to · runs meetings
   where everyone participates. (Reference §3 — "there are 1,200 options.")
3. **The human residue:** what here is gut feeling, presence, connection — the part a machine can't fake yet?
   (Reference §1.)

For a **business**, replace "you" with "this business in its market": what do customers say only you do?
What do competitors not even try? What do you deliver with force and speed nobody matches?

### 3) Test each candidate
Score honestly (✅ / ⚠️ / ❌) on:

| Test | Passes when |
|---|---|
| **7 seconds** | Can be said in one breath, no hedging. |
| **Call Ruti** | Others in the room would name you for it — or would within a month if you started saying it. |
| **Specific** | Not a title, not a virtue; a thing that happens because of you. |
| **Radius** | True at a real radius (team / org / city / segment) — you are not claiming the universe. |
| **Sharpenable** | You can make it 2% better *this week*. |
| **Human** | It lives in judgement, presence, connection, intuition — not in a task list a model does. |

Pick **one** anchor (at most two). If nothing passes, say so and go back to step 2 with the "relocation"
frame: *if you had to move country tomorrow, what would you take with you and retrain into the local
version?* (football → American football.)

### 4) Write the anchor sentence
Format: `<Name> is the one who <specific effect>, at <radius>.`
Hebrew: `<שם> הוא/היא זה/זו ש<אפקט ספציפי>, ב<רדיוס>.`
Examples: "Ruti is the one to call on technology + representation, in this company." "We are the ones who
show up at your home instead of making you come to us, in home entertainment."

### 5) Weekly sharpening ritual (השחזה שבועית)
Ayal: "every week I improve that meeting a little more, I hone it." Define with the user:
- **The unit:** the recurring moment where the anchor shows (a meeting, a call, a delivery, a decision).
- **This week's 2%:** one concrete improvement.
- **Evidence:** how they'll know it landed (someone said "call X"; a metric; a reaction).
- **Complements:** who completes them (Ayal: "I know which problems I bring to Dolev, where Chen completes me").

### 6) Ladder jump
State where they are (1–4) and what the anchor changes: "With the anchor named and sharpened weekly, the jump
from 2 to 3 is possible: you know who you are, so change stops being a threat and becomes the thing you're
good in." Hand off to `/06-win-habit-infrastructure` for the supporting habits, and to `/02` if they have a
goal to attack.

## Output

Save to `Outputs/Win/<slug>/01-anchor.md` if the challenge folder exists; otherwise show in chat and offer to save.

```markdown
# Anchor — <name / team / business>
## The anchor (7 seconds)
"<anchor sentence>"
## Candidates considered
| Candidate | 7s | Call-Ruti | Specific | Radius | Sharpenable | Human | Verdict |
## Why this one
<2–3 lines>
## Weekly sharpening
- Unit: … · This week's 2%: … · Evidence: …
- Who completes me: …
## Ladder
- Now: <1–4> → Target: 3 (thrive). What changes: …
## Next
- /02-win-almost-absurd-goal on: <goal> · /06-win-habit-infrastructure for: <habits>
```

## Guardrails

- Never assign an anchor the user didn't recognize; propose, then let them choose.
- When the subject is a child or an employee, keep it strengths-only and concrete.
- Don't drift into a generic strengths assessment; the output is **one sentence**, a weekly ritual, and the jump.
