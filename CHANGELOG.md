# Changelog

## 1.0 — 2026-03-19

Initial release.

### Features

- **Templates tab** — 21 built-in themes as live-colored cards with Preview / Load buttons
- **Selective template merge** — loading a template preserves `bg_image`, `extends`, `sections`, `dev_tools`, `chassis`
- **Palette tab** — 14 color pickers with role labels
- **Palette generation** — from image, from base color (both via matugen), or random (colorsys)
- **Dark / Light dropdown** — governs all three generation modes; no repeated dialogs
- **Typography tab** — font family and three size sliders
- **Sections tab** — reorder and toggle visible sections
- **Dev Tools tab** — add, remove, and reorder development tool entries
- **Window tab** — width, full height, mini height
- **Effects tab** — animation (type, scope, color, opacity, speed, drops), gradient bar, background image
- **General tab** — layout, default mode, chassis override
- **About tab** — version, author, GitHub / web links
- **Export theme dialog** — choose which keys to include; Select all / Deselect all
- **Live preview** — launches vsFetch with current unsaved settings via temp config
- **Dirty state tracking** — ● indicator in title, confirm-before-discard on Reset / Load / Open / Close
- **Keyboard shortcuts** — Ctrl+S, Ctrl+O, Ctrl+R
- **Dark / Light editor UI toggle**
- **Single executable** — no build step, no dependencies beyond python-gobject
