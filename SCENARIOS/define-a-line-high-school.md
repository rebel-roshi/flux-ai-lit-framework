# SCENARIOS/define-a-line-high.md
# Scenario: “Define a line” (High school) — Flux micro-moves while circulating

## Important note (explicit)
This is **one implementation** of Flux in a high school context, under a frame we are **not fully exposing**
(unit goals, pacing, prior knowledge, classroom norms, assessment pressures, etc.). It’s a projection, not a canon.

## Local frame (partial)
- Grade band: ~9–11
- Setting: students working in pairs/groups; teacher circulates for formative cues
- Goal (today): make “line” precise enough to support **graphing, equations, and point tests**
- Constraint: don’t lecture “multiple definitions”; let students encounter the need for precision through work

---

## The moment the teacher walks up on
Student: “Define a line.”  
AI (or student reading AI): “A line is a straight path that goes on forever in both directions.”

### Transactional risk
Students treat the sentence as final and move on (definition as slogan), or they jump to a memorized formula
without being able to justify it or stress-test it.

### Flux re-entry (without a speech)
A small question shifts from copying → reasoning.

---

# Path 1: [POKE] — Make “straight” operational (micro-intervention)
**Teacher move (to students):**
- “What does **straight** mean in coordinate geometry—how could you **test** it?”

**Prompts (only as needed):**
- “If I give you three points, how could you check if they lie on a line?”
- “What would have to stay the same as you move along the line?”
- “Can a line be vertical and still be ‘straight’?”

**Formative cues:**
- Students rely only on appearance vs propose an operational test (slope consistency, point test, equation check).

---

# Path 2: [UNKNWN] — Surface the ‘job’ of the definition (micro-intervention)
**Teacher move (to students):**
- “What should a definition of a line **let you do**?”

Common student answers: write an equation, graph it, check if a point is on it, generate it from two points.

**Prompts (only as needed):**
- “If I give you a point, how would your definition tell you yes/no?”
- “If I give you two points, how would your definition produce the line?”
- “What happens with a vertical line—does your idea still work?”

**Formative cues:**
- Students notice that some familiar forms don’t cover all cases and articulate requirements (all orientations, point-testable).

---

# Path 3: [NOGUARD] — Restore ownership from AI + from “formula reflex” (micro-intervention)
**Teacher move (to students):**
- “Convince me without saying ‘because the AI said so’ or ‘because that’s the formula.’”
or
- “How can you **check** your idea with examples?”

**Prompts (only as needed):**
- “Give an example your definition handles well.”
- “Now stress-test it with a **vertical line**.”
- “Give a non-example and explain why it fails.”

**Formative cues:**
- Students generate stress tests (vertical lines, point checks) and treat equations/AI outputs as candidates to verify.

---

## Optional placements of AI (same Flux paths, different logistics)

### A) AI is only on student devices
Teacher uses the same micro-moves above to prevent “AI authority drift.”

### B) AI is used briefly with students as a stress-test generator (not an authority)
Teacher → AI (in front of students):
“Give 5 stress-test cases for common ‘line’ definitions in Algebra 1/Geometry
(e.g., vertical line, two points with same x, checking if a point lies on a line).
For each, give a short ‘what this tests’ note.”

Teacher (to students):
“Pick one stress test and use it to evaluate your definition.”

### C) Teacher uses AI backstage for better questions (confidence + precision)
Teacher → AI (private):
“I’m circulating in Algebra 1. Give me quick formative prompts that push students from
‘straight forever’ to operational tests (point tests, slope consistency, vertical-line stress test)
without me lecturing multiple definitions.”

---

## Collapse signals (what the teacher notices while circulating)
- Students copy the sentence and can’t *use* it (no point test, no equation reasoning).
- Students treat `y = mx + b` as “the definition of a line” and ignore vertical lines.
- Students defer to AI or to “the formula” without verification.

## Flux re-entry cheat-sheet (one-liners)
- [POKE] “What does **straight** mean *operationally*?”
- [UNKNWN] “What does your definition **let you do**?”
- [NOGUARD] “How can you **check** it—try a vertical-line stress test.”

---

## Note on AI as context partner during productive struggle
Students can return to AI at any time for:
- stress-test examples (including vertical lines),
- alternate equation forms to compare,
- questions that help them verify a candidate definition,
as long as the group keeps ownership by **testing with points, graphs, and shared reasoning**.
