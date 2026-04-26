---
title: Common questions
sidebar_position: 1
sidebar_custom_props:
  icon: chat-circle-text
---

Answers to frequently asked questions about Docsio, how it works, and what you can do with it.

## How does Docsio generate documentation from my website?

Docsio scrapes your website, extracts your product information, features, and brand identity (colors, logo, fonts), then uses AI to generate structured documentation following best practices. The entire process takes under 5 minutes.

The AI reads your website, identifies product pages and feature information, and writes documentation pages using only real content from your site. It never fabricates features or invents API endpoints.

## Can I edit the generated documentation?

Yes. Every generated page is fully editable. You get an AI agent that can make any change you describe, from rewriting content to changing colors to adding new pages. You also get a live preview that updates instantly as you make changes.

You can also edit pages manually in the editor if you prefer to make changes directly without using the AI agent.

## What kind of sites can I create documentation for?

Any product with a website. SaaS tools, developer APIs, mobile apps, open source projects, and agencies all use Docsio to ship documentation faster.

If your product only has a marketing website with no product information, you can upload internal documents instead. Docsio transforms BRDs, PRDs, API specs, and other documents into customer-facing documentation.

## Where are my documentation sites hosted?

Every site is hosted with SSL included on a Docsio subdomain: `yourproject.docs.docsio.co`. Pro users can connect their own custom domain like `docs.yourcompany.com`.

Your documentation is served from a global CDN for fast performance worldwide.

## Is Docsio free?

Yes. The free plan includes one documentation site with 20 AI agent edits per month, custom domains, brand extraction, live preview, and hosted publishing. No credit card required, no time limit.

Upgrade to Pro ($60/month per site) for unlimited AI usage, doc versioning, password protection, full-text search, AI chat widget, team members, and branding removal.

## How is Docsio different from GitBook or Mintlify?

Docsio generates your docs automatically from your existing website or uploaded documents. You don't start from a blank page. It also extracts your brand identity so your docs match your product from day one. And it's free to start, with no complex setup or deployment pipeline.

GitBook and Mintlify require you to write documentation from scratch or migrate existing docs manually. Docsio automates the entire process.

## What if my website is just a marketing site?

No problem. You can upload internal documents, BRDs, PRDs, API specs, or any files directly. Docsio's AI transforms them into customer-facing documentation, automatically stripping internal details like architecture, credentials, and team information. You review and approve the proposed structure before anything is built.

See [Uploading documents](/docs/guides/uploading-documents) for details.

## Is my data safe? What about sensitive documents?

Every user gets an isolated sandbox environment. We have a strict zero data retention policy, your files are processed and never stored. We never train AI models on your content.

When you upload internal specs, the AI automatically strips sensitive details (API keys, database schemas, internal URLs, employee info) and only produces customer-facing content. You approve everything before it goes live.

## How many pages can my documentation site have?

There's no limit. Docsio can generate documentation for products with 5 pages or 500 pages. The AI scales to handle websites of any size.

## Can I use Docsio for internal documentation?

Yes. You can create private documentation sites for internal use. The free plan includes custom domains, so you can host internal docs at `internal-docs.acme.com` if you want.

Pro plan includes password protection for additional security.

## Can I version my documentation?

Yes, but only on the Pro plan. Pro includes doc versioning so you can maintain multiple versions of your documentation side by side. Users get a dropdown to switch between versions.

The free plan doesn't include versioning.

## How do I add a custom domain?

See [Custom domain setup](/docs/guides/custom-domain-setup) for step-by-step instructions. It takes about 5 minutes and requires adding a single CNAME record at your DNS provider.

## Can I embed videos or other media?

Yes. You can ask the AI agent to embed videos, images, diagrams, and other media on your pages. The agent handles the embedding and responsive layout.

You can also edit pages manually and add media directly using Markdown.

## How do I make my documentation searchable?

Docsio includes full-text search on every plan. Your readers can search your documentation using the search bar at the top of every page.

Search is powered by Algolia and works instantly across all your pages.

## Can I customize the look and feel?

Completely. Docsio starts by matching your existing brand (colors, logo, fonts) but you can change anything. Edit CSS directly, swap colors, change fonts, adjust layouts, add custom components. The AI agent makes complex design changes as easy as describing them.

## How do I republish after making changes?

1. Review your changes in the live preview
2. Click **Publish**
3. Your site updates in seconds

Your URL stays the same and the site updates in place.

## See also

- [Quick start](/docs/getting-started/quickstart), get your first site live in 30 seconds.
- [Introduction](/docs/getting-started/introduction), what Docsio is and who should use it.
- [Features](/docs/features/ai-generation), explore all Docsio capabilities.
