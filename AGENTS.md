# Existing Pattern First Gate

Before modifying any existing lesson data, manifest, generated deck, script,
test, or workflow in this repository, read and follow:

`/Users/francis/.codex/skills/existing-pattern-first/SKILL.md`

This gate is always-on for this repo. It applies to small follow-up edits, not
only large refactors. First find and read the closest local implementation with
`rg`; reuse existing data formats, manifests, generators, and validation scripts
by default. Do not introduce ad hoc duplicate data, hand-maintained derived
state, fake schemas, or edits to generated artifacts without identifying the
source and regeneration path unless the user explicitly approves the deviation
before edits.

Tests or validation must prove behavior, coverage, and provenance invariants,
not implementation trivia. Final reports must name the existing pattern or
native capability reused, the affordance preserved, and the verification
performed.
