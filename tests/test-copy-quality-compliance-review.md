# Test: copy-quality-compliance-review

Load skill: `.claude/skills/copy-quality-compliance-review.md`

## Prompt

```text
Read .claude/skills/copy-quality-compliance-review.md

Inputs:
- campaign set: 1 subject + 5 touches
- geo: UK + US
- claim used: "reply rate grew 3x"
- proof available: one anonymized client report
- platform policy: no first-touch links, mandatory opt-out processing

Return QA scorecard, corrections, and go/no-go decision.
```

## Must Pass Checklist

- [ ] Scores relevance, credibility, deliverability, and compliance
- [ ] Flags unverifiable or risky claims
- [ ] Produces corrected copy for failed messages
- [ ] Returns explicit go/no-go decision
- [ ] Lists required prelaunch actions

## Failure Indicators

- approves unverified numeric claims
- no compliance check on suppression or opt-out policy
- no remediation path

