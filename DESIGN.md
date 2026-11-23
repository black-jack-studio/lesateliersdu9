# Design

<!-- impeccable:design-schema 1 -->

## World

Fir-green stamp/poster system built from the client's own brand kit, not a generic wellness-studio template. Fir-green (`--color-fir` `#1F4A33`) fields carry structure (header, footer, hero bands, alternating module tiles); beige (`--color-paper` `#EDE6D2`) is the paper ground for reading sections; taupe (`--color-taupe` `#CFC7B6`) hairlines are the only dividing device — no shadows, no rounded cards anywhere in the system.

## Type

- Display/headings: Londrina Solid, uppercase, tight tracking (`-0.02em`), tight leading (`0.92`) — self-hosted via `@fontsource/londrina-solid`.
- Body/UI: DM Sans — self-hosted via `@fontsource/dm-sans` (400/500/700).
- Numbered module markers (`01`, `02`...) run as a real wayfinding sequence across nav and page sections, echoing the kit's sticker/stamp motif — not decorative section numbering.

## Tokens

Defined in `src/styles/global.css` under `@theme` (Tailwind v4): `--color-fir`, `--color-fir-dark`, `--color-paper`, `--color-paper-dim`, `--color-ink` (`#141414`), `--color-cream` (`#FFFFFF`), `--color-taupe`, `--font-display`, `--font-body`.

## Components

- `Header.astro` — sticky fir-green bar, white wordmark, desktop inline nav, mobile full-screen beige takeover menu (pure CSS checkbox toggle, no JS), numbered links.
- `Footer.astro` — fir-green, white wordmark, both practitioners' contact details, address, socials.
- `StickyCta.astro` — mobile-only fixed bottom bar, one or two pill actions (primary fir-filled, secondary fir-outlined); every page declares its own `cta` prop.
- Module tiles (home) — mixed-size grid (two large practitioner tiles, two smaller offer tiles), photo bleeds under a fir-green wash, numbered kicker line, no identical card grid.

## Imagery

All on-site photography (`src/assets/photos/`) is run through a uniform fir-green duotone (`ffmpeg geq`, shadows→`#1F4A33`, highlights→`#EDE6D2`) so the older bohemian-zen photos read as one system with the new identity rather than fighting it. Wordmark assets (`src/assets/brand/wordmark-green.png`, `wordmark-white.png`) are cropped and chroma-keyed to transparency from the client's kit PDF.

## Known gaps / next real content

- Logo is a cropped raster from the kit PDF, not a vector — fine for web use, but ask the client for the original vector/AI file if print work follows.
- Room-rental pricing (`location-de-salles`) and all Casiers locaux content are explicitly fictional placeholders, visually flagged on-page — replace with real data before launch.
- No automated finish-review or documenter subagent pass was run on this build (time-boxed session); a manual desktop + mobile pass was done across all 7 pages instead. Recommend a `/impeccable audit` pass before the client sees it live.
