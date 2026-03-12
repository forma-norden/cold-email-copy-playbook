# Test: copy-subject-opener-engine

Load skill: `.claude/skills/copy-subject-opener-engine.md`

## Prompt

```text
Read .claude/skills/copy-subject-opener-engine.md

Inputs:
- segment: founder-led SaaS, 20-80 employees
- trigger: announced expansion to UK market 4 days ago
- role token: founder
- company token: AcmeCloud
- tone: casual-direct

Return 8 subject lines, 8 openers, and top 3 pairs with scores.
```

## Must Pass Checklist

- [ ] Produces the full requested variant counts
- [ ] Avoids spam-style punctuation and fake urgency
- [ ] Keeps subjects concise
- [ ] Keeps openers them-first
- [ ] Includes rejected variants with reasons

## Failure Indicators

- fabricated personalization
- opener starts with sender company pitch
- no scoring or rationale for selected pairs

