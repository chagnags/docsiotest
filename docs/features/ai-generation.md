---
title: AI Documentation Generation
sidebar_position: 1
sidebar_custom_props:
  icon: brain
---

Docsio's AI agent builds your entire documentation site automatically by scraping your website or processing uploaded documents. It extracts your brand, writes every page, and delivers a polished site in minutes.

## How it works

Paste your website URL or upload internal documents. The AI agent takes over from there. It maps your site, scrapes your content, extracts your brand identity, writes every documentation page, and runs a full quality audit. The entire process takes 2-5 minutes depending on your website size.

You watch each step happen in real time. The AI shows you exactly what it's doing: extracting brand colors, mapping pages, scraping content, writing documentation, building navigation, and running the final audit.

:::note
The AI only uses real information found on your website or in your uploaded documents. It never fabricates features, invents API endpoints, or makes up content.
:::

## What the AI generates

**Getting started guide**, Installation or setup steps for your product, structured with clear prerequisites and step-by-step instructions.

**Feature documentation**, A page for each major feature explaining what it does, how to use it, and what options are available.

**Integration guides**, Pages documenting how to connect your product with other services.

**API reference**, If your product exposes an API, the AI generates endpoint documentation with parameters and examples.

**Homepage**, A landing page with your product overview, key features, and navigation to all documentation sections.

**Navigation and sidebar**, Complete sidebar structure with categories and pages organized logically.

**Footer**, Footer with working links to all major documentation sections.

Every page is written in Markdown and can be edited manually after generation if you want to refine the content.

## Content quality

The AI uses the Diataxis framework to structure documentation. This framework organizes content into four types:

- **Tutorials**, Step-by-step guides for getting started
- **How-to guides**, Task-focused instructions for specific goals
- **Explanations**, Conceptual information and background
- **Reference**, Technical specifications and API documentation

This structure ensures your documentation is organized in a way that matches how users actually learn and use your product.

## Handling sensitive data

If you upload internal documents (BRDs, PRDs, API specs, architecture diagrams), the AI automatically strips sensitive details before generating customer-facing documentation.

**What gets stripped:**
- API keys and authentication tokens
- Database schemas and internal architecture
- Internal URLs and service names
- Employee names and team information
- Confidential business metrics

Only customer-facing content makes it into your final documentation. You review and approve the proposed structure before anything is built or published.

:::warning
Always review the generated documentation before publishing to ensure no sensitive information was missed. The AI is very good at stripping internal details, but you should do a final check.
:::

## Customization after generation

The generated documentation is a starting point, not a final product. You can:

- **Edit any page** manually by clicking into the editor
- **Add new pages** by creating them in the editor or asking the AI agent
- **Change colors, fonts, and layout** through the AI agent or by editing CSS directly
- **Reorganize navigation** by updating the sidebar structure
- **Add custom components** or embed videos, images, and other media

The AI agent stays with you as an editor. Chat with it to make changes without touching code.

## Data privacy

All processing happens in isolated sandboxes. Your uploaded files are processed and never stored after generation. Your content is never used to train AI models. Complete privacy by design.

## See also

- [Quick start](/docs/getting-started/quickstart), get your first site live in 30 seconds.
- [How it works](/docs/getting-started/how-it-works), the five-phase generation process.
- [AI Editing Agent](/docs/features/ai-agent), make changes after generation.
- [Uploading documents](/docs/guides/uploading-documents), upload internal docs instead of pasting a URL.
