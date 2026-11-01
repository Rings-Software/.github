# Rings Software — Brand Identity & Visual Design Standard

> **Design reference:** Rings Software identity board supplied on 2026-11-01.  
> **Scope:** Organization-wide brand direction and the intended visual specification for [Rings Software Project #17](https://github.com/orgs/Rings-Software/projects/17).  
> **Status:** Reference standard for future design work. The supplied board is raster artwork; production vector masters and tested color/contrast combinations must still be validated.

## Identity

**Company:** Rings Software  
**Motto:** *We build extraordinary software, and every detail is intentional.*

The mark consists of three interwoven, precision-crafted metallic bands forming a continuous, dimensional ring. It connects a **Lord of the Rings** heritage (craftsmanship, creation, mastery, enduring value) with an **automotive engineering** inspiration (precision, performance, timeless design). These are references for the design rationale, **not** permission to copy a film property or automotive manufacturer's trademarks.

### Core identity rules

- Preserve the approved ring's recognizable topology, proportions, restrained copper reflections, and brushed-silver / graphite construction.
- Use the approved **Rings** wordmark with **SOFTWARE** beneath it, generously tracked, and copper divider accents; do not generate a substitute wordmark from a typeface.
- Keep the ring and wordmark visually consistent in horizontal, stacked, icon-only, and GitHub application variants.
- Use subtle materials and accurate highlights on marketing imagery. Prefer simpler, flat or monochrome variants for tiny icons, code/UI surfaces, accessibility, and reproduction.
- No medieval-fantasy ornament, magical glows, sparks, busy 3D effects, neon accents, or unrelated visual motifs.
- Maintain a premium **software engineering** identity: precise geometry, excellent optical alignment, restrained gradients, clear hierarchy, deliberate details, and proven usability.

## Color palette

The following values are the **hex codes printed on the supplied 2026-11-01 reference board**, not re-estimated from sampled pixels.

| Token | Role | HEX | Usage |
| --- | --- | --- | --- |
| **Graphite** | Foundation | `#0B0D12` | Primary dark backgrounds, deep surfaces and image foundations |
| **Steel Grey** | Secondary neutral | `#8E949B` | Metallic midtones, borders, disabled/secondary UI |
| **Silver** | Light neutral | `#E6E8EB` | Primary foreground on dark surfaces, polished metallic highlights |
| **Copper** | Signature accent | `#C68A57` | Accent separators, small focal details, restrained emphasis |

**Application guidelines:** Use Graphite as the dominant background, Silver for readable foreground text, Steel Grey for depth/secondary elements, and Copper as a selectively applied accent. The ring's reflective silver and warm copper highlights are *artwork treatments*, not gradients that should be applied to all UI controls. Keep semantic success, danger, warning, and focus states distinct, explicitly labeled, and accessible. Do not rely on copper alone to convey state. Validate contrast in actual light/dark screens rather than inferring accessibility from the reference board.

## Typography

| Family | Purpose |
| --- | --- |
| **Sora** | Primary — brand and display headings, titles, selected prominent UI elements |
| **Inter** | Secondary — body text, interface, controls, technical documentation |

Keep consistent capitalization, optical alignment, measured tracking, and a clear hierarchy. The outlined **Rings** logotype is a fixed artwork asset and should **not** be redrawn by merely typing “Rings” in Sora. Package licensed font assets when needed and provide readable system fallbacks.

## Core values

1. **Engineering Excellence:** Robust, performant, reliable software.
2. **Precision:** Every detail is intentional and justified.
3. **Craftsmanship:** High-quality, durable, well-crafted solutions.
4. **Purposeful Innovation:** Meaningful progress, not novelty for its own sake.
5. **Premium Experience:** A refined, coherent, high-performance user experience.
6. **Timeless Sophistication:** Modern, enduring, and recognizably Rings Software.

## Logo system & applications

| Variant | Intended application |
| --- | --- |
| **Horizontal lockup** | Organization pages, repository banners, website header, documents |
| **Stacked lockup** | Brand/marketing compositions with constrained width |
| **Icon / favicon** | GitHub organization avatar, apps, runners, compact UI |
| **Dark icon tile** | Graphite with high-contrast metallic ring |
| **Light icon tile** | Silver/light neutral with an appropriately contrasting ring |
| **Monochrome / outline** | Small, flat, engraved, low-color, accessibility-sensitive use |

Derive every variant from the same reviewed master geometry. A rendered promotional composition is not a substitute for the vector source. Avoid cutting off the ring or introducing inconsistent band intersections.

## Visual language

- **Precision:** Clean metallic arcs, fine controlled highlights, balanced negative space, aligned grid, disciplined spacing.
- **Craftsmanship:** Subtle tactile material cues and copper accents only where they strengthen the composition.
- **Technology:** Dark engineered surfaces, precise overlaps and restrained silver/blue-neutral specular reflections; do not invent a separate bright-blue brand accent.
- **Interaction:** Clear hover/focus states, keyboard access, understandable copy, semantic feedback, reduced-motion support and minimal distraction.
- **Performance:** Prefer lean assets, correctly sized images, and no unnecessary animated or expensive effects.

## Project #17 implementation checklist

- [ ] Update Project #17's title/short description/README to reflect **Rings Software** and the current identity board; preserve unrelated project planning content.
- [ ] Replace superseded Vanguard Software / VGSW / Bridge 08 logo, palette, and typography instructions **where they describe the current corporate standard**.
- [ ] Record the four canonical hex values and the Sora + Inter typography split.
- [ ] Update design acceptance criteria and linked work items, without changing unrelated execution status, due dates, assignees, or priorities.
- [ ] Use the exact reviewed horizontal, stacked, and icon-only artwork when production masters become available; assess small sizes, light/dark, and accessibility.
- [ ] Review visual consistency across GitHub banners, repository identities, GitHub App avatars, runner imagery, installer/webview UI, and documents.
- [ ] Preserve real user-task clarity, software correctness, performance, and accessible semantics over decorative matching.
- [ ] Attach/link the approved reference board and reviewed vector/color assets in Project #17 once those files are stored in a persistent, accessible location.

### GitHub Projects color constraints

GitHub Projects does not offer arbitrary HEX styling for the whole board. Its single-select field options use built-in colors rather than custom HEX values. For brand-aligned custom field options, **GRAY** is the closest native neutral and **ORANGE** the nearest native copper analogue; these are **visual approximations only**, not substitutes for the official palette. Preserve semantic status colors so project workflow meaning remains clear.

## Migration notes

Prior issue content may still claim that the **VGSW Bridge 08** V-shaped logo, **Instrument Sans**, and earlier palette are the corporate master. Those statements predate this 2026-11-01 Rings Software reference and must not be carried forward as current visual identity requirements. Retain technical/functional acceptance criteria unaffected by the identity change. The historical wording may remain visible in audit trails, but new implementation work must use the latest approved corporate direction.
