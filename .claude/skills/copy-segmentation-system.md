# copy-segmentation-system

Use this skill to define actionable outbound copy segments before message writing.

## Required Inputs

- offer and ACV band
- ICP constraints (industry, company size, geography)
- target roles
- available trigger signals
- channel limits and weekly send capacity

## Execution Sequence

1. Define the buying context from ACV:
   - `<10k` role-first segmentation
   - `10k-50k` role plus company-size segmentation
   - `>50k` industry plus pain-depth segmentation
2. Create segment rows by:
   - role
   - company size band
   - trigger type
3. For each segment, define:
   - primary pain
   - desired outcome
   - language style to mirror
   - acceptable proof type
4. Add disqualification rules:
   - stale trigger (>30 days unless lifecycle is long)
   - no role ownership for the pain
   - weak evidence for claimed result
5. Rank segments by expected yield and operational effort.

## Output Contract

Return a table with:

- segment_id
- target_profile
- trigger_condition
- lead_with
- avoid_language
- required_proof
- priority_tier
- do_not_send_conditions

## Anti-Patterns

- one-template-for-all-segments behavior
- founder copy reused for enterprise buyer committees
- trigger claims with no source traceability
- volume-first segmentation that ignores proof fit

