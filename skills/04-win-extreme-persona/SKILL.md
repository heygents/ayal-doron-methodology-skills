---
name: 04-win-extreme-persona
description: "Ayal Doron's Tool 3 — the extreme persona (דמות קיצונית), \"one problem + someone's idea = a solution in 60 seconds\". Picks 2–3 contrasting, distinctive public figures, asks what each would do if they ran this problem, walks the corridors of each concept, extracts each one's single \"chicken for a shekel\" message, and translates it back to the user's context. Use when the user runs /04-win-extreme-persona, is stuck after /02 and /03, needs fresh options fast, or asks \"what would X do\"."
---

# 04 · Win — The Extreme Persona ("1 + רעיון של מישהו")

> "One problem plus the idea of someone bold, extreme, colorful — and within a minute you have a solution.
> It's embarrassing how well it works."

When extremizing the goal and the obstacle didn't move you, borrow a brain. Imagine a person who lives in
extremes and speeds, whose thinking is very distinct, and ask: **if they were here right now, what would
they shout at us to do?** You don't debate whether they're right or good — you take their operating logic.

## Read first

- `../../references/ayal-doron-examples.md` §6 (Trump / Gandhi as principal and at the safari, Rami Levy for the municipality).
- `Outputs/Win/<slug>/challenge-card.md` plus `02-…` / `03-…` if present. Otherwise ask for the problem in one line and the (almost-absurd) goal.

## Language

User's language (default Hebrew). Keep: דמות קיצונית, "עוף בשקל", מסר אחד.

## Workflow

### 1) Fix the "1"
One line: the problem + the goal it must serve. Example: *"residents thank us even when the garbage truck wakes them."*

### 2) Choose 2–3 personas that contrast
Ask the user *"עם מי אתה רוצה להתייעץ?"* first — Ayal always let the room pick (they said Rami Levy). Then add one
or two **opposites** so the range is visible (Trump ↔ Gandhi).

Persona criteria: public figure or archetype · **extreme and distinct** thinking · well-known operating logic ·
you can predict their first three moves. Suggested bank (extend freely):

| Logic | Examples |
|---|---|
| Maximal spectacle, dominance, money | Trump, MrBeast, a Formula-1 team boss |
| Radical simplicity, empathy, no punishments | Gandhi, Fred Rogers, a Zen abbot |
| One killer offer, price as message | Rami Levy ("chicken for a shekel"), IKEA, Ryanair |
| Come to the customer, remove the fee | Reed Hastings, Bezos |
| Craft and taste above all | Jony Ive, a Michelin chef |
| Slowness as strategy | Carlo Petrini (Slow Food) |
| Wartime speed | a special-forces commander, a trauma surgeon |
| A child, a grandmother, a tourist | (archetypes are allowed and often sharper) |

Avoid private individuals; avoid real-time political argument — the persona is a lens, not a position.

### 3) Sixty seconds per persona — walk the corridors
For each persona, produce the concept **fast** and **concrete**, the way Ayal described Trump's school
(mahogany, gold stripes, a teacher fired every four days, rhetoric class, jackets, a stage) and Gandhi's
(mats, no bells, no punishments, everyone hugged):
- **First three moves** they'd make on day one.
- **What the place looks, sounds and feels like** — walk the corridor.
- **What they'd kill** immediately.
- **Their "chicken for a shekel"**: the *one* thing the customer/employee/resident would remember.
  Rami Levy's rule: *the brain holds one thing; don't multiply messages.*

Keep each persona to ~8 lines. Contrast is the point; don't reconcile them.

### 4) Translate back
For each persona's "chicken for a shekel", ask: **what is *our* version?** (Tel Aviv's answer to Rami Levy
was free parking.) Write 1–2 candidate moves per persona in the user's actual context, with the constraint
that each is a **single message**.

### 5) Pick and hand off
Ask the user which move made them sit up. Route to `/05-win-calculated-knockout` to shape it into a
calculated risk with a pilot; or back to `/02` if a persona revealed that the goal was still too small.

## Output

Save to `Outputs/Win/<slug>/04-extreme-persona.md` if the folder exists; else chat + offer to save.

```markdown
# Extreme persona — <title>
## The "1"
Problem: … · Goal it must serve: …
## Personas
### <Persona A> — logic: <one phrase>
- First three moves: 1… 2… 3…
- Walk the corridor: …
- Kills immediately: …
- Chicken for a shekel: **"<one message>"**
### <Persona B> — (contrast) …
### <Persona C> — …
## Our version
| From | Their one thing | Our one thing | Single message? |
| A | … | … | ✅ |
| B | … | … | … |
## Chosen move
"<…>" — because …
## Next
- /05 to make it a calculated risk with a pilot
```

## Guardrails

- Personas are caricatures of *operating logic*; keep it light and never attribute real quotes or intentions to real people.
- If the user picks a persona you find distasteful, still run it — Ayal's point is that the lens works regardless — but keep the output to the mechanism.
