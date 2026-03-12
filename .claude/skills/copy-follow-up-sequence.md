# copy-follow-up-sequence

Use this skill to build touches 2 to 5 with new value each step.

## Required Inputs

- first-touch message
- days since prior touch
- segment and offer context
- available proof assets
- stop conditions

## Sequence Policy

- each follow-up must add new information
- no "just bumping this" language
- preserve single CTA per message
- stop after defined max touches or explicit negative response

## Recommended Angle Map

- touch 2: insight add
- touch 3: social proof
- touch 4: free resource or actionable asset
- touch 5: permission close

## Execution Sequence

1. Pull thread context from previous touch.
2. Select the next angle not yet used.
3. Draft message with one net-new value point.
4. Attach appropriate CTA friction level.
5. Define stop, pause, and revisit rules.

## Output Contract

Return:

- touches_2_to_5 copy set
- angle used per touch
- CTA per touch
- stop_conditions
- revisit_window recommendation

## Failure Conditions

- repeated body text with minor wording changes
- non-value follow-ups
- no close logic after max touches

