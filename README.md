# Radical Equations Workout

Practice solving radical equations with a staged solve → check → verdict flow that forces the substitution check on every candidate, including planted extraneous roots.

Math 2201 · Unit 4 — Radicals (Section 4) · Indicators MA2201.1.9, MA2201.1.10, MA2201.1.11, MA2201.1.12

## Modes

- **Mode 1 · Solve — square roots:** √(linear) = constant; in Mixed sets also √(linear) = linear with two valid candidates.
- **Mode 2 · Extraneous traps:** √(linear) = x − d equations where exactly one algebraic candidate fails the check.
- **Mode 3 · Solve — cube roots:** ∛(linear) = constant, including negative values; no extraneous roots are possible, and the app explains why.
- **Mode 4 · Formula problems:** position / depth / height formulas F(v) = √(a·v + b); find v for a given F value.
- **Mixed set:** all shapes combined, with roughly half the solved items being traps.

Every session is 10 items: a fully worked example, a faded example (solving and checking shown, verdict left to the student), then 8 generated items. Each generated item runs the full staged flow — enter the candidate(s), substitute and enter the left side's value, then declare each candidate valid or extraneous — with "Show this step" help available during the solving stage.

Single self-contained `index.html`; no external libraries or assets. `harness.js` verifies every generator shape headlessly (2,000 draws each, independent brute-force key recomputation, zero mismatches required).
