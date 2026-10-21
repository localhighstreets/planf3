# Planf3

Planning skill assets in the LocalHighStreets organisation. The original project is attributed to IndyDevDan. This repository contains instructions, workflow templates, image-generation scripts and example plans rather than a deployed LocalHighStreet service.

## Completion and remaining work

Snapshot: **21 October 2026**.

| Measure | Status |
|---|---|
| Overall feature/release completion | **Not yet measurable** — no reconciled, acceptance-tested repository-wide baseline was established in this review |
| Tracked-work completion | **N/A** — no eligible GitHub issues in this repository |
| Open tracked work | 0 issues |
| Excluded closures | 0 cancelled/not-planned or unclassified closures |

The tracked percentage is `completed / (completed + open) × 100`, rounded to one decimal place. It counts repository GitHub issues equally; PRs and closures not marked `completed` are excluded. It is **not** a feature-completeness, effort, test-coverage or production-readiness percentage. Jira work, untracked requirements and upstream-project issues are outside this denominator. An empty tracker means unknown scope, not 100% completion.

### Remaining work and acceptance evidence

The following items identify implementation decisions, tracker reconciliation or validation still needed to establish completion; they are not all newly verified code defects.

- Define the target agent host and supported planning/image workflows for this copy.
- Verify skill invocation, template/reference handling and generated-plan outputs in that host.
- Validate configured image-provider access and review generated implementation changes against the plan's acceptance criteria.

### Tracked backlog

No open GitHub issues were returned for this repository at the snapshot date. Establish an owner-approved scope and acceptance checklist before assigning an overall percentage.

[Review the current issue tracker](https://github.com/localhighstreets/planf3/issues?q=is%3Aissue). Reconcile old package scopes, route assumptions and duplicate/superseded tickets against current code before acting on them. Update this dated numerator/denominator and remaining-work list after acceptance changes.

## Contents

| Path | Purpose |
|---|---|
| [.claude/skills/planf3/SKILL.md](.claude/skills/planf3/SKILL.md) | Skill instructions and plan template |
| [.claude/skills/planf3/workflows](.claude/skills/planf3/workflows) | Create, update, reference, build and image workflows |
| [.claude/skills/planf3/scripts](.claude/skills/planf3/scripts) | Image generation/editing helpers |
| [specs](specs) | Example plan output |
| [prompts](prompts) | Example prompts |
| [RAW.md](RAW.md) | Original planning material |
| [legacy_v1_meta_plan.md](legacy_v1_meta_plan.md) | Earlier specification |
| [.env.sample](.env.sample) | Environment template |

## Use

Read the skill entrypoint and load or copy the complete skill directory through your agent host's supported mechanism. Its documented invocation is:

```text
/planf3 "<work to plan>" [questionable]
```

Slash-command availability and installation locations depend on the host. Merely copying a directory does not establish compatibility with every agent tool.

Image generation has separate provider and credential requirements. Inspect the scripts and configure a provider available to your account before running them. Model names in templates are configuration choices, not guarantees of model availability.

## Output and limits

The repository contains HTML plan examples with linked image assets. Review both the plan and any implementation changes produced from it. Templates and instructions do not guarantee that generated work is correct, complete or confined to the intended scope.

Claims about model intelligence, universal host compatibility or improved engineering outcomes are not established by the checked-in files.

## Verification and attribution

Reviewed against the default-branch repository inventory on 21 October 2026. No model calls, image generation or generated-plan execution were performed. See [LICENSE](LICENSE) for the licence. Original project walkthrough: [Planf3](https://youtu.be/DzbqeO_diOQ).
