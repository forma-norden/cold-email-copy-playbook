# Cold Email Copy Playbook

Production copy workflow for cold outbound teams that need segment-specific,
reply-focused messaging without sacrificing deliverability or compliance.
This repo turns copy writing into an operating system with deterministic
structure, CTA policy, follow-up logic, and prelaunch QA gates.

## What's Inside

| File | What it does |
|------|-------------|
| `.agents/skills/SKILL.md` | Orchestrator and routing logic |
| `.agents/skills/copy-atl-executive-messaging.md` | Strategic messaging targeting the C-Suite and VPs (Above the Line). |
| `.agents/skills/copy-btl-practitioner-messaging.md` | Tactical messaging targeting managers and practitioners (Below the Line). |
| `.agents/skills/copy-segmentation-system.md` | How to split outbound lists into executable copy segments. |
| `.agents/skills/copy-message-architecture.md` | Building first-touch emails with a constrained 4-block structure. |
| `.agents/skills/copy-subject-opener-engine.md` | Generating subject and opener variants with anti-spam controls. |
| `.agents/skills/copy-cta-friction-design.md` | Selecting CTA style by touch stage and buyer readiness. |
| `.agents/skills/copy-follow-up-sequence.md` | Designing touches 2-5 with new value and close logic. |
| `.agents/skills/copy-quality-compliance-review.md` | Quality, deliverability, and compliance checks before launch. |

## Prerequisites

- [ ] Clear ICP and segment definitions
- [ ] Source-backed trigger data for personalization
- [ ] Proof assets (case outcomes, teardown, or process evidence)
- [ ] Sequencer with suppression and opt-out handling
- [ ] Deliverability baseline already configured

## Installation

### Cursor, Windsurf, or Generic AI IDE
1. Clone the repo: `git clone https://github.com/forma-norden/cold-email-copy-playbook`
2. Copy the `.agents/skills/` directory into your project's `.agents/skills/` folder.

### Claude Code
1. Clone the repo: `git clone https://github.com/forma-norden/cold-email-copy-playbook`
2. Copy the `.agents/skills/` directory into your project's `.claude/skills/` folder.

## Usage

```text
Read .agents/skills/copy-message-architecture.md

Inputs:
- segment: VP Sales at 50-300 employee B2B SaaS firms
- trigger: hiring outbound reps this month
- pain hypothesis: response lag and poor qualification
- proof: similar team improved qualified reply rate by 2.4x
- CTA type: low friction yes/no

Return:
1) three first-touch variants
2) risk notes for each
3) selected primary variant and rationale
```

Expected output:

- three testable first-touch messages
- one selected production variant with reasoning
- risk flags to fix before launch

## Who This Is For

GTM engineers, RevOps leads, VP Sales, and founders at B2B companies with 50 to
500 employees who are building or consolidating their outbound infrastructure and
want to reduce tool sprawl through better-engineered GTM systems.

---

## From the Forma Nôrden GTM Library

This is a free resource from the Forma Nôrden open-source GTM library, built by
[Yananai A. Chiwuta](https://yananaichiwuta.com/), GTM engineer and founder of
[Forma Nôrden](https://formanorden.com/).

- [Open-source GTM systems](https://github.com/forma-norden) - all repos in the library  
- [GTM engineering blog](https://formanorden.com/blog/) - strategy, systems, and outbound deep-dives  
- [All resources](https://formanorden.com/resources/) - guides, frameworks, and templates  

If this saves you time, star the repo and follow
[Forma Nôrden on LinkedIn](https://www.linkedin.com/company/formanorden/).

Built by [Forma Nôrden](https://formanorden.com/) - GTM engineering for B2B companies.



