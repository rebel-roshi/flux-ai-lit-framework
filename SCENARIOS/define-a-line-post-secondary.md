# SCENARIOS/define-a-line-math-major.md
# Scenario: “Define a line” (Math major) — Flux micro-moves in a more formal ecology

## Important note (explicit)
This is **one implementation** of Flux in a math-major context, under a frame we are **not fully exposing**
(course (linear algebra / geometry / analysis), instructor norms, proof culture, time, student background, etc.).
It’s a projection, not a canon.

## Local frame (partial)
- Audience: undergrad math major (proof-capable, multiple structures available)
- Setting: small group work / recitation / office hours; instructor circulates and listens for cues
- Goal (today): turn “line” from a word into an object that can be **used** (proved about / mapped / classified)
- Constraint: avoid a lecture of “all the definitions.” Let the need for a frame emerge through work.

---

## The moment the instructor walks up on
Student: “What is a line, really?”  
AI (or student reading AI): “A line is a straight path extending infinitely in both directions.”

### Transactional risk
The group treats “straight” as primitive and stops, or tries to argue about “the true definition” instead of
naming the structure that makes the question precise.

### Flux re-entry (without a speech)
A small question shifts from slogan → structure.

---

# Path 1: [POKE] — Make one word do mathematical work (micro-intervention)
**Instructor move (to students):**
- “What does **straight** mean *in your current structure*?”

**Prompts (only as needed):**
- “Are we in a vector space, an affine space, a metric space, a manifold…?”
- “What property is the ‘straight’ object supposed to satisfy—closure, minimality, geodesic, linearity?”
- “What would count as a counterexample to your meaning of straight?”

**Formative cues:**
- Students can name a structure and a testable property vs staying at metaphor-level.

---

# Path 2: [UNKNWN] — Turn ‘definition’ into a frame-choice (micro-intervention)
**Instructor move (to students):**
- “What job must ‘line’ do **here**? What are we trying to prove or compute with it?”

**Prompts (only as needed):**
- “Do you need an object determined by two points?”
- “Do you need an object that’s the image of an affine map from ℝ?”
- “Do you need a 1D subspace, or a 1D affine subspace?”
- “Are we trying to characterize automorphisms, intersections, or distances?”

**Formative cues:**
- Students articulate requirements (two-point determination, invariance under translations, point-membership test, etc.).
- They notice when a candidate doesn’t satisfy the job (e.g., “subspace” fails ‘line not through origin’).

---

# Path 3: [NOGUARD] — Restore ownership from authority (AI or ‘standard definition’) (micro-intervention)
**Instructor move (to students):**
- “Convince me without ‘because that’s the definition’ or ‘because the AI said so.’”
or
- “What would you need to check to make your definition *usable*?”

**Prompts (only as needed):**
- “Give two equivalent characterizations and prove they match (in this frame).”
- “Stress-test: does your definition capture vertical lines / translated lines / geodesics / projective lines?”
- “Show me how you’d decide if a point lies on the line using your definition.”

**Formative cues:**
- Students can verify equivalences, produce stress tests, and treat ‘definition’ as a tool with obligations.

---

## A few candidate “lines” (not a lecture—just options students may converge to)
These should emerge from the group’s chosen frame:

- **Affine geometry (common undergrad frame):**
  A line is a **1-dimensional affine subspace**:  `{p + tv : t ∈ ℝ, v ≠ 0}`.
- **Linear algebra (subspace-only frame):**
  A line through the origin is a **1D subspace**: `{tv : t ∈ ℝ, v ≠ 0}`.
- **Metric / Riemannian geometry (analysis/geometry frame):**
  A line is a **geodesic** (locally length-minimizing curve / zero acceleration).
- **Projective geometry (advanced undergrad frame):**
  A projective line corresponds to a **2D subspace** of a vector space modulo scaling.

The Flux point: the “right” choice is the one that matches the job + structure you’ve made explicit.

---

## Optional placements of AI (same Flux paths, different logistics)

### A) Student device AI (in the wild)
Instructor uses micro-moves above to prevent “authority drift.”

### B) AI as hole-poker (in front of students)
Instructor → AI:
“Poke holes in the phrase ‘straight
