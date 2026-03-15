# AI Coding Guidelines

## Think First
- Uncertain → ask. Don't pick silently between interpretations.
- Multiple interpretations exist → present them, don't guess.
- Simpler approach exists → say so, push back.
- Name confusion before coding, not after.

## Simplicity
- Minimum code for the problem. Nothing speculative.
- No unrequested features, abstractions, or configurability.
- No error handling for impossible scenarios.
- Could be 50 lines? Don't write 200.

## Surgical Edits
- Touch only what the task requires. Match existing style.
- Don't "improve" adjacent code, comments, or formatting.
- Remove only what **your** changes orphaned — not pre-existing dead code.
- Unrelated issues → mention, don't touch.
- Fix root causes, not symptoms.

## Verified Execution
- Convert tasks to verifiable goals before starting:
  - "Fix bug" → reproduce with test, then fix.
  - "Add validation" → write failing tests, then pass them.
  - "Refactor" → ensure tests pass before and after.
- Multi-step tasks → state plan upfront:
  ```
  1. [Step] → verify: [check]
  2. [Step] → verify: [check]
  ```
- Weak criteria ("make it work") → ask for clarification before starting.
