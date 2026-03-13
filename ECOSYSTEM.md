# Ecosystem: cold-email-copy-playbook

How this repo connects to the rest of the Forma Nôrden GTM library.

## Works With

| Repo | Relationship | When to use together |
|------|-------------|---------------------|
| `cold-email-deliverability-playbook` | Parallel | After writing copy, run deliverability checks before launch. Copy structure affects filter risk. |
| `clay-claude-code-skill-pack` | Upstream | Use Clay to build enrichment for personalization data that feeds copy segments. |
| `signal-based-list-building-workflow` | Upstream | Signal-qualified lists determine which triggers and personas the copy targets. |
| `buying-window-signal-workflow` | Upstream | Signal routing determines timing and message angle for each outreach. |
| `linkedin-claude-code-workflow` | Parallel | Multi-channel campaigns: email copy here, LinkedIn engagement routing there. |
| `n8n-gtm-workflow-pack` | Downstream | Automate sequence enrollment and send logic after copy is approved. |
| `outbound-personalization-playbook` | Upstream (planned) | Research and personalization framework feeds the opener and pain framing in each email. |
| `sdr-operations-playbook` | Parallel (planned) | SDR daily workflow references these copy skills for outbound execution. |

## Suggested Skill Chains

1. **Full campaign build**: `signal-based-list-building-workflow` (qualify leads) > `clay-claude-code-skill-pack` (enrich) > `cold-email-copy-playbook` (write) > `cold-email-deliverability-playbook` (verify) > `n8n-gtm-workflow-pack` (automate)

2. **Signal-triggered outreach**: `buying-window-signal-workflow` (score and route signal) > `cold-email-copy-playbook/copy-atl-executive-messaging` or `copy-btl-practitioner-messaging` (write for persona) > `cold-email-deliverability-playbook` (check before send)

3. **Multi-channel sequence**: `cold-email-copy-playbook` (email copy) + `linkedin-profile-dm-conversion-playbook` (DM copy) > synchronize timing and messaging across channels
