# Contributing to Zhuge Liang

Zhuge Liang welcomes thoughtful proposals for strategic patterns, specifications, examples, evaluations, and implementations.

The project is currently unlicensed and all rights are reserved. Opening a contribution does not change that status. Do not submit material you are not authorized to share.

## Proposing a stratagem

A proposal should include:

1. **Name** — the story, episode, writing, or character pattern.
2. **Source classification** — historical, literary, composite, or modern interpretation.
3. **Story summary** — concise and responsibly framed.
4. **Strategic principle** — the transferable idea.
5. **Agent behavior** — what an agent does differently.
6. **Inputs and outputs** — preferably structured.
7. **Use cases** — where the protocol helps.
8. **Failure modes** — where the metaphor or implementation breaks.
9. **Evaluation plan** — how usefulness can be tested.
10. **Source notes** — citations or references when available.

## Quality test

Before submitting, ask:

- Is the story essential to understanding the protocol, or merely decoration?
- Is the protocol implementable by someone else?
- Does it produce a usable artifact or decision?
- Can its benefit be evaluated?
- Does it distinguish historical record from literary tradition?
- Does it preserve safety, privacy, and human authority?

## Suggested structure

```text
stratagems/<slug>/
├── STRATAGEM.md
├── SKILL.md
├── schema.json
└── evals/
```

Not every first proposal needs all four files. A strong `STRATAGEM.md` is enough to begin discussion.

## Pull requests

Keep pull requests focused. Explain:

- what strategic behavior is introduced or changed;
- why the source story supports that behavior;
- how the output can be used;
- what remains uncertain;
- how the change was tested or reviewed.

## Historical care

Do not present famous literary scenes as verified biography. Use the classifications described in [`docs/historical-vs-literary.md`](docs/historical-vs-literary.md), and mark modern interpretation clearly.

## Conduct

Critique ideas precisely and respectfully. This project studies adversarial thinking, but productive opposition is not personal hostility. The goal is to collect arrows and forge better work.
