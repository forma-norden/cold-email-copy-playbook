# copy-quality-compliance-review

Use this skill to run final copy QA before campaign activation.

## Required Inputs

- final copy set (subject, opener, body, CTA)
- segment definitions
- proof references
- jurisdiction constraints (GDPR/CAN-SPAM/local policy)
- deliverability policy constraints

## QA Dimensions

1. Relevance:
   - segment-specific language
   - role-specific pain mapping
2. Credibility:
   - no unverifiable claims
   - proof aligned to message
3. Deliverability:
   - low spam pattern risk
   - no unsafe first-touch link strategy
4. Compliance:
   - lawful basis assumptions documented
   - suppression and opt-out policy compatibility

## Execution Sequence

1. Run checklist scoring (pass, warning, fail) for each message.
2. Flag risky terms, claims, and CTA mismatches.
3. Propose corrected version for each failed message.
4. Produce go/no-go decision with remediation steps.

## Output Contract

Return:

- qa_scorecard by message
- fail_reasons
- corrected_copy
- go_no_go decision
- required_prelaunch_actions

## Non-Negotiable Fails

- fabricated personalization
- illegal or non-compliant claims
- no opt-out path in the sending system
- message approved without proof for key numeric claim

