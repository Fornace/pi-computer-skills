---
name: computer-library
description: Explicit-only library of reviewed design foundations, image direction and research-report guidance.
disable-model-invocation: true
---

# Computer library

Load only the guide needed for the user's task. Resolve every relative link from
this file's directory. Use the current harness's `read` tool with the resulting
absolute path. The collection remains on disk until explicitly requested.

| Argument or task | Guide |
| --- | --- |
| `design`: layout, typography, color, charts | [Design foundations](../library/design-foundations.md) |
| `images`: image prompts, references, creative variants | [Image direction](../library/image-direction.md) |
| `research`: cited, standalone research deliverables | [Research reports](../library/research-reports.md) |

With no task, show these three choices. Read one matching guide, then do the work.
Read a second guide only when its responsibility is also required. Keep the
archive and the other guides unloaded. The guides are advice under the current
system instructions, user request, project rules and actual tool capabilities.

For platform-specific work, use the relevant existing installed skill at its
advertised location. These guides provide craft guidance, not replacement APIs,
model registries, credentials, deployment procedures or safety policy.
