# Beth Shalom GMI — Light Theme Style Guide

## Design direction

A calm, institutional light theme: warm off-white page surfaces, soft gray-green card layers, muted sage actions, and pale mint active states. Deep forest green is retired. Body copy and control labels use dark neutral-sage foregrounds for clear contrast.

## Color tokens

| Token | Value | Use |
| --- | --- | --- |
| `surface` / `background` | `#FFFDFA` | Main page and app backgrounds |
| `surface-container-lowest` | `#FFFFFF` | Cards, forms, dialogs |
| `surface-container-low` | `#F5F6F2` | Page section bands and navigation |
| `surface-container` | `#EEF1EC` | Secondary card surfaces and quiet controls |
| `surface-container-high` | `#E8ECE7` | Hover and raised surface states |
| `surface-container-highest` | `#E1E7E1` | Borders, separators, subtle depth |
| `primary` | `#4C6B55` | Brand text, primary solid buttons, icons |
| `on-primary` | `#FFFFFF` | Foreground on primary buttons |
| `primary-container` | `#DCEBE0` | Selected states, soft primary buttons, pale panels |
| `on-primary-container` | `#263D2E` | Foreground on pale primary panels |
| `secondary` | `#52775E` | Sage CTAs, links, and emphasis |
| `on-secondary` | `#FFFFFF` | Foreground on secondary actions |
| `secondary-container` | `#E2EFE5` | Mint badges, soft highlights, and calm panels |
| `on-secondary-container` | `#2C4533` | Foreground on mint panels |
| `on-surface` | `#202923` | Main body text |
| `on-surface-variant` | `#47534A` | Supporting copy and metadata |
| `outline` / `outline-variant` | `#68756D` / `#C6D0C7` | Focus, borders, and separators |
| `tertiary-fixed-dim` | `#EEC14B` | Limited heritage/gold accent |

## Typography and responsive scale

The established `Source Serif 4` display and `Plus Jakarta Sans` text families remain. Existing Tailwind type tokens and responsive breakpoints are retained. Large titles scale from 34px on compact screens to 48px on desktop; section titles use the existing 28–36px tokens; supporting text ranges from 15–19px with 22–30px line heights.

## Glassmorphism

- Hero card and history panel: white at 68% opacity, 12–24px backdrop blur, 1px translucent white edge, soft shadow.
- Carousel controls: white at 62% opacity, sage border at 22% opacity, dark-sage icons, 10px pill indicators; active indicator uses medium sage.
- Hero video: full-bleed `object-fit: cover`, muted and inline, 90% visible when ready. A warm ivory overlay gradient preserves contrast without a dark forest scrim.
- If the browser requests reduced transparency, the cards use opaque alabaster and disable blur.

## Components and states

### Header

Public pages keep the wordmark and navigation links. The official seal sits at the right edge in a 48×48px white disc after the admission action; both seal and wordmark link home. On narrow screens, the mobile menu remains the route to admission when the compact header action is hidden.

### Homepage hero carousel

- Slides: campus, care, and community footage, clearly attributed as illustrative stock media.
- Controls: previous, next, slide indicators, and pause/play. No central play overlay.
- Motion: autoplay is muted; rotation pauses on hover/focus, page visibility changes, and reduced-motion preference. The source poster remains the no-video fallback.
- Actions: **Virtual Tour** links to `/living-spaces/visualizer/`; the admissions CTA links to `/admission/`.
- History: 1965 society founding, 1967 registration, and current intergenerational care narrative.
- Metric: **60+** years of charitable legacy.

### Cards, forms, and dialogs

White and low-surface cards use a 1px outline-variant edge, 12–24px corner radius, and restrained shadow. Hover/focus states move to `surface-container-high`; selected states use `primary-container` with `on-primary-container`. Solid actions use `primary`/`on-primary` or `secondary`/`on-secondary`. Existing directory, room, donation, admin, and subscription content and behavior are retained; their semantic color tokens now resolve to the light theme.

## Footage sources

All three clips are labeled illustrative and credited in the hero. The clip pages identify them as free to use:

- Campus: [Pexels 32307709](https://www.pexels.com/video/aerial-view-of-lush-green-campus-area-32307709/)
- Care: [Pexels 7522368](https://www.pexels.com/video/a-volunteer-support-a-patient-7522368/)
- Community: [Pexels 27333199](https://www.pexels.com/video/two-older-men-walking-outside-27333199/)

Use approved Beth Shalom footage in place of stock clips when the organization provides it.
