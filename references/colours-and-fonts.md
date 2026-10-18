# Colour and typography that can be used

## Role-based palette

Translate the chosen direction into a compact palette with exact values, names and uses. Sampled pixels from generated paper/lighting are not the canonical palette.

Separate brand accent, decorative fill, text, functional boundary, disabled and state roles. A darker functional boundary can solve contrast without replacing a brand hue. Calculate actual intended text/background and essential boundary pairs; use unrounded values for decisions and rounded values for display.

For screen guidance, verify current criteria from primary sources when applying them: [W3C text contrast](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html) and [non-text contrast](https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html). Ordinary text generally requires 4.5:1; large text 3:1; relevant essential non-text boundaries 3:1. A 4.48:1 result does not pass 4.5:1 because it rounds up. Contrast results do not certify the entire product or physical printing.

Document forbidden/limited pairs and alternatives. Use shape, labels or pattern when colour alone would carry meaning. For print, define colour and required monochrome treatments explicitly; don't automatically remap the colour PDF to grayscale.

## Real font comparison

Generated lettering is an appearance reference. Compare actual licensed fonts using identical content, line breaks, colour and surrounding layout. Use real upright and italic files/axes. Verify browser loading before screenshotting, so fallback fonts cannot masquerade as candidates.

Show:
- A headline at comparable initial size and an optically adjusted comparison when proportions differ.
- Practical body/labels, digits, long names and all language glyphs at real intended sizes.
- Print specimens where thin strokes or small type matter.

Explain what optical adjustment equalises (for example approximate cap height), and what it does not (weight, lowercase proportions). A selected headline family does not identify logo lettering or approve a body font.

Record family, weight/style, variable axes, source URLs, licence and local files. Retain licences with redistributed fonts. Use open or appropriately purchased fonts according to scope.

## Tokens and documentation

Adapt [tokens.css](../assets/tokens.css); its neutral examples are not recommendations. Keep one canonical tokens source. Existing application token locations take precedence when appropriate. If an export needs a snapshot, generate/record it from that source; do not maintain two hand-edited truths.

Document palette roles and contrast in `palette.md`; type roles, weights, scales and fallback behavior in `typography.md`. Bundle permitted local fonts for portable final artifacts. In generated PDFs verify embedded glyph programs and selectable text rather than trusting CSS declarations.
