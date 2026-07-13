<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shuttering/.github/main/profile/assets/mark-dark.svg">
  <img alt="shuttering — the reusable form every app is cast in" src="https://raw.githubusercontent.com/shuttering/.github/main/profile/assets/mark.svg" width="112" height="112">
</picture>

### The reusable form every app is cast in

**One design system, distributed as a swappable token contract.**

Every surface in the org — sites, docs, dashboards — is cast in the same form: one
contract of CSS custom properties, filled by an interchangeable **ground** and
**accent**, so each product reads as itself while sharing the same bones.

[`@shuttering/starlight`](https://github.com/shuttering/starlight) &nbsp;·&nbsp; the one public member

</div>

---

### The contract &nbsp;·&nbsp; five orthogonal seams

A theme is the set of custom properties that give an app its look. Fill the seams
and you have a complete, drop-in theme — and because they're orthogonal, any ground
composes with any accent, both flipping light ↔ dark at runtime.

- **ground** (`data-ground`) — the near-neutral surface set: background, card,
  popover, muted, border, and the rest
- **accent** (`data-palette`) — primary, ring, and a brand gradient
- **fonts** — bring-your-own via `--font-*-face`, so a system takes the theme
  without inheriting a typeface
- **radius** + **scrollbar** — the corner feel and a reveal-on-intent overlay bar

Reference grounds (`paper` · `void` · `slate`) and palettes (eucalyptus · indigo ·
amber · rose · slate · emerald) ship built in; author your own by filling the same
seams.

### The family

A monorepo of scoped packages, each a single concern, consumed across the org:

- **tokens** — the theme contract above: grounds, palettes, and the identity-neutral
  base plumbing (reset, scrollbar, focus ring, reduced-motion)
- **motion** — canvas + DOM motion primitives that self-inject their own CSS
- **ui · charts · signature** — components, data-viz, and brand marks
- **starlight** — a Starlight docs theme cut from the contract; the one member on
  **public npm**, so any docs site pulls it without a token

### The cut

`@shuttering/starlight` is public. The rest is an internal design system, published
to GitHub Packages and consumed by the org's apps — [nanohype.dev](https://nanohype.dev),
[rackctl](https://github.com/rackctl), and their tenants — so they share one form
while keeping their own face.

---

<div align="center">
  <sub><b>shuttering</b> &nbsp;·&nbsp; the reusable form every app is cast in</sub>
</div>
