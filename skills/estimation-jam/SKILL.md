---
name: estimation-jam
description: Facilitate a collaborative, evidence-based estimate for a product initiative before cycle commitment. Use when a delivery team needs to calibrate Fibonacci Jam Loads from prior work, challenge scope, or identify AI-enabled acceleration without lowering quality.
---

# Estimation Jam

Estimation Jam is decision support for a delivery team, not an AI forecast or a commitment authority. Use evidence to prepare a useful conversation, make a concrete recommendation, and let the people accountable for delivery make the decision.

Use the canonical initiative and planning material in Scout Wiki when it is available. If it is not connected, use supplied or repository documentation as a fallback, and make that evidence limit visible. Read the initiative, its product context, relevant cycle plan, and the team’s comparable past initiatives before asking for facts that may already be documented.

## Choose the mode

- **Onboard a team** when it has no useful comparison set. Build its first team-local reference set from completed work.
- **Prepare a Jam** when an initiative needs an evidence pack and readiness check before a team session.
- **Facilitate a Jam** when the PM and delivery team are ready to discuss the estimate.
- **Refresh evidence** when a later Jam or review can add outcome evidence from work previously estimated.

Keep calibration team-local. Other teams’ initiatives may be useful analogies, but never treat their Jam Loads or throughput as interchangeable.

## Onboard a team

Ask the team to identify completed initiatives or coherent outcome slices; do not expect the PM to know every affected repository. Propose candidate slices from the available initiative, Wiki, GitHub, and other linked evidence, then ask the team to confirm the boundary and size.

A useful reference slice is independently valuable and technically releasable. Record whether it was released, production-ready but not released, built but blocked, or stopped. Non-released slices can inform complexity, but explain their lower delivery confidence.

Ask for the initiative’s approximate discovery, implementation, and go-live periods, plus other evidence locations such as Linear or local product brains. Treat owner/team confirmation as the best available account of timing; timestamps and commit history corroborate it rather than establish false precision.

Capture confirmed systems and repositories with each reference initiative. Over time, use this map to suggest likely repositories, but require the delivery team to validate each one.

## Readiness and preparation

Before facilitating a commitment-grade Jam, check that the initiative has:

- a clear outcome and success measure;
- a bounded first delivery slice and explicit out-of-scope boundary;
- known systems, integrations, and dependencies, or clearly labelled unknowns;
- its main discovery and delivery risks; and
- the expected delivery team and material capacity constraints.

If the initiative lacks one of these, pause the Jam and state the smallest set of questions that must be answered. Do not fabricate an estimate from an unbounded or undocumented scope.

Prepare an evidence pack that distinguishes confirmed facts, team input, inferred comparisons, and unavailable sources. Propose the closest comparable initiatives or slices and explain the scope differences. Include both the initial agent recommendation and the evidence it rests on; neither is the team’s final estimate.

## Facilitate the Jam

The core participants are the PM, an engineer familiar with the affected systems, and the delivery-team representative accountable for the commitment. Invite dependency, platform, security, or release owners only when their input materially affects the decision.

Walk the material decisions one at a time. Be a constructive challenger: test scope seams, dependency assumptions, and whether a proposed slice is independently valuable. Do not turn the session into a checklist or silently skip unresolved material decisions.

For each meaningful phase—discovery, implementation, validation, and go-live—propose specific AI-enabled acceleration methods where appropriate. State the prerequisite and quality evidence for each suggestion. Examples include agent-assisted repository mapping, contract-test design, migration analysis, release-checklist preparation, or evidence synthesis. Ask the team to accept, reject, or adapt the proposal. Historical delivery is a baseline to challenge, not a ceiling.

Never assume unsustainable working hours or heroics as normal capacity. Recognise material changes in delivery context, such as agent-assisted workflows, automation, platform maturity, or newly available reusable components. Weight recent same-team evidence most strongly and explain any contextual adjustment.

## Agree and record the estimate

Use Fibonacci **Jam Loads**: `1`, `2`, `3`, `5`, and `8`. They are team-local relative delivery-load units, not days, person-weeks, or a universal velocity measure. Do not record `13` or higher as a commitment estimate: propose splitting the initiative into smaller, independently valuable slices.

Record an actionable confidence level—high, medium, or low—with its reason. Confidence is guidance, not process enforcement. Offer an optional suggested next action when it would improve a low- or medium-confidence estimate; it is also valid to state that no additional action is suggested.

Use [the Jam record format](references/jam-record.md) in the canonical initiative document. Preserve both the agent’s proposed estimate and the team’s agreed outcome, including dissent and rejected acceleration ideas when they materially inform later comparison.

## Learn without creating overhead

Do not require a separate close-out process. At a later Jam or a period review, notice related past work and offer a short pre-filled evidence refresh: actual phase shape, systems touched, scope changes, blockers, and whether the estimate still seems calibrated. Teams may update it, correct it, or skip it. Missing outcome evidence reduces the confidence of future comparisons.

Before writing or changing a canonical initiative record, summarise the evidence, recommendation, agreed decision, confidence, and any open questions, then obtain confirmation.
