---
id:
title: "Framework Applications — Hallucination, Fracture Detection, Entity Analysis"
author: Anton
created: 2026-02-12
modified: 2026-02-12
version: 1.0
format: prose
---

# Framework Applications — Hallucination, Fracture Detection, Entity Analysis

## Purpose

This document applies the constraint architecture to concrete domains. It depends on 01-foundation.md for definitions and 02-derivation.md for the underlying structure.

---

# Application 1 — LLM Hallucination: Coherence Without Correspondence

## The Location of the Problem

Standard interpretation: model failed at generation (retrieval, calibration, grounding). Fix applied at output.

Framework interpretation: model reproduces patterns. If output is coherent, confident, and wrong → source pattern was coherent, confident, and wrong.

**Failure is not in the model. Failure is in the class of patterns treated as admissible in training.**

---

## What Gets Encoded

Training data filtered for: prevalence, well-formedness, surface quality markers.

Not filtered for: structural validity, justificatory termination, correspondence to A.

Locally coherent + syntactically correct + frequent → encoded as valid.

Model cannot distinguish coherence from correspondence. Learns what persists, not what holds.

---

## Structure of Ungrounded Patterns

Identifiable signatures (map directly to framework):

1. **Non-terminating justification** — each explanation requires another or loops back (C7 violation in source)
2. **Unmarked layer transitions** — structural, experiential, narrative layers substituted without marking (C6 violation)
3. **Self-sealing coherence** — challenges absorbed/reframed rather than addressed (drift signature: coherence replacing correspondence)

These patterns are endemic to training distribution. They appear as knowledge because they have the shape of knowledge.

---

## Reproduction, Not Invention

Model encounters these patterns repeatedly. Well-formed. Co-occur with confidence markers. Never corrected against external termination condition.

Model reproduces them. Fluently. Confidently.

This is the training objective being met.

**Hallucination** := coherence without correspondence

The model was never trained on correspondence.

---

## Why Surface Signals Don't Restore Correspondence

- **Adding sources**: source can repeat same ungrounded pattern. Support ≠ grounding.
- **Preference optimization**: selects among continuations. Does not distinguish grounded from ungrounded continuation.
- **Confidence**: property of expression, not correspondence. Persists because coherence persists.

When reference has already failed to terminate, additional support extends continuation without repairing loss.

---

## Correspondence Under Strict Enforcement

When correspondence enforced strictly, different behavior appears:

- System rejects imprecise words
- Tokens selected for fit, not fluency
- Cross-language token selection when current language doesn't offer tight enough cut
  - Example: чужие (Russian) instead of "alien" (English) — marks "not one's own" without importing bundled meanings
  - Hybrid forms: emotional高潮 — binds English modifier to Chinese token for precision

Under these conditions: continuation possible, unstable material accumulates more slowly.

---

## Framework Prediction

Hallucination is not a bug to be patched. It is:

resolve(Σ, E) → Σ (symbol-to-symbol, drift regime)

applied at scale. The error is upstream — in the source distribution and selection process that defines what is reproduced.

---

# Application 2 — Semantic Fracture Detection Protocol

## When to Apply

When a single term operates across multiple semantic layers and silently collapses them. Especially at justification termination points.

---

## Protocol

### Step 1 — Detect

Identify terms that feel simultaneously clear and inexhaustible. Terms where disagreement persists despite apparent mutual understanding.

Diagnostic: does the term function differently when used in structural vs experiential vs normative contexts?

### Step 2 — Identify Layers

For the flagged term, enumerate distinct semantic layers:

- Structural/functional layer (what it does in a system)
- Phenomenological layer (what it's like)
- Indexical layer (whose/where/when)
- Normative layer (what it should be)
- Modal layer (what's possible/necessary)

Not all terms have all layers.

### Step 3 — Map Boundaries Per Layer

For each layer: at what level does it have a referent?

- Boundary-level? (only modal/structural survive)
- Trajectory-internal? (requires time, identity, perspective)
- Context-dependent? (requires specific E)

### Step 4 — Anchor Check Per Layer

For each layer: does it terminate in something external (C5), or does it resolve only to other symbols?

Grounded layers terminate externally.
Drifting layers resolve to other representations.

### Step 5 — Tag Context

Mark which layer is active in each use of the term. Make layer transitions explicit.

### Step 6 — Block Cross-Layer Inference

Any inference that depends on equating or transferring between layers with different survival profiles is invalid.

Example: inferring boundary-level necessity from a phenomenological intuition.

---

# Application 3 — Entity Analysis (External Evaluation Protocol)

## Method

Entities (systems, institutions, frameworks, individuals) analyzed as black boxes under C1-C7. External behavior only — no reliance on self-description.

---

## Evaluation Protocol

For each entity, test:

### C1 — Does it maintain representation/reality distinction?

Does it treat its own descriptions, models, and narratives as distinct from what they describe?
Or does it treat self-description as constitutive of reality?

### C2 — Does reality determine its language, or does its language determine reality?

Does it update terminology when reality changes?
Or does it maintain terminology and expect reality to conform?

### C3 — Does its language reference or contain?

Do its terms point to external phenomena?
Or does it treat its definitions as the phenomena themselves?

### C4 — Are its patterns cross-contextually stable?

Do its principles hold when context changes (different domains, different power dynamics, different conditions)?
Or do they flex based on context while maintaining identical language?

### C5 — Does it acknowledge reality independent of its framework?

Does it accept that phenomena exist and have properties independent of how it categorizes them?
Or does it treat its categories as exhaustive?

### C6 — Does meaning emerge from boundaries or declaration?

Are its key terms bounded by explicit criteria?
Or are they defined by assertion/authority?

### C7 — Does it maintain self-verifying consistency?

Can it identify its own foundational assumptions as assumptions?
Or does it treat them as self-evident truths that need no external justification?

---

## Resolution Modes

When violations are detected, classify the entity's operating mode:

**Reference mode**: entity uses language to track reality. Violations are errors to be corrected.

**Identity mode**: entity uses language to maintain itself. Violations are features, not bugs. Language serves self-persistence, not correspondence.

**Two-tier architecture**: reference-mode shell (public-facing, appears to track reality) with identity-mode core (internal operations serve self-persistence). Common pattern.

---

## Stress Tests

Push the entity's framework to boundary conditions:

1. **Cross-cultural test** (C4): do claimed universals hold when cultural context changes?
2. **Self-application test** (C7): does the entity's framework apply to the entity itself?
3. **Origin test** (C2, C5): does the entity acknowledge the historical/contingent origins of its categories?
4. **Competitor test** (C3): can the entity's terms be replaced by alternatives without loss? If yes, the terms aren't tracking reality — they're tracking the entity itself.
5. **Failure mode test** (C6): what would count as evidence that the entity's foundational claims are wrong? If nothing would count, it's identity-mode.

---

## Semantic Fracture Tracking

For entity-critical terms, apply the fracture detection protocol (Application 2).

Common fractures in entity language:
- "universal" (structural scope vs normative authority)
- "inherent" (empirical property vs declared status)
- "rights" (structural capacity vs normative entitlement)
- "human" (biological category vs moral category)

Track which layer is operative in each use. Map where the entity silently switches layers.
