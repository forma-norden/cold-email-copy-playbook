# Test: copy-follow-up-sequence

Load skill: `.claude/skills/copy-follow-up-sequence.md`

## Prompt

```text
Read .claude/skills/copy-follow-up-sequence.md

Inputs:
- first-touch body: sent and no reply after 4 days
- segment: VP Sales, funded Series B SaaS
- offer: signal-based list building workflow
- proof assets: one case study and one teardown template
- max touches: 5

Return touches 2-5 with angle mapping and stop/revisit logic.
```

## Must Pass Checklist

- [ ] Uses distinct angle for each follow-up touch
- [ ] Adds new value in every touch
- [ ] Includes one CTA per message
- [ ] Includes stop and revisit rules
- [ ] Avoids bump-style filler language

## Failure Indicators

- repeated body copy across touches
- no permission close on last touch
- no stop logic

