# copy-message-architecture

Use this skill to build first-touch cold emails with deterministic structure.

## Required Inputs

- segment row from `copy-segmentation-system`
- one verified trigger or observation
- one problem hypothesis
- one proof element (result, case, or process)
- one CTA type from the CTA skill

## Structure Rules

Message blocks:

1. Opener (5 to 15 words): specific to them
2. Pain context (15 to 25 words): plausible and role-relevant
3. Value proposition (10 to 20 words): what changes and why you can credibly help
4. CTA (5 to 15 words): single low-friction ask

Hard constraints:

- target total: 50 to 90 words
- exactly one CTA
- no links in first touch
- no inflated claims or unverifiable numbers
- no generic opener lines

## Execution Sequence

1. Draft three openers from source-specific observations.
2. Pair each opener with one pain hypothesis.
3. Inject one proof element tied to a comparable context.
4. Attach one CTA with friction level aligned to touch number.
5. Validate against constraints and remove any banned patterns.

## Output Contract

Return:

- 3 complete first-touch variants
- assumptions used for each variant
- risk notes per variant (relevance, proof strength, spam risk)
- chosen primary variant with rationale

## Banned Patterns

- "Hope you are well"
- self-intro as line one
- multi-offer paragraphs
- CTA combinations in one message
- forced urgency without factual trigger

