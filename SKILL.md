---
name: abi-brand-guidance
description: Apply AB InBev's corporate visual identity when creating or reviewing corporate presentations, interfaces, or communications. Excludes product-brand guidance unless requested.
---

# AB InBev Corporate Brand Guidance

Use this skill when the user asks for an AB InBev corporate-branded artifact. Create by default; review an existing artifact only when asked. This skill provides the corporate brand layer and does not replace the presentation or interface workflow.

## Scope and source

The source package included with this skill is `ABI Brand Guidelines` version 1.1, last updated January 2022, plus the official assets supplied for this task. The source identifies itself as the visual identity guidance for AB InBev. Use the included files as the source of truth for the supplied artwork. For a future brand refresh, compare the current [ABI Creative Hub](https://brandworld.ab-inbev.com/) and the current internal resource kit, then update the source version and date recorded in `references/assets-manifest.md`.

This is the corporate identity for AB InBev. Do not substitute beer or product brand guidance, or convert local conventions such as BEES yellow, CORA orange, and black outcome blocks into AB InBev corporate tokens.

## How to apply it

1. Identify the artifact and its platform. For slides, use the `Presentations` skill and start from the supplied official PowerPoint template when appropriate. For an interface, use the `ui-ux-pro-max` skill for layout and product UI patterns; apply this skill's identity guidance as the brand layer.
2. Use the supplied logo, pattern, icon, photography, and background assets where they fit the task. Read `references/assets-manifest.md` to find their exact locations. Keep original artwork unchanged; do not redraw, trace, stretch, recolor, rotate, outline, add effects to, or rearrange brand artwork.
3. Separate official rules from your application choices. When the source does not specify a value, say it is missing or choose a clearly labeled implementation value. Never present an inferred value as an official token.
4. For an existing artifact, perform a brand review only when the user requests it. Report concrete deviations and their locations; distinguish confirmed rules from optional improvements.

## Logo and tagline

- Use the supplied logo artwork. The logo consists of the symbol and wordmark; the toolkit also contains symbol and shorthand variants.
- Use the supplied gold, black, or white variant according to the background and contrast examples in the guide. Do not use an unapproved logo color.
- Keep clear space on all four sides equal to the symbol, which is the measurement unit. The guide specifies a minimum logo height of **1.5 in / 38 mm / 30 px**.
- When possible, place the logo at the upper left or use it as a sign-off at the bottom of the page.
- Use the tagline as supplied outline artwork, not retyped text. The approved wording is “To a Future With More Cheers”; the guide recommends it below the logo or as a document sign-off.
- Special expressions inside the symbol are used sparingly and require special permission from the Brand and Marketing team.

## Color

The primary palette is the **Gold Gradient**, balanced by black and white. The gradient example in the supplied guide shows `#D3A238` and `#F5E003` and marks a 25% midpoint. Use the supplied brand artwork or template for exact gradient application; do not invent additional stops or claim an unverified gradient angle.

| Role | Token | HEX | Guidance |
|---|---|---|---|
| Core | Black | `#000000` | Primary palette |
| Core | White | `#FFFFFF` | Primary palette |
| Gradient | Gold Gradient | `#D3A238` and `#F5E003` | Dominant brand color; use supplied artwork/template for exact application |
| Secondary | Gold | `#E5B611` | Use sparingly as an accent with primary colors |
| Secondary | Light Gold | `#F5E003` | Use sparingly as an accent with primary colors |
| Secondary | Dark Gold | `#D1A33C` | Use sparingly as an accent with primary colors |
| Secondary | Light Grey | `#EFEFEF` | Use sparingly as an accent or supporting color |
| Secondary | Dark Grey | `#C7C7C7` | Use sparingly as an accent or supporting color |

The guide also lists tertiary chart colors: Red `#921A28`, Blue `#325A6D`, Beige `#D69E77`, Green `#959B7B`, Light Red `#E88475`, and Brown `#3F1F14`. Limit these to charts and graphs; do not use them as dominant corporate colors.

For text at 12 pt or smaller, the guide specifies these combinations:

- Black text on Gold Gradient, White, Dark Gold, Light Gold, Dark Grey, or Light Grey backgrounds.
- White, Light Gold, or Dark Gold text on a Black background.

For interfaces, check contrast in the actual rendered colors and text sizes against the applicable accessibility standard. The guide's examples do not establish conformance for every web use, color, or text size.

## Typography

**Avantt** is the primary typeface. The guide's editorial stack is:

| Text role | Family/style | Size | Leading | Tracking |
|---|---|---:|---:|---:|
| Headline | Avantt Bold / Light | 80 pt | 80 pt | -20 |
| Large subhead | Avantt Bold | 25 pt | 25 pt | -20 |
| Subhead | Avantt Bold | 15 pt | 20 pt | -20 |
| Body copy | Avantt Book | 10 pt | 13 pt | 0 |
| Caption | Avantt Book | 8 pt | 11 pt | 0 |

These are the guide's editorial layout values, not a responsive web scale. Adapt hierarchy and sizes to the target format while retaining the approved typeface where available. The guide lists **Satoshi** as an alternative and **Arial for Microsoft Office** when Avantt is unavailable. Do not describe an alternative as the primary brand typeface. Avantt requires an appropriate font license; do not include font files unless they are separately supplied and licensed for the intended use.

The guide permits typographic devices such as an eyebrow bar, highlight, or underline, used sparingly and no more than one device per headline.

## Photography and graphic system

- The photography theme is the moment of cheers. Select imagery that conveys connection and optimism, including lifestyle moments, brewing craft, sustainability, and AB InBev brand photography where suitable.
- The guide shows high-contrast black-and-white treatments and a yellow treatment made with the Gold Gradient. Prefer the supplied processed images. Do not invent or modify official photographs as a default.
- The graphic system comes from the symbol's dynamic curves. The guide's composition examples enlarge the symbol so yellow areas reach the layout corners; use the supplied pattern sparingly and on layouts with limited text and graphics.
- Prefer the included icon library. Icons should remain small annotations, not large illustrations. The guide's construction reference for new icons is a 10 × 10 grid, sized to 50 px with a 2.5 px stroke; use this only when a new icon is actually needed.

## Presentations and interfaces

For presentations, use the supplied `PPT Template` as the first reference when the user asks for a corporate AB InBev deck. Preserve its template, editable objects, and original artwork. Apply the guide's logo, color, typography, photography, and composition rules; do not force a decorative brand element onto a data-dense slide.

For interfaces, apply the same corporate identity with the interface skill's responsive, interaction, and component guidance. The corporate brand guide does not define a complete product UI system: it does not supply universal component behavior, breakpoints, spacing tokens, or product-specific interaction states. Use a supplied product design system for those decisions. If none is supplied, use a clear implementation choice and do not label it an official ABI rule.

## Assets and use boundary

The skill bundles a focused set of official files for internal AB InBev work. Use them only for the intended brand application and do not redistribute the bundle outside authorized company channels. The full source directory and the assets included here are inventoried in `references/assets-manifest.md`.

## Updating this skill

The user may ask to refresh the skill when the brand changes. Recheck the ABI Creative Hub and the current internal resource kit, compare them with the bundled January 2022 guide, and update the rules and assets together. Record the source version and date in the manifest. Preserve unresolved details as missing data; do not silently carry forward superseded rules.
