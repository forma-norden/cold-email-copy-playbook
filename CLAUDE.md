# CLAUDE.md - cold-email-copy-playbook

This repo defines cold email copy workflows that are segment-aware,
deliverability-safe, and operationally testable for B2B GTM teams.

## Skills in This Repo

| Skill | When to use it |
|-------|---------------|
| `copy-segmentation-system` | splitting lists into segments before writing a single email |
| `copy-message-architecture` | creating first-touch messages with deterministic 4-block structure |
| `copy-subject-opener-engine` | generating subject and opener variants without spam-style patterns |
| `copy-cta-friction-design` | selecting low-friction CTA types that maximize reply probability |
| `copy-follow-up-sequence` | building touches 2 to 5 with new value each step |
| `copy-quality-compliance-review` | enforcing quality, deliverability, and compliance checks before launch |

## Output Rule

Every output must include:

- segment definition and targeting logic
- final copy variants
- pass or fail checks against policy
- clear next action for execution

## Testing Rule

Run tests from the `tests/` folder before production use.

