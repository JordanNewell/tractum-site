# claudeway-site (Tractum) — Design Notes

> See README §Brand — this file records the pointer per repo-standards.
> Tractum has its OWN brand system, separate from NEWELL.

## Canonical

- **Tractum Brand System v0.1 (Seal Amber)** — canonical source:
  vault `10_PROJECTS/tractum/brand/`.
- Tokens are inlined as CSS custom properties at `:root` in `index.html`.

## Tokens (as shipped)

| Token | Hex | Role |
|---|---|---|
| `--primary` | `#FFB000` | Seal Amber — accent, ≤10% of any surface |
| `--accent` | `#FFC94D` | Amber lift |
| `--bg` | `#0A0A0A` | NEWELL soft-black background |
| `--surface` / `--surface-2` | `#101010` / `#141414` | Surfaces |
| `--border` / `--border-2` | `#1F1F1F` / `#2A2A2A` | Borders |
| `--text` / `--muted` | `#FFFFFF` / `#9E9E9E` | Text |
| Radii | 4 / 8 / 12 / 20 px | NEWELL radius scale |

## Typography

- Display: JetBrains Mono. Body: Space Grotesk (per README).
- Layout: 8px grid. No gradients, no glow, no indigo.

## Rules

- Pre-flight visual changes against the vault Tractum brand dir.
- Amber is the only accent; NEWELL green does NOT appear on this surface.
