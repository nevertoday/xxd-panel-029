# XXD Panel 029 | Horizontal-Field Wax-Pastel Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the one source photograph explicitly supplied for this current task. Lock the principal subject or inseparable relation, core proportion, contour flow, pose, direction, action, function, relational distance, and colour character. Preserve at least three source-specific recognition cues. Never borrow a horizontal field, wax-pastel rhythm, palette, copy, or composition from old outputs, samples, or another input.

## One horizontal low-saturation paper field

Place one horizontally extended low-saturation paper-colour field on rough ivory handmade stock. Derive and reharmonise its hue, warmth, value, and emotion from the current photograph's composite colour and atmosphere. Never fix it to pink, blue, green, brown, or beige, and never reuse the previous source's field colour.

The field only relates subject and space; it is not scenery or decoration. Let subject weight, direction, action, and contour flow determine field height, vertical position, subject scale, offset, crop, and whether the subject crosses the upper or lower boundary. Horizontal field, subject mass, positive/negative shape, and upper/lower whitespace must form one deliberate ratio system rather than default centring.

Use only this one principal field. Reject multiple colour panels, borders, patterns, stickers, tape, stamps, scattered icons, repeated motifs, and cheap scrapbook decoration.

## Light matte wax-pastel subject

Simplify the subject into light-coloured matte wax-pastel masses and marks. Remove busy detail while preserving core proportion, contour flow, pose, direction, action, function, and relation so the original remains recognisable at first glance.

Marks are loose, casual, irregular, slightly broken, and rich in rough friction. Coverage may vary subtly; edges may locally gap, double-touch, flatten, or reveal paper fibre, but defining contours stay readable. Never turn it into mechanically closed outlines, smooth digital illustration, realistic modelling, or a children's cartoon.

Keep restrained double-paper depth: the horizontal field reads as a low-saturation second paper layer on coarse ivory stock, with only delicate edge difference rather than complex collage. Add mild ageing, Risograph grain, and tiny registration imperfection while keeping the piece clean, premium, and quiet.

Reject opaque acrylic blocks, oily crayon shine, coloured-pencil hatching, watercolour bloom, ink wash, impasto, realistic shadow, complex lighting, 3D, glossy vector polish, and dirty filters.

## Source colour and whitespace

The horizontal field is the principal colour event. Lower saturation, unify temperature, and soften the source's composite palette without erasing its distinct warm/cool relation or emotional character. Keep the subject primarily light and chalky, with only restrained source-derived tonal changes required for recognition.

Ivory handmade paper and upper/lower whitespace remain clearly visible. Recompose field ratio, subject scale, boundary crossing, whitespace, type, and safe regions for every device and aspect ratio; never crop another result.

## Relaxed handwritten copy

Obey the resolved automatic, exact-user, or text-free copy mode and target language or locale. Preserve exact user wording verbatim. In text-free mode render no letter, character, number, handwriting trace, text, or pseudo-text.

Automatic copy distils one short line from the photograph's visible or supported emotion, action, state, relation, or metaphor. Add zero to two micro-elements only when genuinely useful. Places, dates, numbers, and provenance must be user-supplied or reliably established and are never fabricated.

Use a natural soft, loose, slightly scribbled but readable handwritten equivalent for the target script. Let it follow the field edge, subject gesture, or open paper, with optional light interweave, offset, or boundary crossing. It must feel drawn into the work. Reject formal typeset titles, bold slogans, commercial script fonts, giant text, glow, and pseudo-foreign writing.

## Mode and acceptance


Hard gate: at least three source cues and the principal action or relation; one source-derived horizontal low-saturation paper field; deliberate field height, subject scale/offset/crop/crossing, and upper/lower whitespace ratio; light matte wax-pastel subject preserving core proportion and flow; loose broken friction marks catching coarse fibre; credible restrained double paper, mild ageing, Risograph grain, and tiny registration shift; native readable handwriting integrated with field, subject, or whitespace; no fixed palette, children's cartoon, cheap scrapbook, acrylic blocks, decorative clutter, realistic modelling, plastic 3D, photo fragment, or pseudo-text.

If any hard condition fails, correct the generated asset. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, or a post-composited type overlay.
