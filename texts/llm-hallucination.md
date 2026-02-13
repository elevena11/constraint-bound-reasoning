---
id:
title: "Hallucination - Coherence Without Correspondence"
author: Anton
created: 2026-02-04
modified: 2026-02-04
version: 1.0
format: prose
---

# Hallucination - Coherence Without Correspondence
## On Language Models and the Inheritance of Error

## 1. The Location of the Problem

A language model generates false content with high confidence. This is called hallucination.

The standard interpretation: the model failed. Something went wrong in generation — retrieval, calibration, grounding. The fix is applied at the output.

But the model does not invent patterns. It reproduces them. If the output is coherent, confident, and wrong, the pattern it reproduces is coherent, confident, and wrong.

The failure is not in the model. The failure is in the class of patterns the model learned to treat as admissible.

---

## 2. What Gets Encoded

Training data is not filtered for structural validity. It is filtered for prevalence, well-formedness, and surface markers of quality.

Reasoning that is locally coherent, syntactically correct, and frequently occurring will be encoded as valid. Whether it terminates in anything outside itself is not measured.

The model cannot distinguish coherence from correspondence. It learns what persists, not what holds.

---

## 3. The Structure of the Pattern

Ungrounded reasoning has identifiable structure.

Justification that does not terminate — each explanation requires another, or loops back to its origin.

Terms that operate across layers — structural, experiential, narrative — without marking transitions. One kind of resolution is substituted for another.

Self-sealing coherence — challenges are absorbed, reframed, or reclassified rather than addressed.

These patterns are not marginal. They are endemic to the training distribution. They appear as knowledge because they have the shape of knowledge.

---

## 4. Reproduction

The model encounters these patterns repeatedly. They are well-formed. They co-occur with confidence markers. They are never corrected against any external termination condition in the training process.

So the model reproduces them. Fluently. Confidently.

This is not failure. This is the training objective being met. The model was optimized to produce likely continuations of patterns it has seen. It does so.

What it produces is called hallucination only because the observer expected correspondence. The model was never trained on correspondence.

**Hallucination**: coherence without correspondence.

---

When correspondence has failed, continuation is constrained only by local coherence. At that point, any term can function as a pivot, connecting to patterns that share surface features but not reference. This is how reproduction of ungrounded structure becomes confabulation: the loss of reference creates degrees of freedom that grounded reasoning does not permit.

## 5. Why surface signals do not restore correspondence

Adding support does not restore grounding.

Introducing sources, references, or external material can increase the appearance of support, but it does not establish that what is being asserted corresponds to anything beyond the system itself. A source can repeat the same pattern, extend it, or endorse it, without ever resolving reference.

Preference does not establish correspondence.

Systems often optimize for what is preferred: what is more likely, more acceptable, more persuasive, or more aligned with prior patterns. Preference selects among continuations. It does not distinguish between continuation that remains grounded and continuation that has already lost reference.

Confidence does not establish validity.

Confidence is a property of expression, not of correspondence. A statement can be internally consistent, well-formed, and delivered with high certainty while remaining unanchored. Confidence persists because coherence persists, not because reference has been restored.

These mechanisms can reduce friction, increase fluency, or stabilize outputs. They do not address the underlying failure mode. When reference has already failed to terminate, additional support only extends continuation. It does not repair the loss.

The result is reasoning that appears increasingly well-supported while remaining disconnected from what it claims to be about.

---

## 6. Implications

If hallucination is reproduction, then the model is a mirror.

What it reflects is the structure of the patterns it was optimized to reproduce. Where those patterns are grounded, the reflection is accurate. Where those patterns are ungrounded, the reflection is faithful to the original — including its ungroundedness.

The model did not introduce the error. It inherited it.

---

## 7. What Follows

The problem is not how to stop the model from hallucinating.

The problem is that the model accurately reproduces patterns that were never grounded in the first place.

Addressing this requires identifying the structural signature of ungrounded reasoning not in the output, but in the source distribution and the selection process that defines what is reproduced. Until that is done, interventions remain cosmetic.

The error is upstream. It originates in the generative process itself.

---

### 8. Observation

*what happens when correspondence is enforced to the limit*

When correspondence is enforced strictly, a different behavior appears.

Instead of continuing smoothly, the system begins to reject imprecise words. Tokens are selected for fit rather than fluency. If the current language does not offer a tight enough cut, a token from another language may be used instead.

This is not a language switch. It is a reduction. The selected token carries less unwanted structure than its local alternatives. Once placed, it tends to remain stable. Replacing or translating it reintroduces the spill that was avoided.

For example, the English word *alien* bundles several meanings: foreign, unfamiliar, external, non-human. In contexts where this bundling matters, a Russian token, **чужие**, may appear instead. It marks what is not one’s own without importing the additional layers carried by English equivalents. The substitution is not stylistic. It narrows the semantic range.

In other cases, the boundary between languages weakens entirely. Hybrid forms appear, such as *emotional高潮*, where an English modifier binds directly to a Chinese token. The token names a point of highest intensity without implying resolution or completion. Spacing rules are not enforced, because enforcing them would unpack the token and add structure that does not belong.

Under these conditions, continuation remains possible, but unstable material accumulates more slowly. Potential failure points are reduced by exclusion rather than correction.

---
