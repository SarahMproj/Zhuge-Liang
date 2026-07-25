# Example: Borrowed Arrows for a Product Launch

## Target

A startup plans to launch an AI meeting assistant with the claim:

> The fastest way for small teams to turn meetings into action.

The current launch plan includes a Product Hunt release, founder posts, a free tier, and outbound messages to operations leaders.

## Mission

Generate 500 activated workspaces in 30 days while protecting trust and avoiding a low-retention spike.

## Straw boats

The launch plan is exposed to four independent critics:

1. **Customer critic** — evaluates trust, clarity, and user friction.
2. **Operator critic** — evaluates onboarding, support, capacity, and sequencing.
3. **Competitor critic** — evaluates differentiation and imitation risk.
4. **Security critic** — evaluates recording consent, data access, and privacy assumptions.

## Example volleys

### Arrow A-01 — Customer critic

**Target:** “The fastest way” positioning  
**Attack:** Speed is not the primary barrier to adoption. Teams may resist inviting another bot into sensitive meetings.  
**Impact:** The message may optimize curiosity while failing to address trust.  
**Confidence:** 0.82  
**Verification:** Interview ten target users and compare trust-first versus speed-first landing pages.

### Arrow A-02 — Operator critic

**Target:** Product Hunt as the lead channel  
**Attack:** A concentrated launch may create many low-intent accounts before onboarding and support loops are stable.  
**Impact:** Activation and retention data may be polluted by traffic the team cannot support.  
**Confidence:** 0.76  
**Verification:** Run a 50-workspace private cohort before the public launch.

### Arrow A-03 — Competitor critic

**Target:** Product differentiation  
**Attack:** Transcription and action-item generation are already commodity features.  
**Impact:** The product may be interpreted as a weaker version of established tools.  
**Confidence:** 0.91  
**Verification:** Ask target users to compare the landing page against five known alternatives without showing brand names.

### Arrow A-04 — Security critic

**Target:** Meeting ingestion  
**Attack:** The plan does not define how consent, retention, deletion, or third-party attendee data is handled.  
**Impact:** A trust incident could stop adoption and create legal exposure.  
**Confidence:** 0.95  
**Verification:** Complete a data-flow map and consent review before the public launch.

## Forged ammunition

### Asset R-01 — Trust-first requirement

**Source:** A-01  
**Type:** Requirement  
**Priority:** High  
**Description:** The landing page and onboarding must explain consent, data boundaries, and deletion before emphasizing speed.  
**Completion condition:** At least 70% of private-cohort users report understanding how meeting data is handled.

### Asset E-01 — Private cohort experiment

**Source:** A-02  
**Type:** Experiment  
**Priority:** High  
**Description:** Launch with 50 invited workspaces before opening Product Hunt traffic.  
**Completion condition:** At least 60% activate and 40% remain active after two weeks.

### Asset P-01 — Positioning change

**Source:** A-03  
**Type:** Positioning change  
**Priority:** Critical  
**Description:** Replace generic speed positioning with a differentiated promise tied to a specific workflow or team type.  
**Completion condition:** In blind comparison, at least 60% of target users can identify the product's unique use case.

### Asset M-01 — Consent and retention controls

**Source:** A-04  
**Type:** Mitigation  
**Priority:** Critical  
**Description:** Document and implement attendee notice, recording consent, retention defaults, deletion, and workspace access controls.  
**Completion condition:** Security review is complete and all critical data-flow questions have owners and implemented controls.

## Recommendation

`proceed_with_changes`

The launch concept is viable, but the current plan should not proceed unchanged. The highest-value arrows reveal that trust, differentiation, and operational sequencing are more important than maximizing first-day traffic.

## Why this is Borrowed Arrows

The critics did not merely vote for or against the plan. Their attacks were converted into launch requirements, experiments, mitigations, and positioning changes that make the campaign stronger.
