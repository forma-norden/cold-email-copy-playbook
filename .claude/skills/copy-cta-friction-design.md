# copy-cta-friction-design

Use this skill to choose CTA style by touch stage and buyer readiness.

## Required Inputs

- campaign touch number
- segment context
- offer type
- current proof depth
- risk tolerance (reply-rate vs meeting-rate bias)

## CTA Policy

- one email equals one CTA
- first-touch CTA should be low-friction
- meeting asks are allowed only after signal or engagement
- CTA must match evidence provided in message body

## Friction Ladder

1. Lowest friction:
   - "interested?"
   - "want me to send it?"
2. Medium friction:
   - "mind if I share the breakdown?"
   - "want a short video?"
3. High friction:
   - "15 mins this week?"
   - direct booking link

## Execution Sequence

1. Determine allowed friction tier for the current touch.
2. Generate 6 CTA variants in the allowed tier.
3. Remove variants with ambiguity or multiple asks.
4. Pair each CTA with one likely objection and mitigation phrase.
5. Select final CTA by segment fit.

## Output Contract

Return:

- allowed_friction_tier
- cta_variants (6)
- final_cta
- objection_handling_line
- blocked_ctas with reasons

## Failure Conditions

- two CTAs in one message
- high-friction CTA on touch one with no engagement signal
- CTA request not supported by prior context

