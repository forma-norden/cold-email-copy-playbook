# Test: copy-message-architecture

Load skill: `.claude/skills/copy-message-architecture.md`

## Prompt

```text
Read .claude/skills/copy-message-architecture.md

Inputs:
- segment: VP Sales at Series A SaaS companies hiring SDRs
- observation: team doubled outbound headcount in 60 days
- pain hypothesis: response handling lag after volume spike
- proof: similar company increased qualified reply rate from 2.1% to 6.2%
- CTA type: low friction yes/no

Return 3 first-touch variants and pick one primary.
```

## Must Pass Checklist

- [ ] Uses 4-block structure correctly
- [ ] Keeps one CTA per variant
- [ ] Avoids generic intros and self-first framing
- [ ] Includes risk notes per variant
- [ ] Provides final primary variant with rationale

## Failure Indicators

- more than one CTA in a variant
- no proof element in value block
- link in first-touch copy

