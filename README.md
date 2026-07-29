# Read Well

**The standard, readable and copy-pasteable: [kaladinx.github.io/read-well](https://kaladinx.github.io/read-well/)**

A writing standard for LLMs. Spend hours a day reading a model's prose and that prose is forming yours; the default style dulls your ear and blunts your thinking. This repo replaces it with the old standard: clear, concrete, vigorous, ordered English in the tradition of the progymnasmata and of Orwell, Lewis, Strunk, and Feynman.

You are what you consume; read well.

## Two ways to use it

### 1. As an Agent Skill

For Claude Code, claude.ai, and other tools that support [Agent Skills](https://agentskills.io). [`SKILL.md`](./SKILL.md) gives the model the standard for everything it writes, and a multi-pass mode for editing existing text: tells, then flab, then force and order, gated by five questions.

```sh
git clone https://github.com/KaladinX/read-well
mkdir -p ~/.claude/skills
cp -r read-well ~/.claude/skills/read-well
```

Per-project instead: copy the folder into `your-repo/.claude/skills/`.

### 2. As a prompt

For any other LLM, paste into the system prompt or custom instructions:

- [`prompts/system-prompt.md`](./prompts/system-prompt.md): the full standard.
- [`prompts/short.md`](./prompts/short.md): compressed for tight character limits.

## What it looks like

| Before | After |
| --- | --- |
| The report is generated once per week by the server. | The server generates the report once a week. |
| A brief network drop won't lose your work. | A brief network drop leaves your work intact. |
| A revoked token can't be un-revoked, only replaced with a new one. | A revoked token stays revoked. Replace it with a new one instead. |

The standard also knows what to keep. "There is no Save button" is a correct sentence: the absence is the point. Judge; don't pattern-match.

## License

MIT. Use it, copy it, adapt it.
