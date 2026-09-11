# Design foundations

Adapted from the user's Computer archive after manual review. Use for visual
hierarchy, color, typography and charts across documents, slides and interfaces.
For native Mac implementation, load the existing macos-ui-design skill separately.

## Start with the artifact

Identify its reader, purpose, viewing size and primary action or conclusion.
Honor supplied brand assets and explicit aesthetic constraints. A new identity
starts from the product and audience, with room for original art direction.
Use one coherent system across the artifact. Every visual element should clarify
content, guide attention, express identity or support an action.

## Hierarchy and spacing

- Establish a dominant element, supporting content and quiet metadata.
- Group related items through proximity and alignment before adding containers.
- Use consistent spacing roles and a deliberate rhythm of larger gaps.
- Keep interface labels and buttons on one line; disclose detail progressively.
- Check actual content lengths, small windows and enlarged text.
- Treat numeric size ranges as starting points, then inspect at delivery scale.

## Color

Use the product's palette and semantic roles rather than an imported house brand.
Start with neutral surfaces, readable text and a small number of purposeful
accents. Add semantic colors when the content needs them. Distinguish selected,
focused, disabled, error and success states using more than hue alone.

When a palette is requested, choose it for that product. Keep charts and interface
controls in the same visual family. Follow explicit light/dark and flat-color
requirements. Surface separation can use spacing, borders and contrast.

For web accessibility, use the actual foreground/background pair:
- Normal text: at least 4.5:1 contrast for WCAG AA.
- Large text: at least 3:1. Large means at least 18pt regular or 14pt bold,
  approximately 24 CSS px regular or 18.67 CSS px bold.
- Check applicable non-text contrast requirements for essential controls.
- Text size, weight and the rendered context matter. A palette swatch alone
  cannot establish compliance for every use of that color.

Measure contrast from source values or rendered pixels rather than visual guess.
Use labels, shapes, patterns or icons alongside color. Test the actual light and
dark surfaces independently.

## Typography

Choose type for the content and medium. Keep a small set of roles with consistent
sizes, weights and leading. One family can provide sufficient variation; add a
second when it has a distinct purpose. Short brand display text can take a more
expressive treatment than body text or controls.

For long prose, roughly 45 to 75 characters per line is a useful starting point.
Set leading and measure together. Tune tracking deliberately, especially at large
sizes; body readability takes priority over decorative effects.

- Native macOS: start from the platform's text styles and accessibility behavior.
- Web: choose fonts deliberately, verify their source/license, and provide a
  documented loading strategy. A CDN is an option rather than a requirement.
- PDF: confirm that the chosen generator embeds the required fonts and glyphs.
- PowerPoint: supported versions can embed eligible fonts. Check the target app,
  font embedding permissions and actual export tool. Verify on the recipient's
  platform; use installed/shared fonts when embedding is unavailable.
- Word: verify the document on the recipient's platform and account for font
  embedding/support rather than assuming a universal system-font inventory.

Avoid categorical claims about what every font or document format supports.
Verify current tool capabilities when they affect delivery.

## Data visualization

Select the chart from the question:
- Time trend: line chart.
- Ranking or category comparison: bar chart.
- Distribution: histogram, box plot or appropriate density view.
- Relationship: scatter plot.
- Composition: a readable stacked representation, treemap or suitable small pie.
- Geography: map only when location carries the meaning.
- Flows: flow diagram or Sankey when its encoding helps the reader.

Use real data with clear units, periods, denominators and sources. Preserve
meaningful baselines. Explain transformations and distinguish forecasts from
observations. Label close to the data, reduce incidental gridlines, and split
crowded series into small multiples. Apply sequential or diverging colors only
when their ordering/center has meaning.

Generate precise charts from data with an appropriate plotting tool. Keep an
accessible table or text interpretation. A KPI needs a clear period, unit and
comparison baseline; color alone cannot establish whether a change is beneficial.
Motion should explain a transition and respect reduced-motion preferences.

## Delivery check

Inspect at intended scale: hierarchy, text fit, spacing, contrast, and consistency.
Exercise real controls for interfaces. Load vision-ground-truth before image-based
verification. A screenshot establishes appearance, not functional behavior.

## Verified corrections

[WCAG contrast guidance](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)
and [Microsoft font embedding](https://support.microsoft.com/en-us/office/fonts/benefits-of-embedding-custom-fonts)
were read on 2026-09-11. Recheck when a specific platform/version changes the task.
