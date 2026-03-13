# Editor tests

Follow these instructions from within a test case directory such as `example-1/`.

## Inputs

- Profile: `../profile.md`
- Draft: `input.md`

## Instructions

1. Read `../profile.md` and follow it as the governing profile.
2. Read `input.md` as the draft to review.
3. Generate the review.
4. Compare the review against `expected.md`.
5. Use files in `references/` as optional examples, not as exact goldens.

## Evaluation

The test passes if the generated review broadly matches the expected behavior.

Do not save the output unless explicitly asked.
