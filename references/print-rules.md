# Print and physical constraints

Apply only to channels requiring print. Recover actual paper/stock/printer constraints early; do not wait until all decoration is finished.

For each relevant printable record page size, intended number of pages, margins, content capacity, smallest practical text and physical interaction dimensions. One-page A4 is a NieZamulaj requirement, not a universal brand-book rule. Never fit by silently shrinking a required sticker area, dropping content or changing product mechanics.

## Geometry means usable space

Distinguish clear interior, outer frame, stroke and corner radius. Confirm that actual stock fits within the curved interior. Document nominal clearance and distinguish it from tested hand placement.

NieZamulaj's required 30 × 14mm label led to proposed 34 × 18mm clear interiors and 35 × 19mm outer frames. These dimensions illustrate the method; don't copy them into unrelated products.

Use mm/pt for physical dimensions and inspect exported PDF geometry. A screen-scaled A4 preview proves neither PDF sizing nor printer scaling.

## Composition and capacity

Use realistic long text and required fields. Check number/field association, reward prominence, image allocation, reading order and completed-state density. Remove redundant visual cues when they compete; don't add arrows by default. Keep image proportions within a fixed allocation.

When capacity and physical size conflict, show the concrete tradeoff (pages, number of tasks, format) to the owner. Do not silently discard repeat behavior or shrink stock.

## Verification

1. Wait for local fonts/images to load; check DOM overflow and all required targets.
2. Export the actual PDF; inspect page boxes, page count, target interiors, clipping, text and embedded fonts.
3. Render every distinct PDF page with a suitable renderer and visually inspect it.
4. Inspect the separately intended colour and monochrome versions. Pale illustrations and placeholders may disappear even if geometry passes.
5. Prepare a calibration page with a measured ruler/square, actual targets and small text. State “100% / actual size”, fit-to-page off.

Use the available PDF skill for PDF production and inspection. A PDF page-box normalization must not silently scale content. Record tolerances and actual measured output rather than claiming exact mathematical geometry from rounded exports.

Only the owner/device can establish physical printer scaling, stock fit, thermal text and hand placement. Record those as untested until actual results arrive. Deliver the reviewed digital materials while this external test remains pending, clearly labelling the package's production status.

Commercial press colour profiles, bleed or dielines apply only when that channel requires them; do not claim CMYK/ICC certification from a browser PDF.
