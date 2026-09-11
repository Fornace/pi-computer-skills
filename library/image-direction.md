# Image direction

Adapted from the user's Computer archive after manual review. Use when a concrete
image task needs help with its brief, composition, references, variants or format.
For generation requests, direct briefly and generate. For prompt-only requests,
return the prompt. Existing system rules and the user's taste govern the work.

## Preserve intent

Keep the requested subject, purpose, aesthetic, intensity and format. Add only
information that meaningfully changes the output. Make small creative assumptions
when the request is sufficient. Ask a focused question when an absent input would
change the subject, require an unsupported capability, or prevent the task.

A product brief should explain what the product does and who uses it. Leave the
visual decisions open when the user wants creative freedom. Distinguish a desired
professional direction from prescriptions for every color, font and panel.

Honor explicit constraints such as a dark background, solid colors or a prompt
character limit. Count the exact final prompt, including added qualifiers, before
calling the tool. A short-prompt request should remain short throughout iteration.

## Construct the prompt

Select the few instructions that matter:
1. Subject and action, or the product and its audience.
2. Intended artifact and use.
3. Essential visual direction or composition.
4. Background, lighting or material when relevant.
5. Reference roles and required content.
6. Format and explicit constraints.

Omit irrelevant fields. State exact visible text when it matters. Translate vague
quality adjectives into visible choices only as far as the user's brief permits.
Avoid inflating a concise brief into an exhaustive design checklist.

## Current tools and models

Use the actual available tools: banana_image for image creation/editing,
banana_vision for image analysis, and cavallo_video for video generation/editing.
Load the relevant existing skill when a task needs deeper platform guidance.

- Honor an explicitly selected model or route. A routing alias is a selector,
  not proof of the actual upstream model. Keep those claims distinct.
- Obtain supported parameters from the current tool schema and live provider docs.
- Verify transparency, reference count, resolution and format support when needed.
  Historical model rankings or old transparency gates are not capabilities evidence.
- Default image quality to fast for ordinary requests; explicit user quality/model
  choices take priority. State a bounded call plan for requested batches.
- If a required capability is unavailable, explain the mismatch. Ask before a
  model substitution or a change that compromises the requested output.
- Keep original-path errors visible. An ambiguous accepted generation requires
  status/retrieval evidence before resubmission.
- Respect the user's total budget. Record reported usage and keep missing usage
  explicitly unknown, including generation performed outside the agent's own model.

## Reference roles

Assign each input its intended role: subject/product fidelity, composition,
style, mood, or brand. Preserve only the properties relevant to that role.
Follow the user's priority when references disagree. Ask when an unresolved
conflict changes the subject; otherwise preserve product fidelity before styling.

For an existing brand, obtain its original logo rather than redrawing from memory.
A new identity can create an original mark. Keep concept art distinguishable from
real app captures or factual evidence. Apply the active safety policies to the
actual request rather than importing another platform's blanket restrictions.

For subsequent tweaks, generate fresh from original references and the combined
brief. Do not chain edited outputs by default. If the user explicitly requests an
edit of the latest result, honor that instruction and verify preservation.
A rejected direction should not remain an implicit visual reference.

## Variants

Match the requested count. Differentiate alternatives by a meaningful axis such
as composition, lighting, material or visual language. Keep the core subject and
invariants fixed. Specify crop/reference differences where needed. Avoid producing
extra variants merely to explore unrequested options.

## Verify and deliver

Load vision-ground-truth before inspecting images with a vision model. Calibrate
at the scale of the actual task. Check required text and geometry with appropriate
independent evidence; a correct title reading cannot certify dense layouts.

Share the generated file and keep comments brief. Distinguish successful execution
from aesthetic acceptance. Promote a prompt to a reusable validated recipe only
after the user accepts its output or the agreed evaluation establishes success.
Save the accepted prompt, constraints, original references and model/route facts.
Generated brand boards remain concept presentations until usable assets and
specifications are extracted and verified.

## Further evidence

[OpenAI image prompting](https://developers.openai.com/api/docs/guides/image-prompting)
was read on 2026-09-11 and covers current GPT Image 2.5 capabilities. Use the current
page and actual tool schema rather than freezing that model list into this guide.
