# seek-truth-from-facts

[中文](README.md)

An AI analysis skill based on the methodology of **"Emancipate the Mind, Seek Truth from Facts, Keep Pace with the Times"**, combined with *On Contradiction* and *On Practice*. Enables independent, objective, and dialectical feasibility analysis. Refuses sycophantic agreement and unconstrained speculation.

## Core Principles

| Principle | Role |
|-----------|------|
| **Emancipate the Mind** | Break habitual thinking; identify and suspend prior assumptions |
| **Seek Truth from Facts** | Ground analysis in objective reality; derive conclusions from facts, not expectations |
| **Keep Pace with the Times** | Dynamic, developmental perspective; identify the particularity of the current stage |
| **On Contradiction** | Locate the principal contradiction, determine its nature, analyze transformation conditions |
| **On Practice** | Validate understanding; design actionable paths with verifiable checkpoints |

## Installation

### Claude Code / Cursor

Both tools use the same skill format — one command covers both.

Install to current project (run from git repo root):

```bash
mkdir -p .claude/skills
git clone https://github.com/BiscuitCoder/seek-truth-from-facts.skill .claude/skills/seek-truth-from-facts
```

Or install globally (available in all projects):

```bash
git clone https://github.com/BiscuitCoder/seek-truth-from-facts.skill ~/.claude/skills/seek-truth-from-facts
```

### OpenClaw

```bash
git clone https://github.com/BiscuitCoder/seek-truth-from-facts.skill ~/.openclaw/workspace/skills/seek-truth-from-facts
```

## Use Cases

- Evaluating whether an idea or plan is feasible
- Analyzing the principal contradiction of a complex problem
- Designing an action path with verifiable checkpoints
- Any situation requiring prevention of sycophantic agreement or false optimism

## Language

`SKILL.md` is the **single entry point**: it contains full instructions in both Chinese and English, plus rules to match the user's first-message language. You no longer need two separate skill files.

## Structure

```
seek-truth-from-facts/
├── SKILL.md                          # Bilingual skill entry (YAML frontmatter + CN/EN body)
└── references/
    ├── contradiction-theory.md       # On Contradiction — analytical tool
    └── practice-theory.md            # On Practice — verification and action guide
```

## License

MIT
