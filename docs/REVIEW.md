# Manual adaptation review

Date: 2026-09-11. Reviewer: parent coding assistant, direct source reading.
Archive supplied by user: `Computer octopus archive/workspace/skills` in Downloads.
Inventory: 44 SKILL.md files. Selected: three guides, six complete source files.
The other 41 skills were inventoried by path/size, not certified or installed.

## Design foundations

Read all 285 lines of design-foundations/SKILL.md.

Retained: meaningful hierarchy, restrained color, readable type, accessible
encodings, consistent chart design and delivery-scale checks.

Changed:
- Removed Perplexity's Nexus palette, FK Grotesk/Berkeley Mono defaults and mandatory
  font-service choices. User/project identity controls the design.
- Removed rigid font blacklists, compulsory font variation across projects and
  unsupported blanket statements about font use.
- Corrected the claim that PowerPoint cannot embed fonts. Microsoft documents
  embedding in supported versions, subject to font and tool capabilities.
- Corrected WCAG large-text thresholds from px to pt: 18pt regular or 14pt bold.
- Replaced visual contrast guessing with measurement of actual color pairs.
- Replaced automatic animation and absolute chart prohibitions with purposeful
  encoding, accessibility and reduced-motion behavior.
- Kept native macOS guidance in the existing macos-ui-design skill.

## Image direction

Read image-output-director/SKILL.md and all three references:
reference-roles.md, prompt-variants.md and trust-boundaries.md.

Retained: preserve user taste, produce the requested artifact, concise brief
construction, explicit reference roles, meaningful variants and delivery checks.

Changed:
- Replaced asi-generate-image, ask_user_question and archive model-catalog/media
  dependencies with actual available Pi tools and current provider documentation.
- Removed stale model rankings and the GPT Image 1.5-only transparency rule.
  Current OpenAI documentation includes transparency for GPT Image 2.5.
- Removed the archive's restricted aspect-ratio set and silent nearest-model/format
  substitutions. Current tool schemas and explicit user choices govern execution.
- Replaced blanket imported content bans with the current system's applicable
  policies; the archive does not supply a replacement safety policy.
- Replaced chained-edit recommendations with original-reference fresh generation,
  subject to an explicit user request to edit the latest version.
- Added route-versus-upstream honesty, usage uncertainty, exact prompt-length
  constraints and explicit separation of generated output from user acceptance.
- Kept image analysis under the existing vision-ground-truth protocol.

## Research reports

Read all 304 lines of research-report/SKILL.md.

Retained: standalone reports, claim-level citations, useful tables, relative image
links, primary evidence, visible uncertainty and conclusions tied to the question.

Changed:
- Replaced `.pplx.md` with ordinary `.md` and removed execute_code/share_file APIs.
- Removed the false expectation that local image links become uploaded URLs.
- Removed compulsory 5-to-10-paragraph factual answers, 20-to-40-paragraph
  comparisons, always-comprehensive research and citation-count quotas.
- Allowed a sources section and renderer-appropriate math syntax.
- Put the direct answer in the saved report as well as chat, for standalone use.
- Routed research to the existing web skill rather than a duplicate search stack.

## Loading and installation

The archive's selected SKILL.md files have no Pi frontmatter. Copying them directly
would not produce valid Pi skills. A new, explicit-only entry has valid name,
description and disable-model-invocation fields. The three guides are plain
Markdown support files outside auto-discovery, selected through that entry.

The original archive is unchanged. No copied executables or provider credentials.
Existing global skills remain intact. The package is local and private.

## Sources verified

- Installed Pi 0.85.1 docs/skills.md was read in full, including discovery rules
  and disable-model-invocation semantics.
- Installed Pi 0.85.1 README.md and docs/packages.md were read in full.
- [Microsoft embedding](https://support.microsoft.com/en-us/office/fonts/benefits-of-embedding-custom-fonts)
  and [WCAG contrast](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)
  were fetched successfully and their relevant passages checked.
- [OpenAI image prompting](https://developers.openai.com/api/docs/guides/image-prompting)
  was fetched and checked for current model capabilities and prompt construction.

Freshness claims refer to those reads, not to an assumed release date. The native
loader verification uses installed Pi 0.85.1 code without making a model request.
