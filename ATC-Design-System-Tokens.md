# A.T.C Supply 1993 — Design System Tokens

**Version:** 1.0  
**Optimized for:** Webflow Variables + Framer Variables  
**Base unit:** 4px  
**Last updated:** 2026-10-22

---

## 1. Color Tokens

### Primary (Green)

| Token                  | Hex       | RGB                  | Usage                                      |
|------------------------|-----------|----------------------|--------------------------------------------|
| `color-primary-950`    | `#0d2d25` | 13, 45, 37           | Footer bg, strongest text                  |
| `color-primary-900`    | `#123d32` | 18, 61, 50           | Brand mark, header accents                 |
| `color-primary-800`    | `#1b5746` | 27, 87, 70           | Primary button default                     |
| `color-primary-700`    | `#28755a` | 40, 117, 90          | Primary hover, links, icons                |
| `color-primary-600`    | `#2f8a6a` | 47, 138, 106         | Secondary accents                          |
| `color-primary-100`    | `#e7f1eb` | 231, 241, 235        | Light backgrounds, tags, hover soft        |
| `color-primary-50`     | `#f4f8f5` | 244, 248, 245        | Page background, subtle surfaces           |

### Neutral / Ink

| Token                  | Hex       | Usage                                      |
|------------------------|-----------|--------------------------------------------|
| `color-ink`            | `#172b25` | Body text chính                            |
| `color-ink-soft`       | `#2a3d35` | Secondary text                             |
| `color-muted`          | `#63736c` | Description, caption                       |
| `color-muted-light`    | `#8a9a92` | Placeholder, disabled text                 |
| `color-line`           | `#e0e8e2` | Border, divider default                    |
| `color-line-strong`    | `#c5d4cb` | Stronger borders                           |

### Surface

| Token                  | Hex       | Usage                                      |
|------------------------|-----------|--------------------------------------------|
| `color-white`          | `#ffffff` | Cards, inputs, pure white                  |
| `color-surface`        | `#f7faf8` | Section background nhẹ                     |
| `color-surface-dark`   | `#0f2a22` | Dark sections                              |

### Semantic

| Token                  | Hex       | Usage                                      |
|------------------------|-----------|--------------------------------------------|
| `color-success`        | `#2f8a6a` | Success states                             |
| `color-warning`        | `#c9a227` | Warning                                    |
| `color-error`          | `#c45c4a` | Error / destructive                        |
| `color-info`           | `#3a7ca5` | Informational                              |

---

## 2. Typography Tokens

**Font Family**
```
Inter, "Segoe UI", system-ui, -apple-system, sans-serif
```

### Type Scale

| Token            | Mobile   | Desktop     | Line Height | Weight | Letter Spacing | Usage                  |
|------------------|----------|-------------|-------------|--------|----------------|------------------------|
| `text-display`   | 36px     | 56–60px     | 1.08        | 800    | -0.04em        | Hero H1                |
| `text-h1`        | 30px     | 40–44px     | 1.15        | 800    | -0.03em        | Page titles            |
| `text-h2`        | 24px     | 28–32px     | 1.25        | 700    | -0.02em        | Section headings       |
| `text-h3`        | 18px     | 20–22px     | 1.35        | 700    | -0.01em        | Card titles            |
| `text-h4`        | 16px     | 17px        | 1.40        | 650    | 0              | Sub-headings           |
| `text-body-lg`   | 16px     | 17px        | 1.70        | 400    | 0              | Lead paragraphs        |
| `text-body`      | 15px     | 15–16px     | 1.65        | 400    | 0              | Body text              |
| `text-body-sm`   | 14px     | 14px        | 1.60        | 400    | 0              | Secondary text         |
| `text-caption`   | 13px     | 13px        | 1.50        | 500    | 0.01em         | Captions, meta         |
| `text-overline`  | 11px     | 12px        | 1.40        | 700    | 0.14em         | Eyebrows / kickers     |
| `text-button`    | 13–14px  | 13–14px     | 1.20        | 650    | 0.01em         | Buttons                |

### Font Weights

| Token              | Value |
|--------------------|-------|
| `font-regular`     | 400   |
| `font-medium`      | 500   |
| `font-semibold`    | 600   |
| `font-bold`        | 700   |
| `font-extrabold`   | 800   |

---

## 3. Spacing Tokens (4px base)

| Token       | Value  | Common use                     |
|-------------|--------|--------------------------------|
| `space-0`   | 0      |                                |
| `space-1`   | 4px    | Micro gaps                     |
| `space-2`   | 8px    | Icon gaps, tight spacing       |
| `space-3`   | 12px   | Small button padding           |
| `space-4`   | 16px   | Card padding (compact)         |
| `space-5`   | 20px   |                                |
| `space-6`   | 24px   | Default card padding           |
| `space-8`   | 32px   | Medium gaps                    |
| `space-10`  | 40px   |                                |
| `space-12`  | 48px   | Section padding (mobile)       |
| `space-16`  | 64px   | Section padding (desktop)      |
| `space-20`  | 80px   | Large sections                 |
| `space-24`  | 96px   | Hero vertical padding          |

**Semantic aliases**
- `space-section-y-mobile`: 48px
- `space-section-y-desktop`: 68–80px
- `space-card-padding`: 16–24px
- `space-container-x`: 24px (mobile)

---

## 4. Border Radius

| Token          | Value   | Usage                          |
|----------------|---------|--------------------------------|
| `radius-none`  | 0       |                                |
| `radius-sm`    | 6px     | Buttons, inputs, badges        |
| `radius-md`    | 8px     | Small cards, dropdowns         |
| `radius-lg`    | 12px    | Main cards, modals             |
| `radius-xl`    | 16px    | Large cards, hero elements     |
| `radius-full`  | 9999px  | Pills, avatars, status dots    |

---

## 5. Shadows

| Token         | Value                                           | Usage                  |
|---------------|-------------------------------------------------|------------------------|
| `shadow-xs`   | `0 1px 2px rgba(13, 45, 37, 0.06)`              | Very subtle            |
| `shadow-sm`   | `0 4px 12px rgba(13, 45, 37, 0.08)`             | Default card           |
| `shadow-md`   | `0 12px 28px rgba(13, 45, 37, 0.10)`            | Card hover             |
| `shadow-lg`   | `0 18px 48px rgba(13, 45, 37, 0.12)`            | Dropdown, floating     |
| `shadow-xl`   | `0 24px 60px rgba(13, 45, 37, 0.16)`            | Strong elevation       |

---

## 6. Motion

| Token              | Value                              |
|--------------------|------------------------------------|
| `duration-fast`    | 150ms                              |
| `duration-normal`  | 250ms                              |
| `duration-slow`    | 400ms                              |
| `ease-default`     | `cubic-bezier(0.25, 0.1, 0.25, 1)` |
| `ease-out`         | `cubic-bezier(0.16, 1, 0.3, 1)`    |

---

## 7. Layout

| Token                | Value     |
|----------------------|-----------|
| `container-max`      | 1200px    |
| `container-padding-x`| 24px      |

### Recommended Breakpoints

| Name     | Range          |
|----------|----------------|
| Mobile   | ≤ 479px        |
| Tablet   | 768px – 991px  |
| Desktop  | ≥ 992px        |
| Wide     | ≥ 1200px       |

---

## How to import

### Webflow
1. Go to **Variables** panel
2. Create Color / Size / Font variables matching the names above
3. Bind them to Styles

### Framer
1. Create **Color Styles** and **Text Styles**
2. Create **Variables** for spacing, radius, shadows
3. Use inside Components and Variants

### CSS (copy-paste)
See file `atc-tokens.css` in the same folder.
