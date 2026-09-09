# Ayal Doron Methodology Skills

A Claude Code plugin that turns Dr. Ayal Doron's "how to be unreplaceable" toolbox into seven
conversational skills. The method works at three levels — **a person, a team, or a business** — and
follows one rule:

> A predictable question produces a predictable answer from the same playing field.
> An almost-absurd question forces you to invent a new playing field — on the same half hour of thinking.

The skills: a challenge intake, the **anchor** ("what am I the best in the world at?"), the **four tools
for inventing a new playing field**, and the **habit infrastructure** that makes it stick.

## Skills

| # | Slash command | Ayal's tool | What it does |
|---|---------------|-------------|--------------|
| 00 | `/00-win-challenge-intake` | — | Conversational intake: who, the challenge verbatim, what was tried, constraints, the 7-second anchor, the uncertainty ladder. Writes a Challenge Card to `Outputs/Win/<slug>/` and routes to the right tool. Never solves. |
| 01 | `/01-win-irreplaceable-anchor` | העוגן — במה אני הכי מעולה בעולם | Find the one thing you / the team / the business is the best at, at a real radius. 7-second test, "call Ruti" test, weekly sharpening, the jump from *coping* to *thriving* on uncertainty. |
| 02 | `/02-win-almost-absurd-goal` | הקצנת המטרה | Rewrite the goal as received into an almost-absurd goal using Ayal's escalation grammar ("not only… but…", "every baby gets a key", "what does school have that no home has"), test it, redefine the primitives, sketch three new-field directions. |
| 03 | `/03-win-extreme-obstacle` | הקצנת המכשול | Multiply the obstacle (2 weddings → 5, 4 students → 25, 3 → 3,000) until the current tactic collapses; redefine what the goal really is ("what does the groom actually do?"); build a solution ladder from helicopter to nearly free. |
| 04 | `/04-win-extreme-persona` | דמות קיצונית — "1 + רעיון של מישהו" | Pick 2–3 contrasting public figures (Trump ↔ Gandhi, Rami Levy), get each one's concept in 60 seconds, extract their single "chicken for a shekel" message, translate it back to your context. |
| 05 | `/05-win-calculated-knockout` | סיכון מחושב / נוקאאוט | Find the move that sounds crazy now and obvious in hindsight (Netflix, Amazon, Bank Leumi), anchor it to the supreme goal, quantify the downside, design a bold-idea / cautious-execution pilot and name the next knockout. |
| 06 | `/06-win-habit-infrastructure` | תשתית של הרגלים | Design the habits, environment changes and contagion rules (the judo team's 90-minute isolation) that sit between the want and the goal; answer "what do we stop doing" in the AI era. |

All seven read one shared reference, [`references/ayal-doron-examples.md`](references/ayal-doron-examples.md)
— the full bank of Ayal's principles and real examples, so the skills quote him rather than improvise.

## How the tools chain

Ayal's own order, which `/00` recommends by default:

```
/01 anchor → /02 absurd goal → /03 extreme obstacle → (02 + 03 combined) → /04 persona → /05 knockout → /06 habits
```

Every skill also runs alone: if there is no Challenge Card it asks the two or three questions it needs.

**Worked examples** — a full chain on a business challenge, each skill on its own, a team case, a personal
case, and a workshop format: [docs/EXAMPLES.md](docs/EXAMPLES.md).

## Language

Skill instructions are in English; each skill **replies in the language the user writes in** (Hebrew by default)
and keeps Ayal's Hebrew key terms (מגרש חדש, מטרה כמעט מופרכת, הקצנת המכשול, נוקאאוט, עוגן).

## Install

Open a terminal (not a Claude chat) and run:

```bash
claude plugin marketplace add heygents/heygent-skills
claude plugin install ayal-doron-methodology-skills@heygent
```

Then in Claude Code, in any workspace, run `/00-win-challenge-intake` and describe what you're stuck on.
Outputs are saved under `Outputs/Win/<challenge-slug>/` when an `Outputs/` folder exists; otherwise the
skills work in chat and offer to save.

The `heygent` marketplace manifest lives in [heygents/heygent-skills](https://github.com/heygents/heygent-skills).
See [INSTALL.md](INSTALL.md) for the step-by-step version.

## Credits — Dr. Ayal Doron

The methodology, the framing and every example in this plugin belong to **Dr. Ayal (Eyal) Doron** —
researcher, author and one of Israel's leading voices on creativity, mental resilience and education in
the AI era. The skills are a structured adaptation of the toolbox he presented at Elementor Day
(9 September 2026): the irreplaceable anchor, the four tools for inventing a new playing field, and the
habit infrastructure. If these skills help you, the credit is his.

- Website, books, lectures and workshops: **https://www.eyaldoron.co.il/**

This plugin does not claim authorship of the ideas and is not affiliated with or endorsed by Dr. Doron.
Plugin code and skill text: MIT, © HeyGent.
