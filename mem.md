
# Project Memory: Wyatt

## Framework & Architecture
- **Framework**: Astro.js (v5+)
- **Styling**: Tailwind CSS (v4+) with OKLCH color support.
- **Components**: shadcn/ui (React-based) integrated with Astro.
- **Layouts**: Located in `src/layouts/`. `BaseLayout` is the primary wrapper.
- **Sections**: Reusable page sections are in `src/components/sections/`.

## Wyatt Theme Conventions
- **Aesthetic**: Data-centric, techy, Apple-inspired.
- **Interactive Grid Background**: Implemented in `src/pages/index.astro` using CSS `perspective`, `rotateX(60deg)`, and mouse-tracking via `--mouse-x` and `--mouse-y` variables.
- **Data Insights**: Focus on presenting data metrics using cards with `ios-shadow` and backdrop-blur.
- **Typography**: Uses Geist and Geist Mono fonts. Apple-inspired text styling with `.ios-text`.
- **Shadows**: Custom utility classes `.ios-shadow` and `.ios-shadow-lg` for subtle, refined depth.
- **Colors**: Defined in `src/styles/globals.css` using OKLCH format. Primary color is used for highlights and interactive elements.

## Key Files
- `src/pages/index.astro`: The main landing page with the Wyatt theme implementation.
- `src/styles/globals.css`: Global styles, theme definitions, and custom utility classes.
- `PROJECT.md`: Contains project-specific goals and theme details for AI assistants.
- `AGENTS.md`: Standardized instructions for AI coding agents.
