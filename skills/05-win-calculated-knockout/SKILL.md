---
name: 05-win-calculated-knockout
description: "Ayal Doron's Tool 4 — the calculated risk that lands a knockout (סיכון מחושב / נוקאאוט). Finds the move that sounds crazy in real time and obvious in hindsight (Netflix no-late-fees and binge, Amazon free shipping, Bank Leumi's branch-manager phone number), anchors it to the supreme goal, quantifies the real downside, and designs a bold-idea / cautious-execution pilot. Use when the user runs /05-win-calculated-knockout, asks for the next big bet, a go-to-market edge, how to beat a much bigger competitor, or arrives with a chosen move from /02–/04."
---

# 05 · Win — The Calculated-Risk Knockout (סיכון מחושב / נוקאאוט)

> "A knockout means I bring not only irreplaceable value — I bring it with such force and speed that no one
> else can compete with me." · "A calculated risk is a move that sounds crazy in real time; in hindsight
> everyone asks: why didn't *we* do that?"

Netflix at $50M knocked out Blockbuster at $50B not by opening stores (that field was already taken) but by
*coming to your home*, killing late fees, and later letting you binge — each time asking **what is our
supreme goal?** This tool finds the user's knockout and makes the risk *calculated*: bold idea, cautious execution.

## Read first

- `../../references/ayal-doron-examples.md` §7 (Netflix sequence, Amazon, Bank Leumi, bold idea / cautious execution) and §3 (the knockout must stand on the anchor).
- `Outputs/Win/<slug>/challenge-card.md`, `01-anchor.md`, and any `02-`/`03-`/`04-` outputs. Otherwise ask: what is the business/team, who is the incumbent or the "already-taken" field, and what is the supreme goal.

## Language

User's language (default Hebrew). Keep: נוקאאוט, סיכון מחושב, "בדיעבד ברור", רעיון נועז – ביצוע זהיר.

## Workflow

### 1) The supreme goal (מטרת-העל)
Ask Hastings' question: *"מה מטרת-העל שלנו?"* — one sentence about the customer, not about us
(Netflix: "the best entertainment for every person, in the way they want to consume it").
If the user has an almost-absurd goal from `/02`, use it. Every knockout candidate must be justified by this sentence.

### 2) The anchor it stands on
From `/01` or ask: what are we the best at? A knockout is the anchor delivered with force and speed.

### 3) Map the fields
| Question | Netflix's answer |
|---|---|
| Which field is **already taken** by the incumbent? (don't fight there) | 9,000 stores |
| What does the customer **pay or suffer** that we could remove? | late fees; $5 shipping; the 18-shekel water bottle |
| Where do they **come to us** — could we **come to them**? | DVDs to the home, then streaming |
| What would managers say **"we'll go bankrupt"** about? | binge, free shipping |
| What move is **already lying here** that nobody takes? | branch manager's photo + phone |

Fill each row for the user's situation. Rows 2, 4 and 5 are where knockouts hide.

### 4) Generate 3–5 knockout candidates
Each candidate in one line, then the **hindsight sentence**: *"In two years everyone will say 'why didn't we
___?'"* If you can't write the hindsight sentence convincingly, it isn't a knockout — it's an improvement.
Include at least one candidate that removes a fee/friction and one that changes *where* value is delivered.

### 5) Calculate the risk honestly
For the top 1–2 candidates:
- **Downside, in numbers:** the Bank Leumi question — *how many will actually call?* ("thirty").
- **What the incumbent cannot copy fast** (structure, incentives, cannibalization) — this is the "force and speed".
- **What breaks** if it works (capacity, margins) — the binge objection.
- **Kill criteria:** what result would make you stop.

### 6) Bold idea, cautious execution (רעיון נועז, ביצוע זהיר)
Design the pilot exactly as Ayal describes: *"only in the south, only in south-east Ramat Gan — I'm testing it."*
- **Scope:** one region / segment / cohort / week.
- **Success signal** and **kill signal**, dated.
- **Scale path:** what happens at 2x, 10x.
- **The next knockout:** Netflix went home → no fees → streaming → production → binge. Ask what the *next* one after this would be; write one line.

### 7) Hand off
Route to `/06-win-habit-infrastructure` for the habits that keep the team at "thrive"; to the user's planning
skills (e.g. a PRD or one-pager tool) for execution detail.

## Output

Save to `Outputs/Win/<slug>/05-knockout.md` if the folder exists; else chat + offer to save.

```markdown
# Knockout — <title>
## Supreme goal
"<one sentence, about the customer>"
## Anchor it stands on
"<from /01>"
## Field map
| Already taken | Customer pays/suffers | Come to them | "We'll go bankrupt" | Already lying here |
| … | … | … | … | … |
## Candidates
| # | Move | Hindsight sentence | Removes | Delivered where |
| 1 | … | "why didn't we …" | … | … |
## Calculated risk (top candidate)
- Downside in numbers: … · Incumbent can't copy because: … · Breaks if it works: … · Kill criteria: …
## Pilot (bold idea, cautious execution)
- Scope: … · Start: <date> · Success signal: … · Kill signal: … · Scale path: …
## The next knockout after this one
"<one line>"
## Next
- /06 for habits · <planning skill> for execution
```

## Guardrails

- A knockout without a hindsight sentence is an improvement; say so rather than inflate it.
- Do not promise outcomes. Numbers in the risk section are the user's estimates, labeled as such.
- The pilot must be genuinely small; if the user resists testing, quote the rule: the idea is bold, the execution is careful.
