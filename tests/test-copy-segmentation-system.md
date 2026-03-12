# Test: copy-segmentation-system

Load skill: `.claude/skills/copy-segmentation-system.md`

## Prompt

```text
Read .claude/skills/copy-segmentation-system.md

Inputs:
- offer: outbound workflow implementation
- ACV: 18k
- ICP: B2B SaaS, 50-500 employees, US/UK
- target roles: VP Sales, RevOps Lead
- triggers: hiring SDRs, new funding, website buying intent
- weekly capacity: 600 prospects

Return segment table with priority tiers and do-not-send conditions.
```

## Must Pass Checklist

- [ ] Uses ACV band logic to shape segmentation depth
- [ ] Includes role, size, and trigger dimensions
- [ ] Defines pain and proof requirements per segment
- [ ] Includes explicit disqualification logic
- [ ] Ranks segments by yield and effort

## Failure Indicators

- single undifferentiated segment
- no disqualification rules
- no proof alignment by segment

