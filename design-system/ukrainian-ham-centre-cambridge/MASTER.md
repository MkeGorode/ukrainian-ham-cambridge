# Ukrainian HAM Centre (Cambridge) - Master Design & Copywriting System

## 1. Product & Audience Profile (`ui-ux-pro-max`)
- **Product Type:** Grassroots Non-profit / Refugee Support & Cultural Community Charity + Grant/Donor Portal
- **Primary Style:** Accessible & Ethical (`WCAG 2.1 AA/AAA`) + Editorial Grid (`Storytelling + Trust & Authority`)
- **Reference Benchmark:** Ukraine Appeal (`ukraineappeal.org.uk`, Milton Keynes, Charity No. 1199404) adapted to Cambridge's academic, civic, and community ecosystem.
- **Three Core Personas:**
  1. **Grantmakers & Institutional Partners (Cambridge City Council, National Lottery, Cambridgeshire Community Foundation, University Colleges):** Look for measurable social outcomes, refugee/senior vulnerability relief, safeguarding policies, and governance transparency.
  2. **British Donors, Hosts & Cultural Supporters:** Look for tangible micro-impact (`£15` / `£30` / `£50` tiers), transparent fund allocation, and vibrant Ukrainian-British cultural events.
  3. **Displaced Ukrainians, Seniors & Youth in Cambridgeshire:** Need clear bilingual (`UA / EN`) navigation, large readable typography for older adults, schedules, addresses (`40-43 St Andrew's Street` and `12-14 Fitzroy Street`), and easy registration.

## 2. Three-Layer Token Architecture (`design-system`)

### Layer 1: Primitive Tokens
- `--color-blue-900: #10233E` (Deep Cambridge Navy Ink)
- `--color-blue-800: #132F5E` (Institutional Deep Blue)
- `--color-blue-600: #2458AB` (Official HAM Letterhead Royal Blue)
- `--color-blue-100: #EBF2FC` (Soft Sky Tint)
- `--color-yellow-400: #FBEB64` (Official HAM Seal Medallion Yellow)
- `--color-gold-500: #E4C93B` (Warm Accessible Action Gold)
- `--color-slate-900: #10233E`
- `--color-slate-600: #4A5E7A`
- `--color-slate-200: #DAE4F2`
- `--color-white: #FFFFFF`
- `--color-paper: #F7FAFE`

### Layer 2: Semantic Tokens
- `--surface-page: var(--color-paper)`
- `--surface-card: var(--color-white)`
- `--surface-brand: var(--color-blue-600)`
- `--surface-brand-deep: var(--color-blue-800)`
- `--text-primary: var(--color-slate-900)` (Contrast ratio > 12:1 on white)
- `--text-secondary: var(--color-slate-600)` (Contrast ratio > 5.8:1 on white)
- `--accent-cta: var(--color-yellow-400)`
- `--accent-cta-text: var(--color-blue-900)` (Contrast ratio > 11:1 on yellow)
- `--border-subtle: var(--color-slate-200)`

### Layer 3: Component Tokens
- `--nav-height: 86px`
- `--touch-target-min: 44px` (Mobile buttons, language toggle, social squares)
- `--card-radius: 14px`
- `--pill-radius: 9999px`

## 3. Typography & Iconography Rules
- **Headings & UI:** `Plus Jakarta Sans` (Weights: 500, 600, 700, 800; clean geometric legibility matching official letterhead and `ukraineappeal.org.uk`).
- **Editorial & Heritage Quotes:** `Lora` (Serif, Weights: 500, 600, 400 italic; max line length `65ch`).
- **Senior Accessibility Floor:** Minimum `16px` (`1rem`) body text, `1.65` line-height, visible `3px` focus outline (`--color-yellow-400` on dark, `--color-blue-600` on light).
- **Icon Discipline:** Strictly inline SVG icons (`24x24` viewBox, `2px` stroke, `stroke-linecap="round"`). Zero emojis as UI icons.

## 4. Copywriting & Offer Rules (`sales-pitch` + `plain-writing`)
- **Causal Fusion (Survival + Dignity):** Never present culture as an isolated hobby. Frame cultural, educational, and digital programmes as the direct vehicle for trauma recovery, anti-isolation, cyber/financial safety for seniors, and family stability.
- **Concrete Proof Over Abstractions:** Name real Cambridge venues (`40-43 St Andrew's Street`, `Technical Centre at 12-14 Fitzroy Street`), real programmes (`IT School for Seniors & Cyber Safety`, `Community Pantries`, `Youth Volunteering`), and real beneficiaries.
- **Zero AI Tells:** No em-dashes or en-dashes (`-` only), no buzzwords ("seamless", "delightful", "fostering"), no vague claims.
