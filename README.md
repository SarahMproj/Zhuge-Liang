# Zhuge Liang

### Executable stratagems for agents facing uncertainty.

Zhuge Liang transforms the stories, methods, dilemmas, and strategic character of Kongming into reusable protocols for modern AI agents.

This is not a personality prompt.

This is not another generic multi-agent framework dressed in Three Kingdoms vocabulary.

Each legend becomes an executable strategic behavior:

```text
Story -> Strategic principle -> Agent protocol -> Evaluation
```

## Why Zhuge Liang?

Zhuge Liang endures as more than a brilliant tactician. Across history and legend, he represents preparation, patience, leverage, loyalty, disciplined counsel, political intelligence, logistics, adaptation, and service to a mission larger than himself.

Modern agents are often optimized to produce the next answer. Zhuge Liang explores a different question:

> How should an agent behave when the terrain is uncertain, resources are constrained, stakeholders disagree, and the first plan will not survive contact with reality?

## The first stratagem: Borrowed Arrows

> Turn opposition into ammunition.

Inspired by the famous story of borrowing arrows with straw boats, this protocol sends a plan, artifact, or decision toward deliberate criticism and converts the returning attacks into useful assets.

```text
Criticism      -> requirements
Attacks         -> tests
Objections      -> responses
Failures        -> fixtures
Contradictions  -> research questions
```

Example interface:

```bash
zhuge borrow-arrows ./proposal.md \
  --critics skeptic,operator,security,competitor
```

Example result:

```text
72 arrows collected

18 untested assumptions
14 failure scenarios
12 stakeholder objections
11 product improvements
 9 adversarial test cases
 8 missing evidence requests
```

Read the full protocol in [`stratagems/borrowed-arrows/STRATAGEM.md`](stratagems/borrowed-arrows/STRATAGEM.md).

## Planned stratagems

| Stratagem | Agent behavior |
|---|---|
| **Borrowed Arrows** | Convert opposition, criticism, and failure into reusable assets. |
| **Longzhong Plan** | Map the entire field before choosing a campaign. |
| **Three Visits** | Acquire sufficient context and commitment before revealing strategy. |
| **Empty Fort** | Reason about what others infer from incomplete signals. |
| **Seven Captures** | Build voluntary alignment through iterative understanding. |
| **Memorial to the Throne** | State duty, counsel, risk, and required authority before consequential action. |
| **Seven-Star Lamp** | Preserve mandate, identity, and strategic state across context death. |

## Repository structure

```text
Zhuge-Liang/
├── docs/
│   ├── vision.md
│   └── historical-vs-literary.md
├── stratagems/
│   └── borrowed-arrows/
│       ├── STRATAGEM.md
│       ├── SKILL.md
│       └── schema.json
├── examples/
│   └── borrowed-arrows/
│       └── product-launch.md
└── CONTRIBUTING.md
```

## Design principles

1. **The story must matter.** Removing the story should damage the protocol, not merely its branding.
2. **The output must be usable.** Every stratagem produces structured evidence, decisions, or artifacts.
3. **The protocol must be testable.** A compelling metaphor is not enough; each stratagem should have evaluations.
4. **History and legend stay distinct.** The project will identify whether a pattern is historical, literary, or a modern interpretation.
5. **Strategy serves the mission.** Cleverness without duty, consequences, or logistics is not Kongming.

## Status

Zhuge Liang is in its earliest design phase. The first milestone is a portable specification and reference implementation for Borrowed Arrows.

No license has been granted for this repository at this time. All rights are reserved unless explicitly stated otherwise.
