---
title: Brand Extraction
sidebar_position: 4
sidebar_custom_props:
  icon: palette
---

Docsio automatically extracts your brand identity from your website and applies it to your documentation. Colors, logo, fonts, and favicon are detected and configured without any manual setup.

## What gets extracted

**Primary and secondary colors**, The AI reads your website's CSS and computed styles to identify your brand color palette. It extracts your primary color, secondary colors, backgrounds, and accent tones.

**Logo and favicon**, Your logo and favicon are downloaded automatically from your website and placed in the correct locations in your documentation project.

**Typography**, Docsio detects which fonts your website uses for headings and body text. Your documentation is configured to use the same fonts so your readers see familiar typography.

**Theme preference**, The AI detects whether your brand leans light or dark and sets the default documentation theme accordingly.

## How it works

When you paste your website URL, the AI agent's first step is brand extraction. It:

1. Fetches your website and analyzes its CSS
2. Identifies your primary and secondary colors
3. Downloads your logo and favicon
4. Detects your heading and body fonts
5. Determines your light or dark theme preference
6. Applies all extracted elements to your documentation

The entire extraction process takes seconds. By the time you see your live preview, your documentation already looks like your product.

## Color extraction

The AI analyzes your website's color palette and identifies:

- **Primary color**, Your main brand color used for buttons, links, and highlights
- **Secondary color**, A complementary color for accents and secondary elements
- **Background colors**, Light and dark backgrounds for different sections
- **Text colors**, Primary and muted text colors for readability

These colors are applied throughout your documentation: navbar, sidebar, links, buttons, code blocks, and more.

:::note
If the extracted colors don't match your brand exactly, you can adjust them. Ask the AI agent to change the primary color or any other color in your documentation.
:::

## Logo and favicon

Your logo is automatically downloaded and placed in your documentation's navbar. Your favicon appears in browser tabs and bookmarks.

If you want to use a different logo or favicon, you can upload a new one through the editor or ask the AI agent to update it.

## Typography

Your documentation uses the same fonts as your website. If your website uses Inter for body text and JetBrains Mono for code, your documentation will too.

You can change fonts at any time by asking the AI agent to update the typography or by editing the CSS directly.

## Dark mode

Docsio automatically creates a dark mode version of your extracted colors. The dark mode uses lighter tints of your brand colors to maintain readability on dark backgrounds.

Your readers can toggle between light and dark mode. Both themes use your brand colors consistently.

:::tip
Test your documentation in both light and dark mode to ensure colors are readable and look good in both themes.
:::

## Customization

The extracted brand is a starting point. You can customize any aspect:

- **Change colors**, Ask the AI agent to change the primary color or any other color
- **Update logo**, Upload a new logo or favicon
- **Modify fonts**, Change typography or add custom fonts
- **Adjust theme**, Switch between light and dark mode as the default

All customization can be done through the AI agent without touching code.

## See also

- [Quick start](/docs/getting-started/quickstart), get your first site live in 30 seconds.
- [AI Editing Agent](/docs/features/ai-agent), customize colors and branding.
- [How it works](/docs/getting-started/how-it-works), the five-phase generation process.
