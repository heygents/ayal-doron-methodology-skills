---
name: 02-win-almost-absurd-goal
description: "Ayal Doron's Tool 1 — extremize the goal (הקצנת המטרה). Rewrites a goal as received into an \"almost-absurd\" goal (מטרה כמעט מופרכת) that leaves no choice but to invent a new playing field, using Ayal's escalation grammar, quality tests, and primitive-redefinition. Use when the user runs /02-win-almost-absurd-goal, brings a goal phrased as improve/reduce/retain/faster/less-boring, asks for a bolder vision or a north-star, or the Challenge Card routes here."
---

# 02 · Win — The Almost-Absurd Goal (הקצנת המטרה)

> "You never leave a goal the way you received it. You always turn it into an almost-absurd goal."
> "The more ambitious goal is *easier* to reach than the modest one — it works backwards."

A goal phrased as *improve / reduce / retain / faster / less boring* is a **talent** question: no matter how
smart you are, you will sharpen the same pencil. This tool rewrites it into a **super-talent** question so
big that there is nothing to hurry toward — you have to invent a new field (מגרש חדש) on the same half hour.

## Read first

- `../../references/ayal-doron-examples.md` §1 and §4 (the four before/after examples and the escalation grammar).
- `Outputs/Win/<slug>/challenge-card.md` if present. If not, ask for: the goal **as currently phrased**, who it is for, and one line of context.

## Language

User's language (default Hebrew). Keep: מגרש חדש, מטרה כמעט מופרכת, לחדד את אותו עיפרון, טלנט / סופר-טלנט.

## Workflow

### 1) Show the goal as received and name its type
Quote it verbatim. Say which pencil it sharpens: *"זו שאלה של טלנט — התשובה תהיה עוד מאותו דבר: פחות ביורוקרטיה, שני תלושים במקום אחד."*
If the user gave a **solution** ("we need a referral program"), recover the goal behind it first.

### 2) Escalate in public, 5–7 rungs
Build a ladder from the received goal upward. Each rung must be **bigger in kind**, not in quantity. Use the grammar:

| Pattern | Hebrew | Example from Ayal |
|---|---|---|
| Not only… but… | לא רק ש… אלא ש… | not only do they stay — they bring friends — the best fight to come — people pay to work here |
| Every X gets Y on day Z | כל X מקבל Y ביום Z | every baby gets a key on the day of birth |
| What does A have that no B has, even the best B? | מה יש ב-A שאין בשום B, גם ב-B הכי מופלא | what does school have that no home has |
| People pay to… / X fight over… | אנשים משלמים כדי… / X הולכים מכות כדי… | talents fight to work here |
| Native-level by age / by date | דוברי שפת אם עד גיל… | native English by age ten |
| The customer cries when… | הלקוח בוכה כש… | the kid cries when told to go home |

Do this **with** the user: propose two rungs, ask for the next one, push back exactly like Ayal did —
*"מביאים חברים זה עדיין יכול להיות שיפור של אותו עיפרון. תמשיכו, זה קשה עכשיו, תנו לי עוד."*

### 3) Apply the quality tests to each rung
| Test | Ask |
|---|---|
| **Question, not solution** | Is this still a goal, or did a tactic sneak in? (אל תיתן לי פתרון, תן לי שאלה) |
| **Same pencil?** | Could a competent team hit it by doing more of what they do? If yes → not extreme enough. |
| **Forces a new field** | Would answering it require changing *the whole event*, not smiling more? |
| **Almost absurd, not nonsense** | It sounds impossible today but you can imagine someone, somewhere, having done it. |
| **20x gap** | Two equally smart groups, one with the old goal, one with this — would the pitches be embarrassingly different? |

Pick the rung that passes all five. That is the **almost-absurd goal**. Write it as one sentence.

### 4) Redefine the primitives (after three minutes you must ask "what is X?")
Ayal: with "every baby gets a key", after three minutes you must ask *what is housing? what is a key? what is
an apartment? what is ownership?* For the chosen goal, list its 4–6 nouns and ask "what is ___, really?" for
each. Note which definitions the current field takes for granted.

### 5) Sketch 3 new-field directions
For each direction: one line, which primitive it redefines, and why it is impossible in the old field.
Do **not** develop them into plans; that's for the team, `/05-win-calculated-knockout`, or the user's PM tools.
Optional: one line of what a *talent* would have done with the same half hour, for contrast.

### 6) Hand off
- If nothing moved the user, say so and route to `/03-win-extreme-obstacle` (or combine: goal + obstacle).
- If they want the *move*, route to `/05-win-calculated-knockout`.
- If it is a shared goal for a team or a community, add the "unifying vision" note (reference §9): big enough for everyone to find their place under it.

## Output

Save to `Outputs/Win/<slug>/02-almost-absurd-goal.md` if the folder exists; else chat + offer to save.

```markdown
# Almost-absurd goal — <title>
## As received (talent question)
> "<verbatim>"  → sharpens: <what more-of-the-same looks like>
## Escalation ladder
1. … (still same pencil)
2. …
3. … ✅ almost absurd
…
## The almost-absurd goal
**"<one sentence>"**
Passes: question ✅ · not same pencil ✅ · forces new field ✅ · almost-absurd ✅ · 20x gap ✅
## Primitives to redefine
- What is <noun>? — current assumption: … → could mean: …
## Three new-field directions
1. <direction> — redefines <primitive>; impossible in the old field because …
2. …
3. …
## Contrast (same half hour)
- Talent would: …
## Next
- /03 to extremize the obstacle · /05 for the knockout move · /06 to build habits
```

## Guardrails

- Keep the user's domain constraints visible but don't let them shrink the goal; constraints belong to execution (Tool 4: bold idea, cautious execution).
- No more than one goal per run. If the user brings three goals, pick the one from the Challenge Card and park the rest.
