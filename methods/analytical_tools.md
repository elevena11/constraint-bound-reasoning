# Analytical Tools (Derived Primitives)

## Purpose
This document defines specific analytical operations derived from the intersection of the Core Constraints. These tools provide shorthand definitions for common pattern-recognition tasks.

They are particularly useful when instructing reasoning engines (LLMs) to perform specific types of filtering.

---

### 1. The 2×2 Truth Table (Behavioral Consistency)
**Function**: Exhaustive mapping of the relationship between words and acts.
**Derivation**: C4 (Pattern Stability) ∩ C6 (Boundaries) ∩ C2 (Reality Creates Words)

```text
Definition: 
  Say = {verbal_expressions}
  Do = {behaviors}
  Analysis_Space = (Say ∪ ¬Say) × (Do ∪ ¬Do)
  Valid_Patterns = Pattern_Recognition(Analysis_Space ∩ Reality_Correspondence)
```

Use Case: Detects when a system claims X but incentivizes ¬X.

---

### 2. Black Box Methodology (Epistemic Hygiene)

Function: Restricts analysis to observable inputs and outputs, ignoring unobservable internal states (intent, sincerity).
Derivation: C5 (Objective Reality) ∩ C7 (Self-Verification) ∩ C1 (Distinction)

```text
Definition:
  Observable = {inputs, outputs, behaviors}
  Internal_States = Universal_Set \ Observable
  Valid_Claims = Claims ∩ Observable
  Constraint: Claims relying on Internal_States are inadmissible.
```

Use Case: Analyzing high-trust or opaque institutions without assuming good faith.

---

### 3. Language as Exclusion (Precision Test)

Function: Verifies meaning by checking what a definition excludes rather than what it affirms.
Derivation: C6 (Boundaries) ∩ C3 (References) ∩ C2 (Causality)

```text
Definition:
  Word_Meaning = {x | x ∈ Reality_Correspondence ∧ x ∈ Boundary_Function}
  Precision_Test: If (Inclusion_Set ∩ Exclusion_Set) ≠ ∅, then Meaning = Undefined.
```

Use Case: Testing abstract concepts ("Justice," "Spirit") for semantic drift.

---

### 4. Authority vs. Representation (Legitimacy Check)

Function: Distinguishes between authority derived from reality-alignment and authority derived from self-declaration.
Derivation: C3 (References) ∩ C4 (Stability) ∩ C2 (Causality)

```text
Definition:
  Authority = Contextual_Overlap ∩ External_Validation
  Valid_Representation = Authority ∩ Reality_Correspondence
  Illegitimate_Claims = Self_Declaration \ External_Verification
```

Use Case: Separating "Truth Signals" from "Authority Signals."
