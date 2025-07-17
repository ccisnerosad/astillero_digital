# Copilot Instructions for Astillero Digital

## Big Picture Architecture
- The project is organized around a maritime metaphor, with each zone and component representing a type of digital solution or workflow.
- Main documentation is in `doc/estructura.md` and `astillero_digital.md`, which describe the philosophy, service boundaries, and development process.
- Source code lives in `src/` with subfolders for `components`, `layouts`, `pages`, and `styles`. Static assets are in `public/`.
- The project supports static sites, dynamic microapps, backend APIs, and automation scripts, mapped to "zones" (Lagunas, Ríos, Mar Abierto, etc.).

## Developer Workflows
- Use `npm install` to install dependencies.
- Use `npm run dev` to start the local Astro dev server (default: `localhost:4321`).
- Use `npm run build` to generate the production build in `./dist/`.
- Use `npm run preview` to preview the build locally.
- TailwindCSS v4 is configured in `tailwind.config.js` and/or directly in CSS files. See below for v4 notes.
- Documentation and architecture references are in `doc/estructura.md` and `astillero_digital.md`.

## TailwindCSS v4 Integration
- TailwindCSS v4 uses a new high-performance engine (builds up to 5x faster, incremental builds 100x faster).
- Designed for the modern web: leverages cascade layers, custom properties, color-mix, logical properties, and more.
- Installation is simplified: just `npm i tailwindcss @tailwindcss/postcss` and `@import "tailwindcss"` in your CSS.
- Content detection is automatic; you rarely need to configure the `content` array.
- Supports CSS-first configuration: you can define theme variables and customizations directly in your CSS file using `@theme`.
- All design tokens are exposed as CSS variables for runtime use and animation.
- New utilities: 3D transforms, expanded gradients (linear, conic, radial), container queries, `not-*` variant, `@starting-style` for transitions, and more.
- For Vite projects, use the official plugin `@tailwindcss/vite` for best performance.
- See [Tailwind v4 docs](https://tailwindcss.com/docs) and [upgrade guide](https://tailwindcss.com/docs/upgrade-guide) for details.

## Project-Specific Conventions
- All UI and logic should reinforce the maritime metaphor (zones, navíos, rutas, etc.).
- Use the custom color palette and font defined in `tailwind.config.js` for consistent branding.
- New components should be placed in `src/components/` and follow the naming and thematic conventions (e.g., `BitacoraNavegacion.astro`, `MarAbierto.astro`).
- Layouts go in `src/layouts/`, pages in `src/pages/`, and global styles in `src/styles/global.css`.
- Documentation for new features or zones should be added to `doc/estructura.md`.

## Integration Points & Dependencies
- Astro is the main framework; see [Astro docs](https://docs.astro.build) for advanced usage.
- TailwindCSS v4 is used for styling; see `tailwind.config.js` and CSS files for customizations.
- No backend or database integration is present by default, but the structure supports adding APIs and automation scripts as new "zones".
- Images and icons for the maritime theme are in `logo_prototipos/` and `public/`.

## Examples & Patterns
- To add a new "zona" (service area), create a new component in `src/components/`, update navigation in `src/pages/index.astro`, and document the zone in `doc/estructura.md`.
- For animations, use the gradient animation defined in Tailwind or add GSAP for advanced effects.
- For new workflows, document the process en `astillero_digital.md` y referencia la zona relevante.

## Key Files & Directories
- `doc/estructura.md`: Main architecture and philosophy.
- `astillero_digital.md`: Development process and workflow.
- `src/components/`: Thematic UI components.
- `src/pages/`: Main routes/pages.
- `tailwind.config.js`: Custom styling and animation.
- `logo_prototipos/`, `public/`: Brand assets and icons.

---

For any new feature, ensure it fits the maritime metaphor and update documentation accordingly. If conventions or workflows are unclear, ask for clarification or examples from the user.
