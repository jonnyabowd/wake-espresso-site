# Wake Espresso — Design System

## Colors

| Token | Hex | Usage |
|---|---|---|
| `--color-brand-blue` | `#0cc0df` | Primary brand color, CTA buttons, accents |
| `--color-brand-cream` | `#fffde8` | Light backgrounds, text on dark |
| `--color-brand-grey` | `#545454` | Background the logo is designed to sit on |
| `--color-text-muted` | `#aaaaaa` | De-emphasized text, inactive UI elements |

## Logo

Files are in `/images/`:
- `WE_logo.svg` — full wordmark, use at larger sizes
- `WE_icon.svg` — icon only, use for favicons and small contexts

Logo is designed to display over `--color-brand-grey` (`#545454`).

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
