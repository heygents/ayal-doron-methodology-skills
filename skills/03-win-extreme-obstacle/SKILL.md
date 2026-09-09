---
name: 03-win-extreme-obstacle
description: "Ayal Doron's Tool 2 — extremize the obstacle (הקצנת המכשול). Multiplies the obstacle on purpose (two weddings → five, four students → twenty-five, three → three thousand) until the current tactic collapses, redefines what the goal really is, and produces a solution ladder from extravagant to nearly free. Use when the user runs /03-win-extreme-obstacle, describes a shortage, a clash of time/place/resources, or a \"we only have N\" problem, or when /02 didn't move them."
---

# 03 · Win — The Extreme Obstacle (הקצנת המכשול)

> "If four students disrupt the class you'll never solve it. If it were twenty-five, you'd go out and
> solve it from the root." · "Three terrorists — same fence. Three thousand — *what is a fence?*"

The brain forgets to exaggerate. When the obstacle is small enough to cope with, you cope — and stay in
the old field. This tool enlarges the obstacle **deliberately** until the current approach is obviously
dead, and the mind has no choice but to design a new kind of solution.

## Read first

- `../../references/ayal-doron-examples.md` §5 (the two-weddings ladder, the fence, the coffee pause) and §4 (to combine with the goal).
- `Outputs/Win/<slug>/challenge-card.md` and `02-almost-absurd-goal.md` if present. Otherwise ask for: the obstacle as they see it, the goal it blocks, and what "being there / solving it" currently means to them.

## Language

User's language (default Hebrew). Keep: הקצנת המכשול, מגרש חדש, "מה זה גדר?".

## Workflow

### 1) State the obstacle and the coping answer
Write the obstacle in one line, in their numbers ("two weddings, 2.5 hours apart, both at 20:00").
Write the **group-1 answer** they are about to give: *a bit and a bit*, hire one more, work harder.
Name it: *"זה מתמודד עם חוסר ודאות. אנחנו רוצים לקפוץ."*

### 2) Multiply until it breaks
Escalate along the obstacle's own dimensions. Pick the ones that apply:

| Dimension | Multiply by | Example |
|---|---|---|
| Count | 2.5x · 10x · 100x | 2 weddings → 5 · 4 students → 25 · 3 → 30 → 300 → 3,000 |
| Distance / spread | across the country | one in Eilat, one in the Galilee, three of your choice |
| Time | same hour · same day | all at 20:00 next Wednesday |
| Scarcity | remove the resource entirely | zero engineers, zero budget, no venue |
| Stakes | make it unforgettable | four years later everyone still talks about it |

Stop at the rung where the user says *"עכשיו אתה מסבך את האירוע"* or *"זה כבר לא אותו דבר"*. That is the
**breaking point** — the current tactic is dead there. Write down *why* it died (e.g. "physical presence
is no longer possible at five places at once").

If the user wants to quit here, do the **coffee pause**: say you're getting coffee, hold the silence, and
invite them to stay in the process. Nine out of ten leave. Work with the one who stays.

### 3) Combine with the goal (optional but usually decisive)
Attach the almost-absurd goal from `/02` (or build one now): *"five weddings from Eilat to the Galilee — and
four years later everyone still talks about the fact that you were there."* Obstacle × goal together is what
produced the whole ladder in Ayal's example.

### 4) Redefine what the goal really is — "what does the groom actually do?"
The extreme obstacle exposes that the original goal was a proxy. Ask the Beni question:
*what actually happens on the other side, and what would count as success there?*
- "Be at the wedding" → "the groom is sure I was there" → "the groom remembers one word in the morning".
- "Teach with four disruptors" → "the class lets me teach" → "the class *wants* the lesson to continue".
Write the **redefined goal** in one line.

### 5) Build the solution ladder — three cost levels
Generate at least one solution at each level, all satisfying the *redefined* goal:

| Level | Ayal's example | Your job |
|---|---|---|
| **Extravagant** (the helicopter, ~100K) | land in the chuppah | the no-limits version — it proves the goal is reachable |
| **Moderate** (the disproportionate check, ~10K) | he keeps inventing memories of you dancing | keeps the effect, cuts the cost 10x |
| **Nearly free** (Beni's 250 ILS, the five-shekel check, the AI photo) | "Beni was just looking for you", once an hour | the architect's version — targets the mechanism itself |

For each: what it costs, what it *reduces to* (the mechanism), and the risk (the five-shekel check is
unforgettable "not in a good way").

### 6) Hand off
- Still nothing? Route to `/04-win-extreme-persona` ("1 + someone's idea, 60 seconds").
- Have a favorite? Route to `/05-win-calculated-knockout` to turn it into a calculated risk with a pilot.

## Output

Save to `Outputs/Win/<slug>/03-extreme-obstacle.md` if the folder exists; else chat + offer to save.

```markdown
# Extreme obstacle — <title>
## Obstacle as stated
"<…>" → coping answer we refuse: <…>
## Escalation
| Rung | Obstacle | Current tactic still works? |
| 1 | … | yes |
| … | … | ❌ breaking point — because … |
## Combined with the goal
"<obstacle × almost-absurd goal>"
## Redefined goal ("what does the groom actually do?")
"<one line>"
## Solution ladder
| Level | Solution | Cost | Mechanism | Risk |
| Extravagant | … | … | … | … |
| Moderate | … | … | … | … |
| Nearly free | … | … | … | … |
## Next
- /04 if stuck · /05 to make it a calculated risk
```

## Guardrails

- The multiplication is a *thinking* device. Never propose the extreme scenario as a real plan; propose solutions that survive it.
- Keep the nearly-free rung honest — cheap tricks that deceive people (fake photos, fake attendance) are Ayal's jokes about *mechanism*; present them as illustrations of the mechanism, and let the user choose ethical variants.
