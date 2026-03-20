# Design Vibes

**Find your aesthetic. Copy the prompt. Build beautiful interfaces with AI.**

A visual reference tool for 25+ design aesthetics. Browse styles, compare them side-by-side, and copy AI-ready prompts straight into ChatGPT, Claude, or Midjourney to generate interfaces that actually look intentional.

**Live site:** [rohitjz.github.io/Design-vibes](https://rohitjz.github.io/Design-vibes/)

<img width="1808" height="1342" alt="image" src="https://github.com/user-attachments/assets/8eab0856-5a3c-4eb4-b479-9df32a6c6e01" />

## What It Does

Each design aesthetic includes:

- **Visual preview** with the style applied directly to the card
- **AI prompt** (150-200 words) describing colors, typography, spacing, and effects in enough detail for an LLM to reproduce the style
- **CSS implementation hints** for manual builds
- **Accessibility rating** so you know what you're trading off
- **Brand examples** showing who uses the style in production
- **"Best for" tags** (SaaS, portfolio, startup, e-commerce, etc.)

## Featured Styles

| Category           | Styles                                                      |
| ------------------ | ----------------------------------------------------------- |
| **Trending** | Glassmorphism, Liquid Glass, Material You, Dark Mode + Neon |
| **Modern**   | Neumorphism, Bento Grid, Gradient Mesh, Aurora UI           |
| **Playful**  | Neo Brutalism, Claymorphism, Y2K, Vaporwave                 |
| **Classic**  | Bauhaus, Swiss/International, Art Deco, Editorial           |
| **Minimal**  | Minimalism, Japandi, Monochrome, Whitespace-first           |

## Features

- **Search** across all styles in real time
- **Filter** by category (Trending, Modern, Classic, Playful, Minimal)
- **Multi-select and compare** 2-4 styles side-by-side
- **One-click copy** of AI prompts with visual feedback
- **Detail panel** with extended descriptions, similar styles, and brand references
- **Fully responsive** single-page app, works on mobile

## Tech

Single HTML file. No frameworks, no build step, no dependencies.

- CSS Grid layout with glassmorphic cards
- Backdrop-filter blur effects with webkit fallback
- Keyframe animations (floating orbs, pulse, glitch)
- Playfair Display + Inter typography pairing
- Dark theme (#0a0a12 base) with blue/purple/cyan accents

## How to Use

1. Browse or search for a design aesthetic
2. Click a card to see full details and the AI prompt
3. Hit **Copy Prompt** and paste into your AI tool of choice
4. Build your interface using the style's color palette, typography, and layout rules

## Run Locally

```bash
git clone https://github.com/rohitjz/Design-vibes.git
cd Design-vibes
open index.html
```

No server needed. It's just HTML.

## License

MIT
