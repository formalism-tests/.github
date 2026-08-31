# formalism-tests

**formalism-tests is the independent executable-testing organization for StegVerse and Admissible-Existence formalisms.**

Its purpose is to turn mathematical and governance claims into reproducible fixtures, counterexamples, invariants, and fail-closed tests without treating a passing test as authority or proof beyond the tested scope.

## What belongs here

Repository families include tests for:

- **Triad**
- **GCAT / BCAT**
- **ECAT / ICAT**
- **Existence**
- **Inference Window**
- **Entropy / Reversibility**
- **Transition Periodic Table**
- supporting sandbox and Core-Lite test infrastructure.

## Test philosophy

A useful formalism test should state:

- the exact proposition under test;
- the frozen inputs and assumptions;
- the expected invariant or falsifier;
- the observed result;
- the evidence needed to reproduce it;
- what the result does and does not establish.

Local validity is not automatically composite validity, and CI success is not runtime or publication authority. The organization exists to make formal claims easier to challenge, reproduce, compare, and refine.
