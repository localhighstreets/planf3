# Planf3

Planning skill assets in the LocalHighStreets organisation. The original project is attributed to IndyDevDan. This repository contains instructions, workflow templates, image-generation scripts and example plans rather than a deployed LocalHighStreet service.

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
