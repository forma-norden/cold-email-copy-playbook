# Test: copy-cta-friction-design

Load skill: `.claude/skills/copy-cta-friction-design.md`

## Prompt

```text
Read .claude/skills/copy-cta-friction-design.md

Inputs:
- touch number: 1
- segment: RevOps Director, mid-market SaaS
- offer: routing workflow teardown
- proof depth: one comparable case result
- bias: reply-rate first

Return CTA tier, 6 CTA variants, and final CTA with objection handling line.
```

## Must Pass Checklist

- [ ] Uses one-touch one-CTA policy
- [ ] Applies low-friction CTA tier for first touch
- [ ] Generates six CTA variants
- [ ] Flags blocked CTA styles with reasons
- [ ] Includes final selected CTA and objection handling line

## Failure Indicators

- direct booking CTA on touch one without engagement
- multiple asks combined in one CTA
- no blocked CTA rationale

