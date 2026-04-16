---
name: awesome-design
description: >
  Brand-inspired design system library. Use when the user wants to build UI
  in the style of a known brand or website. Trigger phrases: "用XX风格",
  "XX style", "design system", "DESIGN.md", "品牌设计", "设计风格",
  "like Linear", "like Stripe", "Apple风格", "Notion风格", "做个XX风格的页面",
  "参考XX的设计", "UI风格", "暗色主题", "dark mode", "brand theme".
version: 1.0.0
category: design
---

# Awesome Design — Brand Design System Library

You have access to **68 curated DESIGN.md files** inspired by world-class brands.
Each file contains a complete design system specification: colors, typography,
spacing, component styles, shadows, responsive rules, and agent prompts.

## When to Use

- User asks to build UI "in the style of" or "inspired by" a brand
- User wants a specific visual aesthetic (dark mode, minimal, playful, etc.)
- User says "use XX design system" or "参考XX的设计"
- User wants consistent UI tokens (colors, fonts, spacing) from a known brand

## How to Use

### Step 1: Identify the Brand

Match the user's request to one of the 68 available brands below.
If the user describes a *vibe* rather than a brand name, suggest the best match:

| Vibe | Suggested Brand |
|------|-----------------|
| Dark, minimal, engineering | linear.app, cursor, warp |
| Warm, editorial, clean | claude, notion, cal |
| Bold, energetic, consumer | nike, spotify, uber |
| Premium, luxury, automotive | ferrari, lamborghini, bmw, bugatti |
| Developer-focused, technical | vercel, supabase, hashicorp, sentry |
| Fintech, trust, precision | stripe, revolut, wise, coinbase |
| Playful, creative, colorful | figma, framer, miro, airtable |
| Enterprise, professional | ibm, mongodb, intercom |
| Futuristic, sci-fi | spacex, nvidia, tesla, playstation |

### Step 2: Read the DESIGN.md

```
references/{brand}/DESIGN.md
```

Read the full file. It contains 9 sections:

1. **Visual Theme & Atmosphere** — mood, density, philosophy
2. **Color Palette & Roles** — semantic names + HEX + functional roles
3. **Typography System** — font families, full hierarchy table
4. **Component Styles** — buttons, cards, inputs, navs with states
5. **Layout & Spacing** — spacing scale, grid, whitespace philosophy
6. **Depth & Elevation** — shadow system, surface layers
7. **Do's & Don'ts** — design guardrails and anti-patterns
8. **Responsive Behavior** — breakpoints, touch targets, collapse strategies
9. **Agent Prompt Guide** — quick color reference, ready-to-use prompts

### Step 3: Apply to Code

When generating HTML/CSS/React/any UI code:
- Use the exact color values from the DESIGN.md
- Follow the typography hierarchy (font-family, weights, sizes, letter-spacing)
- Apply the shadow and border systems as specified
- Respect the Do's & Don'ts section
- Follow responsive breakpoints

### Step 4: Combine if Needed

Users may want to mix elements from multiple brands. In that case:
- Read multiple DESIGN.md files
- Clearly state which tokens come from which brand
- Resolve conflicts by asking the user or defaulting to the primary brand

## Available Brands (68)

### AI & LLM Platforms
claude, cohere, elevenlabs, minimax, mistral.ai, ollama, opencode.ai,
replicate, runwayml, together.ai, voltagent, x.ai

### Developer Tools & IDEs
cursor, expo, lovable, mintlify, raycast, vercel, warp

### Backend / Database / DevOps
clickhouse, hashicorp, mongodb, posthog, sanity, sentry, supabase

### Productivity & SaaS
cal, intercom, linear.app, notion, resend, superhuman, zapier

### Design & Creative Tools
airtable, figma, framer, miro, webflow

### Fintech & Crypto
binance, coinbase, kraken, mastercard, revolut, stripe, wise

### E-commerce & Retail
airbnb, nike, pinterest, shopify

### Media & Consumer Tech
apple, clay, composio, meta, nvidia, playstation, spacex, spotify,
theverge, uber, wired

### Automotive
bmw, bugatti, ferrari, lamborghini, renault, tesla, vodafone

## Notes

- Source: [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md)
- License: MIT
- These are NOT official brand design systems — they are curated starting
  points inspired by each brand's public website.
- All DESIGN.md files are stored locally in `references/{brand}/DESIGN.md`
