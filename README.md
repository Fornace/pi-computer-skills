# Computer skill library

Three manually adapted guides from Francesco's supplied Computer archive:
- Design foundations: hierarchy, typography, color and data visualization.
- Image direction: concise briefs, references, model/tool compatibility and delivery.
- Research reports: evidence, citations and portable Markdown artifacts.

## Explicit-only loading

The package exposes one native Pi command:

```text
/skill:computer-library design <task>
/skill:computer-library images <task>
/skill:computer-library research <task>
```

The entry uses `disable-model-invocation: true`. Its name, description and body are
excluded from the default model skill prompt. Pi discovers the small entry locally
for command registration. Guide files live outside discovered skill directories,
have no skill frontmatter, and enter model context only after a selected read.
This is manual activation: ordinary natural-language requests do not automatically
advertise or trigger this hidden collection. Existing installed skills are unchanged.

## Install locally

```sh
pi install /absolute/path/to/pi-computer-skills
```

Use `/reload` in the desired session or start a fresh Pi session after installation.
Do not reload or steer independently owned running jobs. Pi's local-path install
references this checkout without copying files or executing dependency installers.

The package has no extensions, scripts, dependencies, credential requirements or
startup network calls. It leaves provider settings, existing skills and source
archive files intact. Every guide uses portable paths or existing skill discovery.

## Review and verification

See [manual review](docs/REVIEW.md), [source digests](docs/provenance.json) and
[verification receipt](docs/verification.json). All six source files behind the
three selected guides were read in full. The other archive skills remain uninstalled.

The experimental Favilla brandbook prompts are not bundled as validated recipes.
Their outputs require user acceptance before promotion into reusable guidance.

This is a private local adaptation. Source attribution is retained in the review;
no new license or permission to redistribute the supplied archive is asserted.
