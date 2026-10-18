---
name: branding-skill
description: Create or finish a product brand in Codex, from positioning and naming through visual identity, logo assets, tone of voice and a production-ready brand book. Use for a coherent branding process or continuation of existing brand work, rather than an isolated graphic edit.
---

# Brand identity in Codex

Turn the owner's intent and existing work into usable brand materials. Complete the design and exports in Codex using available tools; an external design application is optional only when the owner requests it. Adapt the scope to the product, its stage and intended channels.

## Start with evidence

Read existing brand decisions, briefs, source assets, references and relevant project instructions. Do not restart settled naming or identity work. Distinguish current decisions from historical experiments and AI recommendations.

Read [working with the owner](references/working-with-the-owner.md) and [pitfalls](references/pitfalls.md) at the start. Use the [brief template](assets/brief.md) to capture missing context: product, audience, differentiation, channels, languages, existing identity and practical constraints. Infer answers supported by the project; ask only material gaps in small batches.

Use the owner's language in conversation and deliverables unless requested otherwise. Explain design choices through visible examples and their effect on the product. Carry out authorized work; seek choices when an unresolved owner decision actually affects the next work. A step is not an automatic permission gate. Continue independent preparation while a needed answer is pending.

## Decisions and scope

Maintain `brand/decisions.md` using the [decision template](assets/decisions.md). For each decision record its source, date, scope, status and files. Use these distinctions:
- **Proposed:** prepared for review.
- **Approved for development:** accepted working direction, including “approved for now”.
- **Approved final:** explicitly accepted for the stated final use.
- **Rejected / superseded:** retain in history, exclude from current guidance.
- **Unverified:** a fact or production check has not been established.

A new human instruction takes precedence over an older log. An AI vote never supplies approval. Approval of headline type does not approve logo lettering; approval of a style does not approve every future asset.

Keep an index of current materials separate from history. Update affected current references when a decision changes; do not rewrite historical evidence to imply it was always current. Preserve unrelated application code and existing work. A branding request does not by itself authorize deployment, registration, purchase or contacting others.

## Workflow and references

Use this order as a dependency guide, not a requirement to repeat completed work. Read only the reference for the work being done.

| Work | Output and reference |
| --- | --- |
| Product and positioning | `brief.md`: audience, need, promise, difference, evidence, brand personality. [Brief](references/brief.md) |
| Name, if open | Screened shortlist and checks. Do not rebrand an already selected name. [Naming](references/naming.md) |
| Verbal identity | Voice principles, messages, tagline candidates, copy examples and glossary. [Voice](references/tone-of-voice.md), [template](assets/tone-of-voice.md) |
| Visual direction | A small fair comparison using identical specimens and the owner's references. [Visual direction](references/visual-direction.md), [prompt](assets/mood-board-prompt.md) |
| Logo | Faithful development of the selected direction, vector master when feasible, variants and usage. [Logo](references/logo.md) |
| Colour and type | Real licensed font specimens, role-based palette and canonical tokens. [Colour and type](references/colours-and-fonts.md), [tokens starter](assets/tokens.css) |
| Graphic system | Signature elements, SVG utility icons, pictures and optional theme accents. [Icons and pictures](references/icons-and-pictures.md) |
| Real use | Populated examples, components, quiet/error states and applicable print checks. [Applications](references/applications.md), [print](references/print-rules.md) |
| Final production | Final source assets, exports, brand book, voice guide and curated delivery. [Brand book](references/brand-book.md), [delivery](references/delivery.md) |

For complex design rounds, use a small art-director/challenger team as described in [team.md](references/team.md), within the tools and agent limits available. Do not simulate independent agents as actual human research. Single-agent work remains valid when delegation is unavailable.

## Essential production rules

- Treat existing owner-supplied logo/art as source authority. If a faithful master is missing, preserve the reference, explain the limitation and resolve it before declaring the logo production-ready. Never substitute an approximate wordmark silently.
- Use image generation for raster exploration and artwork when available; use SVG/code for precise vector construction, typography specimens and utility icons. An image-generation outage blocks those assets, not unrelated strategy, copy or vector work. Follow an available image-generation skill when using its tool.
- Generated moodboard lettering and colours are inspiration, not identified fonts, exact colour values or editable assets. Develop selected components individually.
- Test actual outputs at intended size. Inspect browser renders, exported PDFs and transparent images where applicable. Record what passed and what remains untested. Do not equate geometry checks, peer review or colour ratios with physical testing, user research or a complete accessibility audit.
- Read [guardrails](references/guardrails.md) for project-specific constraints, privacy and provenance. Do not import NieZamulaj's palette, audience, no-magic preference or progress mechanics into another brand.

## Files and completion

Use the owner's chosen location; otherwise work in `brand/`. Create only relevant outputs:

```text
brand/
  brief.md, decisions.md, tone-of-voice.md
  name/                       only when naming is in scope
  explorations/               dated alternatives and critiques
  logo/                       source, exports, usage
  tokens.css, palette.md, typography.md
  icons/, pictures/, components/
  applications/               editable examples and previews
  print/                      sources, PDFs, calibration when needed
  brand-book/index.html       responsive, portable reference
  brand-book/brand-book.pdf    reviewed shareable export
  delivery/START-HERE.md       current package index and status
  delivery/asset-register.csv
  delivery/qa.md
  history/                    superseded work, excluded from final bundle
```

Templates for [asset inventory](assets/asset-register.csv), [delivery notes](assets/delivery.md), [QA](assets/qa.md) and [HTML brand book](assets/brand-book.html) support the final pass. Resolve essential open creative decisions before presenting a final standard. If an external dependency prevents completion, deliver a clearly labelled working package with the precise missing item; do not call a preparation bundle a finished brand.

Before finishing, use [delivery.md](references/delivery.md) to check editable logo + exports, brand book HTML + PDF, voice guide, tokens/type/licences, in-use examples, applicable graphic assets and honest QA. Provide a portable curated ZIP and a clear entry file. Link the useful files and identify any material remaining limitation. Publishing is a separate action requiring authorization.

## Evidence from NieZamulaj

[Worked example](references/worked-example.md) records accepted methods, rejected approaches and approval scope through 18 October 2026. It is a case study, not the default identity for a new project. NieZamulaj's final book and mockups were reserved for Claude Design; future runs of this skill complete those outputs in Codex.
