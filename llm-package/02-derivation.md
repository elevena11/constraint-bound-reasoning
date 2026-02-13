---
id:
title: "Framework Derivation — From Minimal Conditions to Boundary & Trajectory"
author: Anton
created: 2026-02-12
modified: 2026-02-12
version: 1.0
format: hybrid
---

# Framework Derivation — From Minimal Conditions to Boundary & Trajectory

## Purpose

This document contains the full derivation. It depends on 01-foundation.md for symbol definitions and constraint specifications. Two parts:

- **Part A**: Derives the boundary (admissibility structure) from minimal conditions for reference
- **Part B**: Derives consequences for systems embedded in trajectories
- **Part C**: Proves epistemic-ontological convergence

---

# PART A — Termination of Justification

Question: What is the minimum precondition for first-principles reasoning and linguistic reference to be possible at all?

---

## Block 1 — Non-emptiness

Assume U = ∅. Then: ¬poss(ref), ¬poss(reas), ¬poss(question).

But: question occurs (performative constraint).

Therefore: U ≠ ∅

Grants: bare possibility of reference, reasoning.
Does not grant: difference, identity, time, structure.

---

## Block 2 — Invariance

Assume: ∀c ∈ U : free_var(c)

Then: ref(Σ,t₁) ≠ ref(Σ,t₂) for all Σ. Reference fails.

Total instability functionally equivalent to ∅.

Therefore: ∃I : inv(I) — structure not freely variable.

Grants: possibility of reference, memory, tracking.
Does not grant: identity, difference, objects, time.

---

## Block 3 — Difference

Assume: const(U) — ∀c₁,c₂ : c₁ = c₂

Then: no contrast, no selection, no naming. Reference fails.

Therefore: ∃c₁,c₂ : c₁ ≠ c₂

Grants: selection, contrast, "this rather than that."
Does not grant: identity across states, time, objects.

---

## Block 4 — Constrained Difference

Assume: free_var(U) — all transitions unrestricted.

Then: ref unstable across difference. Memory fails. Pattern tracking fails.

free_var(U) → ¬stable(ref)

Therefore: ∃I : ∃c₁,c₂ (¬allowed(c₁ → c₂))

Define: A := { c ∈ U | I(c) }

Grants: stable reference, pattern tracking, reasoning about admissibility.
Does not grant: identity, time, causality, objects.

---

## Block 5 — Admissibility Structure

Constrained difference induces partition:

A ⊂ U (admissible)
Ā = U \ A (inadmissible)

This is the **boundary (B)**: the distinction between allowed and disallowed configurations.

Static. Modal. No dynamics.

---

## Block 6 — No Time at Boundary

Time requires: ord(t₁,t₂), succ relation — extra structure beyond {U, I, A}.

Boundary defined as minimal structure for admissibility.

Therefore: ¬tm(B), ¬ord(B), ¬chg(B), ¬evt(B)

Nothing happens at B. Only: what is allowed and what is not.

---

## Block 7 — No Re-identification at Boundary

same(c₁,c₂) requires: tm ∧ ord ∧ persistence rule.

At B: ¬tm ∧ ¬ord

Therefore: ¬id(B). No objects, no "same again."

Only: membership in A.

---

## Block 8 — Semantic Back-Projection Rule

Derivation used trajectory-internal language (time, persistence, stability) to express boundary-level roles.

Now that B is characterized: earlier blocks must be re-expressed using only surviving layers (L).

**Rule**: roles preserved, semantic carriers replaced.

---

## Block 9 — Refinement of Block 2

Original: "stable enough to persist over time"
Projected: "invariant — structure not free to vary arbitrarily"

stableᵗ → inv(I)

Role (prevent total arbitrariness) preserved. Temporal carrier dropped.

---

## Block 10 — Boundary ≠ World

World requires: obj, id, prs, rel. B has none.

Therefore: ¬world(B), ¬ont(B).

B is the condition of possibility for worlds, not itself a world.

---

## Block 11 — World = Trajectory

A world arises as ordered path through A:

τ ⊂ A, with ord(t), cᵣ : t ↦ cᵣ(t) ∈ A

Generates: tm, chg, id, obj, evt, world — all trajectory-internal.

---

## Block 12 — No Selector

why(τ₀ rather than τⱼ)?

- Inside τ: circular (uses facts presupposing τ₀)
- At B: no sel, no tm, no act
- Meta-level: same question reappears → regress

¬∃ grounded selector. Explanation bottoms out at admissibility.

---

## Block 13 — Error is Semantic

Modal structure complete. No gap. Question persists.

Therefore: error ∈ semantics, not structure.

symbols(Q) ⊄ L → ¬welltyped(Q at B)

---

## Block 14 — Words Bundle Layers

Each word compresses multiple semantic layers.

Example: "actual" bundles modal (admissible) + experiential (happening to us).
Inside τ: context disambiguates silently.
At B: experiential layer has no referent.

---

## Block 15 — Layer Survival at Boundary

At B:
- Survive: modal, structural, constraint layers (L)
- Undefined: phenomenological, indexical, temporal layers (Lτ)

Undefined ≠ false. Referent absent.

Half-working symbols = worst case for reasoning.

---

## Block 16 — Oscillation Generates Paradox

"Why this path?" contains:
- "this" = structural pointer (survives) + indexical (undefined)
- "why" = structural dependency (survives) + causal explanation (undefined)
- "actual" = modal (survives) + experiential (undefined)

Mind oscillates between surviving and undefined layers.
Generates apparent depth. Prevents closure.

---

## Block 17 — Semantic Projection Discipline

**Fix (forced by diagnosis):**

Before boundary reasoning:
1. Decompose word into layers
2. Keep layers with referents at this level
3. Drop layers without referents
4. Invalidate inferences depending on dropped layers

Only modal/structural meaning at boundary.

---

# PART B — The Embedded Condition

Structure, representation, and action under trajectory.

---

## Section A — Stability Typing

stableᴮ ≡ invariance(I) — maximal, non-representational, no time/process.

stableᵗ(Σ) ⇔ reference preserved across t — conditional on compression, interpretive regularities, reference preservation.

Time + identity = compression operators inside τ. Allow large relational structures → small Σ.

At boundary-adjacent expression: compression fails (no time, no identity handles).

Consequences:
- verbosity ↑, global dependence ↑
- no statement locally sufficient

Options:
1. verbose + global interpretation
2. compressed + distorted

¬(compact ∧ fully faithful). No third option.

Appearance of instability when expressing boundary structure from inside = representational failure, not structural failure. invariance(I) unchanged.

---

## Section B — Reality & Truth

**At B:**

Rᴮ := A (modal — what could be realized without violating I)

Tᴮ(c) ⇔ c ∈ A (admissibility = only truth predicate)

No actuality. No correspondence. "Could be true" is the strongest available.

**Inside τ:**

Rᵗ(t) := cᵣ(t) (realized configuration at index)

Tᵗ(s, t) ⇔ s ≈ cᵣ(t) (correspondence — local, partial, path-relative)

**Embedding constraint:**

τ ⊂ A → any internal system has only local access.

T_absolute undefined inside τ. Not merely unknown — undefined.

Not epistemic limitation. Structural consequence of embedding.

---

## Section C — Logic & Mathematics

At B: no symbols, no propositions, no inference. Only I excluding configurations.

Inside τ: I induces preservation requirement on Σ.

**Logic**: L = { f | resolve(f(Σ)) preserves admissibility }
= internal shadow of boundary-level necessity.

**Mathematics**: symbolic encoding of subsets of L.
- Trajectory-internal (depends on time, ordering, persistence)
- Effective because operations preserve relations corresponding to I
- Necessity conditional on encoding, but encoding constrained by A

**Proof**: shows ¬∃ admissible derivation → contradiction. Mirrors exclusion(I) internally.

**Drift progression**:

grounded → symbol-to-symbol resolution → identity replaces invariance → noise

Noise: symbols persist, coordination persists, resolve undefined, constraint not preserved.

Not cognitive failure. Structural consequence of extended τ under limited grounding.

---

## Section D — Meaning

M(Σₜ) := resolve(Σₜ, Eₜ)

- Rule-governed mapping, not intention/belief/state
- Determined by structure + environment, independent of agent
- Continuous with mathematical evaluation (same operator, different complexity)
- Time-indexed: same Σ may resolve differently if E shifts (not indeterminacy — environment changed)

Stability: stable meaning ⇔ stable(E)

Distinguish from truth: meaningful ∧ false is possible. Conflation invalid.

Resolution must: preserve admissibility when grounded, degrade predictably under drift, remain independent of belief/intention.

---

## Section E — Semantic Drift & Noise

**Grounded**: resolve(Σ, E) → A. Stability from invariance.

**Drift**: resolve(Σ, E) → Σ. Stability from identity/recognition. Coherence replaces correspondence. System may remain coherent, consistent, operational — while correspondence ↓.

**Noise**: resolve undefined. Symbolic coupling without constraint-respect. ≠ randomness. Only: loss of admissible anchoring.

Drift is default under extended τ. Identity-based stability sufficient for continued operation. No spontaneous reversal. Re-grounding requires deliberate reconstruction of E.

---

## Section F — Action & Consequence

act : cᵣ(t) → cᵣ(t+Δ) — causal intervention, not semantic event.

Causal propagation ⟂ meaning, truth. Effects from interventions, not correctness.

Agents act on internal models (Σ). Models may be grounded/drifting/incoherent. Influences prediction, not outcome. Outcome determined by act + causal structure.

**Responsibility**: structural, not normative. Attaches to causal participation in shaping shared τ. Not belief, not intention.

No action globally justified by belief alone (T_absolute undefined).

Evaluation uses local truth, evidence, reconstruction. Aims at usable alignment, not completeness.

Semantic failure ≠ causal failure. Action continues under drift/noise.

Meaning, truth, action: distinct. None reduces to others.

---

## Section G — No Privileged Perspective

- B: no perspective (no representation, no viewpoint)
- τ: every representation embedded, partial, indexed

Understanding ≠ completion. Understanding = maintaining constraint-respecting representations, necessarily provisional.

Representation cannot fully encode its own embedding conditions (typing collapse).

Stability: in A and causal structure, not in Σ.

---

## Section H — Closure

Structure complete when:
- A defined by I
- τ ⊂ A with causal propagation
- Σ partial/embedded

Extension attempts all fail:
- Boundary-level addition → no representation at B (type violation)
- Trajectory meta-position → still embedded (no privileged τ)
- Meta-level → boundary (no representation) or trajectory (still embedded)

Self-applicable without collapse: doesn't attempt to escape own conditions.

add → contradiction. remove → loss. Closure is typing consequence.

---

# PART C — Epistemic-Ontological Convergence

**Problem**: Must justificatory termination (the Anchor) necessarily coincide with ontological independence?

**Using**: C1, C5, C6, C7 only.

---

## Step 1 — Termination required (C7)

Without termination: circularity (self-certification, violates C7) or regress (never completes, violates C7).

Therefore: ∃A (termination point).

---

## Step 2 — Internal candidates eliminated

**Internal coherence**: validated using S's own procedures → circular. Rejected (C7).

**Definitions/stipulation**: collapses warrant into assignment. Rejected (C6).

**Consensus/authority**: internal states, force depends on S's criteria → circular. Rejected (C7).

Result: A cannot be internal.

---

## Step 3 — Required properties of valid terminator

1. External — not defined/validated by S
2. Asymmetric — S depends on A, A not on S
3. Non-representational authority (C1)
4. Boundary preservation (C6, C7)

---

## Step 4 — Convergence with C5

| Required for A | Provided by C5 |
|---|---|
| External to S | Independent of observers/representations |
| Asymmetric | Not dependent on system states |
| Non-representational | Not constituted by representation |
| Capable of verification | Constrains what can be valid |

Properties coincide.

---

## Step 5 — Alternatives eliminated

**External but dependent on representations**: reintroduces circularity → C7 violated.

**External but provides no independent constraint**: no verification → C5 violated.

No merely external-but-dependent entity satisfies requirements.

---

## Result

Under {C1, C5, C6, C7}:

**Justificatory termination necessarily converges with ontological independence.**

Remove C5 → convergence undefined.
With C5 → convergence necessary.
