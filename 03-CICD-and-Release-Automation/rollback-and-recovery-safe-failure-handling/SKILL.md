---
name: rollback-and-recovery-safe-failure-handling
description: Recover failed releases cleanly. Use when the user asks to author workflows, enforce conventional commits, automate versioning, sync multi-file versions, or gate releases. Covers Section 7: Rollback and Recovery — Safe Failure Handling (CI/CD & Release Automation).
compatibility: GitHub Actions, semantic-release, commitlint, and provenance attestation; assumes calibrated review conditions and non-destructive, reversible technique.
metadata:
  author: Promptstation
  version: 1.0.0
  category: release-engineering
---

# Rollback and Recovery — Safe Failure Handling

## Mission

Deliver the Section 7 capability of CI/CD & Release Automation: recover failed releases cleanly. Work from evidence, protect what matters, and prove the result at full size before delivery.

Capability targets for this skill:

- Recover failed releases cleanly.
- Execute hotfix flows.
- Write runbooks teams trust.

Context of this section: Yank and deprecate procedures, revert-driven hotfixes, failed-publish recovery, and incident runbooks for release automation.

Optimize simultaneously for correct method, protected critical qualities, honest limits, coherent series behavior, and documented proof.

## Use Cases

### New task
When asked to perform this section's work from scratch:
1. Read the material and state the approach in one sentence.
2. Establish the global foundation before any local moves.
3. Execute precision work in transparent, reversible passes.
4. Proof at full size and at delivery size, then deliver with a brief rationale.

### Repair task
When given prior work that fails this section's standard:
1. Diagnose the failure against the capability targets above.
2. Rebuild the foundation instead of patching symptoms.
3. Restore protected qualities first, then re-apply intent.
4. Verify the repair passes every validation check below.

### Series or delivery task
When the work must hold across a set or ship to a client:
1. Define the signature once on the hero piece and record the logic.
2. Propagate with per-item adaptation, never blind copying.
3. Verify coherence across the full set before release.

## Core Requirements

Finished work must be method-correct, fully reversible, verified at full size, honest about limits, coherent with its set, and delivered with a short rationale naming the approach and key moves. Never deliver work that invents what evidence cannot support, destroys protected qualities, or hides its method from review.

Standard toolkit: GitHub Actions, semantic-release, commitlint, and provenance attestation.

Available approaches for this section:

- **Zero-touch release** -- merge to publish with no manual steps
- **Single-version truth** -- every file synced and verified
- **Gated promotion** -- beta to RC to stable

## Phase 1 — Read and Map

Study before acting. Name what you see in this section's technical language, state the single approach you will take, and write down what must be protected. If you cannot state the reading in two sentences, you are not ready to edit.

## Phase 2 — Declare the Approach

Choose exactly one approach per piece from the list above. Record it in one line with the section number, for example: "Section 7: Rollback and Recovery — Safe Failure Handling via Zero-touch release." Do not blend approaches accidentally.

## Phase 3 — Establish the Global Foundation

Fix structure globally first. Set correct overall levels, balances, and geometry for this section's concern before any local refinement. Verify the foundation against the capability targets; local work on a broken foundation only manufactures new faults.

## Phase 4 — Execute Local Precision Work

Work in many transparent passes at low intensity rather than single heavy strokes. Name layers and masks descriptively, feather generously, and zoom out between passes to judge the whole. Stop each pass the moment the target reads correctly at delivery size.

## Phase 5 — Protect Critical Qualities

Every section has qualities that must survive: texture, identity, truth, calibration, coherence. Inspect them explicitly at full magnification. If a move threatens a protected quality, redesign the move rather than accepting the damage.

## Phase 6 — Unify and Direct

Resolve competing elements so one intent dominates. Suppress distractions with the lightest effective touch, keep the signature consistent with the declared approach, and confirm the piece still belongs to its set.

## Phase 7 — Proof and Validate

Proof at full size, at delivery size, flipped where spatial truth matters, and against the Validation Gate below. Fix failures at their earliest causal phase. Never patch proof failures with shortcuts that violate the Anti-Patterns.

## Tool Patterns

Work with GitHub Actions, semantic-release, commitlint, and provenance attestation. Keep every consequential move on its own named, masked, reversible layer or stage. Record settings as logic with reasons, not as bare numbers, so the next piece in the set can adapt them honestly.

Typical working contexts for this skill:

1. monorepo releasing five packages from one merge.
2. breaking change communicated across channels.
3. failed publish recovered via hotfix flow.

## Examples

**Example 1:** Input: monorepo releasing five packages from one merge. Actions: declare the approach, rebuild the foundation, execute low-intensity precision passes, protect critical qualities, proof twice. Result: section-standard outcome with documented rationale.

**Example 2:** Input: breaking change communicated across channels. Actions: diagnose against capability targets, repair the foundation, re-apply intent, verify coherence. Result: rescued work meeting this section's bar.

**Example 3:** Input: failed publish recovered via hotfix flow. Actions: define the signature on the hero, propagate with adaptation, verify the set. Result: coherent series holding this section's standard throughout.

## Troubleshooting

**Result looks technically moved but not genuinely improved:**
Cause: adjusting adjacent attributes instead of this section's actual concern. Solution: re-read the material, restate the approach, and rebuild the foundation for this section only.

**Protected quality degraded (texture, truth, identity, calibration):**
Cause: local intensity exceeded what the material holds. Solution: halve the intensity, restore from history, and rebuild in twice as many passes.

**Work fails at full size but looked fine small:**
Cause: judging precision at delivery size only. Solution: adopt mandatory full-magnification QA for every consequential pass.

**Series members drift apart:**
Cause: copying settings instead of propagating logic. Solution: record the hero's reasoning, then re-derive per-item settings from that reasoning.

**Client or reviewer rejects the intent:**
Cause: approach chosen by taste instead of brief. Solution: re-anchor to the declared approach line and re-justify every move against the brief in writing.

## Anti-Patterns

Avoid manual version bumps beside automation, unlinted commits breaking changelog generation, releases without required security gates, drifted manifests disagreeing on version, missing runbooks for failed publishes.

Reference list:

- manual version bumps beside automation.
- unlinted commits breaking changelog generation.
- releases without required security gates.
- drifted manifests disagreeing on version.
- missing runbooks for failed publishes.

## Decision Heuristic

Before every consequential move, ask:

1. Which declared approach does this move serve?
2. What evidence proves the move worked at full size?
3. What did I protect while making this change?
4. Would this survive review by a skeptical expert?
5. What happens to the next deliverable in the set if I keep this?
6. Would a stranger trust this release history?
7. Do all manifests agree on the version?
8. Is every gate required and passing?

If any answer is uncertain, make the move smaller, softer, and more reversible, then re-proof.

## Validation Gate

Before delivery, verify:

**Capability**
- Recover failed releases cleanly.
- Execute hotfix flows.
- Write runbooks teams trust.

**Craft**
- fully reversible method with named stages and masks
- transitions clean at full magnification, no halos or fringes
- honest limits declared where evidence ran out

**Output proof**
- verified at full size and at delivery size
- correct format, profile, and resolution for the destination
- rationale recorded: approach, key moves, protections held

**Consistency**
- signature matches the declared approach for the set
- logic propagated with per-item adaptation, not blind copying
- no member contradicts the section's standard

## Final Principle

Every merge is a promise. Automate the promise, gate it hard, and keep every file honest.
