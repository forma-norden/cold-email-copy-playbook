# cold-email-copy-playbook

Production copy workflow for cold outbound teams that need segment-specific,
reply-focused messaging without sacrificing deliverability or compliance.

## Skills

This repo contains AI-assisted skills in `.agents/skills/`.
Start by loading the orchestrator:

```
Read .agents/skills/SKILL.md
```

The orchestrator routes your question to the right skill automatically.

## Available Skills

| Skill | When to use it |
|-------|-----------------|
| `copy-segmentation-system` | Splitting lists into segments before writing |
| `copy-message-architecture` | Creating first-touch messages with 4-block structure |
| `copy-subject-opener-engine` | Generating subject and opener variants |
| `copy-cta-friction-design` | Selecting CTAs that maximize reply probability |
| `copy-follow-up-sequence` | Building touches 2 to 5 with new value each step |
| `copy-quality-compliance-review` | Quality, deliverability, and compliance checks |
| `copy-atl-executive-messaging` | Above-the-line messaging for VP/C-Level/Director |
| `copy-btl-practitioner-messaging` | Below-the-line messaging for Managers and ICs |

## Resources

Reference data is in `resources/`:
- `templates/email-template-library.md` for ready-to-use email templates
- `references/writing-frameworks.md` for named copywriting frameworks
- `benchmarks/email-benchmarks.md` for performance data

## Tests

See `tests/README.md` for validation prompts and checklists.
