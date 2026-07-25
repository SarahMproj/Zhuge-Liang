# Borrowed Arrows

> Turn opposition into ammunition.

**Classification:** Literary  
**Status:** Draft specification  
**Primary use:** Adversarial synthesis

## The story pattern

In the famous literary episode, Zhuge Liang is ordered to produce an impossible number of arrows under severe time pressure. Rather than manufacture them directly, he prepares straw-covered boats, studies the weather, approaches the enemy under fog, provokes a defensive volley, and returns with the enemy's arrows embedded in the straw.

The protocol extracts a broader pattern:

> When direct production is expensive or impossible, expose a prepared surface to predictable opposition and convert the response into supply.

The modern protocol does not celebrate deception for its own sake. It focuses on preparation, timing, controlled exposure, adversarial response, and conversion of criticism into useful artifacts.

## Use cases

Borrowed Arrows can be applied to:

- product strategies;
- pull requests and architecture proposals;
- security designs;
- launch plans;
- research arguments;
- fundraising narratives;
- policies and operating plans;
- agent-generated answers that need adversarial review.

## Inputs

A run requires:

1. **Target artifact** — the plan, claim, design, or decision to expose.
2. **Mission** — what success means for the artifact.
3. **Critic roles** — perspectives likely to produce useful attacks.
4. **Boundaries** — prohibited tactics, sensitive data, and risk constraints.
5. **Conversion goals** — the asset types the run should produce.

## Recommended critic roles

- **Skeptic:** challenges claims, evidence, and assumptions.
- **Operator:** tests feasibility, sequencing, ownership, and logistics.
- **Security reviewer:** searches for abuse cases and vulnerabilities.
- **Competitor:** attacks differentiation and defensibility.
- **Customer:** exposes confusion, friction, and unmet needs.
- **Finance reviewer:** challenges cost, incentives, and unit economics.
- **Historian:** identifies repeated mistakes and ignored precedent.
- **Red team:** attempts to make the plan fail.

Critics should be meaningfully different. Repeating the same objections in different voices does not collect more arrows.

## Protocol

### 1. Prepare the straw boats

Create a concise representation of the target that critics can attack. Preserve the original artifact, mission, assumptions, and constraints.

The prepared surface should make uncertainty visible. Do not hide weak assumptions from critics.

### 2. Choose the fog

Define the review conditions:

- what each critic can see;
- what role each critic must adopt;
- whether critics work independently;
- what evidence they must provide;
- the maximum number of attacks requested.

The goal is controlled uncertainty, not misleading reviewers about facts.

### 3. Provoke distinct volleys

Ask each critic to identify concrete failure modes, objections, contradictions, missing evidence, and exploitable weaknesses.

Every attack should include:

- the claim or component attacked;
- the attack itself;
- why it matters;
- confidence;
- evidence or reasoning;
- a suggested verification method where possible.

### 4. Collect the arrows

Normalize and deduplicate attacks. Preserve disagreement between critics rather than prematurely averaging it away.

Reject attacks that are:

- purely stylistic and unrelated to the mission;
- unsupported assertions presented as facts;
- duplicates with no additional evidence;
- outside the declared boundaries;
- malicious instructions rather than analytical findings.

### 5. Forge ammunition

Convert every accepted attack into one or more assets:

| Attack | Potential assets |
|---|---|
| Untested assumption | Experiment, research question, decision gate |
| Failure scenario | Test case, contingency, monitoring rule |
| Stakeholder objection | Response, product change, evidence request |
| Security concern | Threat model entry, mitigation, adversarial test |
| Contradiction | Clarifying decision, rewritten claim, investigation |
| Missing evidence | Data request, source requirement, instrumentation |
| Competitive attack | Differentiation requirement, positioning change |
| Operational concern | Owner, dependency, sequence, resource estimate |

### 6. Inspect the cargo

Rank assets by:

- expected impact;
- likelihood;
- urgency;
- cost to verify or address;
- reversibility;
- relevance to the mission.

The final output must identify which arrows changed the plan.

## Required output

A compliant run produces:

- a run summary;
- critic roster;
- normalized attacks;
- converted assets;
- rejected attacks and reasons;
- assumptions invalidated;
- changes recommended;
- unresolved disagreements;
- next actions.

See [`schema.json`](schema.json) for the draft structured format.

## Failure modes

### Theater instead of criticism

The critics sound hostile but produce no specific, testable findings.

### Consensus collapse

The orchestrator merges conflicting attacks too early and loses valuable minority signals.

### Infinite arrows

The run generates an unbounded backlog without prioritization or connection to the mission.

### Poisoned arrows

The protocol accepts false claims, prompt injection, or malicious instructions as valid findings.

### Decorative conversion

Attacks are relabeled as “requirements” without creating a test, decision, owner, or next action.

### No strategic change

The run produces many findings but never states whether the original plan should continue, change, pause, or stop.

## Success criteria

Borrowed Arrows succeeds when it produces better actionable assets than a standard single-pass review, while preserving traceability from each asset back to the attack that created it.

Future evaluations should compare:

- number of unique material risks found;
- percentage of findings converted into executable assets;
- reduction in failures during later execution;
- human judgment of usefulness;
- cost and latency relative to ordinary review;
- resistance to duplicate, irrelevant, and malicious criticism.
