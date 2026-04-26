---
title: Uploading documents
sidebar_position: 1
sidebar_custom_props:
  icon: file-text
---

If your product doesn't have a public website or you want to build documentation from internal specs, you can upload documents directly to Docsio. The AI transforms them into customer-facing documentation automatically.

## When to upload documents

Upload documents instead of pasting a URL if:

- Your product only has a marketing website with no product information
- You have internal specifications (BRDs, PRDs, API specs) you want to turn into docs
- You want to build documentation from design documents or technical guides
- You have existing documentation you want to migrate to Docsio

## Supported file types

Docsio accepts:

- **Markdown** (`.md`), Existing documentation in Markdown format
- **PDF** (`.pdf`), Specification documents, guides, and technical papers
- **Text** (`.txt`), Plain text documents and specifications
- **Word** (`.docx`), Microsoft Word documents

## How to upload

1. Go to [docsio.co](https://docsio.co) and click **Get Started Free**.
2. Instead of pasting a URL, click **Upload documents**.
3. Select one or more files from your computer.
4. Click **Upload** and wait for the files to process.

Docsio reads your documents and extracts the relevant information. The AI then generates your documentation site.

:::note
You can upload multiple files at once. Docsio processes them together and creates a unified documentation site.
:::

## Document preparation

To get the best results from document uploads:

**Use clear structure**, Organize your documents with clear headings and sections. The AI uses this structure to organize your documentation.

**Include examples**, Add code examples, screenshots, and diagrams. The AI includes these in your documentation.

**Be specific**, Use specific product names, feature names, and terminology. Avoid generic language.

**Remove internal details**, The AI automatically strips sensitive information, but you should remove obvious internal details before uploading.

## Sensitive data handling

When you upload internal documents, the AI automatically strips sensitive details before generating customer-facing documentation.

**What gets stripped:**
- API keys and authentication tokens
- Database schemas and internal architecture
- Internal URLs and service names
- Employee names and team information
- Confidential business metrics

Only customer-facing content makes it into your final documentation.

:::warning
Always review the generated documentation before publishing to ensure no sensitive information was missed. The AI is very good at stripping internal details, but you should do a final check.
:::

## Brand configuration

When you upload documents, you won't have brand extraction from a website. Instead:

1. After generation, open **Settings → Appearance**.
2. Upload your logo and set your brand colors manually.
3. Choose your primary and secondary colors.
4. Set your preferred theme (light or dark).

The AI agent can also help you customize your brand. Just ask it to change colors or upload a logo.

## After upload

Once your documents are uploaded and processed:

1. Review the generated documentation in the live preview
2. Make any changes using the AI agent
3. Publish your site with one click

The workflow is the same as pasting a URL. The only difference is that your brand is configured manually instead of extracted automatically.

## See also

- [Quick start](/docs/getting-started/quickstart), get your first site live in 30 seconds.
- [AI Documentation Generation](/docs/features/ai-generation), how the AI generates your docs.
- [Brand Extraction](/docs/features/brand-extraction), customize your brand colors and logo.
