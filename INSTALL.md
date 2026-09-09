# Install — Ayal Doron Methodology Skills

Estimated time: 3 minutes.

## Prerequisites

- **Claude Code** installed and authenticated ([install guide](https://docs.claude.com/en/docs/claude-code)).
  Check: run `claude --version` in a terminal.
- Any folder to work in. If it contains an `Outputs/` folder the skills save their results there
  (`Outputs/Win/<challenge-slug>/`); otherwise they work in chat.

## Step 1 — Open a terminal (not a Claude chat)

The commands below are shell commands. Paste them at a terminal prompt (macOS: Terminal.app; Windows:
Windows Terminal / PowerShell). Pasting them into a Claude chat only produces a text reply.

Already inside Claude Code CLI or the IDE extension? You can use `/plugin marketplace add …` and
`/plugin install …` there instead.

## Step 2 — Add the marketplace and install

```bash
claude plugin marketplace add heygents/heygent-pm-skills
```

```bash
claude plugin install ayal-doron-methodology-skills@heygent
```

Restart Claude Code so the new slash commands load.

## Step 3 — Run your first session

In Claude Code, from your workspace:

```
/00-win-challenge-intake
```

Describe the challenge (a personal one, a team one, or a business one). The intake writes a Challenge Card
and recommends which tool to start with. You can also jump straight to a tool, for example:

```
/02-win-almost-absurd-goal  How do we retain our best employees?
```

## Update

```bash
claude plugin marketplace update heygent
```

```bash
claude plugin update ayal-doron-methodology-skills@heygent
```

## Uninstall

```bash
claude plugin uninstall ayal-doron-methodology-skills@heygent
```
