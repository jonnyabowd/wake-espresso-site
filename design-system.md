# Wake Espresso — Design System

## Colors

| Token | Value | Usage |
|---|---|---|
| `--color-brand-blue` | `hsl(189, 90%, 46%)` | Primary brand color, CTA buttons, accents |
| `--color-brand-cream` | `hsl(55, 100%, 98%)` | Light backgrounds, text on dark |
| `--color-brand-grey` | `hsl(0, 0%, 33%)` | Background the logo is designed to sit on |
| `--color-text-muted` | `hsl(0, 0%, 67%)` | De-emphasized text, inactive UI elements |

## Logo

Files are in `/images/`:
- `WE_logo.svg` — full wordmark, use at larger sizes
- `WE_icon.svg` — icon only, use for favicons and small contexts

Logo is designed to display over `--color-brand-grey` (`hsl(0, 0%, 33%)`).

## Typography

| Token | Value |
|---|---|
| `--font-family-base` | TBD |
| `--font-size-base` | 16px |

## Spacing Scale

| Token | Value |
|---|---|
| `--space-xs` | 4px |
| `--space-sm` | 8px |
| `--space-md` | 16px |
| `--space-lg` | 32px |
| `--space-xl` | 64px |

---

All tokens are defined in `/css/tokens.css`. Always reference tokens in code rather than hardcoding values.
