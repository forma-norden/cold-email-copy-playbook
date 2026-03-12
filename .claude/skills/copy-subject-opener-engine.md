# copy-subject-opener-engine

Use this skill to generate subject lines and openers that improve relevance
without looking like spam automation.

## Required Inputs

- segment profile
- trigger source and timestamp
- role and company tokens
- tone constraints (casual, direct, formal-light)

## Subject Rules

- 2 to 5 words preferred
- lowercase or natural-case phrasing
- never use false urgency, all caps, or excessive punctuation
- avoid first-touch brand promotion in subject line

## Opener Rules

- mention recipient context before your company
- reference one concrete signal only
- do not fabricate personalization
- avoid generic social niceties

## Execution Sequence

1. Generate 8 subject variants across four styles:
   - role plus outcome
   - trigger reference
   - pattern interrupt
   - curiosity with constraint
2. Generate 8 opener variants mapped to the same styles.
3. Score each variant for:
   - relevance
   - clarity
   - risk
4. Select top 3 subject/opener pairs with rationale.

## Output Contract

Return:

- subject_variants (8)
- opener_variants (8)
- top_pairs (3) with scores
- rejected_variants with reason

## Failure Conditions

- fabricated signal references
- opener starts with your company pitch
- subject line exceeds 8 words without strong justification
- spam trigger terms or punctuation patterns

