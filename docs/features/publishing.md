---
title: Publishing
sidebar_position: 5
sidebar_custom_props:
  icon: upload-simple
---

Deploy your documentation site with a single button. Automatic SSL provisioning, global CDN delivery, and a shareable URL in seconds. No pipelines, no YAML, no DevOps required.

## How to publish

1. Open the editor and review your documentation in the live preview.
2. When you're ready, click the **Publish** button.
3. Docsio builds your site, optimizes assets, and deploys to the CDN.
4. Your site goes live at `yourproject.docs.docsio.co` with automatic SSL.

The entire deployment process takes 5-10 seconds. Your documentation is live and ready to share immediately.

:::note
You must have reviewed your site in the live preview at least once before publishing. This ensures you're happy with the result before it goes live.
:::

## What happens during publishing

When you click Publish, Docsio:

1. **Builds your site**, Compiles all pages, assets, and configuration
2. **Optimizes assets**, Minifies CSS and JavaScript, optimizes images
3. **Deploys to CDN**, Uploads your site to a global content delivery network
4. **Provisions SSL**, Generates and installs an SSL certificate
5. **Activates your URL**, Your site is live and accessible

```
Building documentation site... 2s
Optimizing assets... 1s
Deploying to CDN... 3s
Provisioning SSL certificate... 2s
Deployment complete
Live at: docs.acme.com
```

## Your live URL

Every documentation site gets a live URL on the Docsio domain:

```
https://yourproject.docs.docsio.co
```

Replace `yourproject` with your project name. This URL is live immediately after publishing and can be shared with your team, customers, or the public.

:::tip
Share your live URL with your team right away. You can make edits and republish at any time. Your URL stays the same and the site updates in place.
:::

## Republishing after edits

If you make changes to your documentation after publishing:

1. Review the changes in the live preview
2. Click **Publish** again
3. Your site updates in seconds

Your URL stays the same. The live site is updated in place. Readers always see the latest version.

## Automatic SSL

Every documentation site includes HTTPS with automatic SSL provisioning. Your readers always get a secure connection.

SSL certificates are provisioned automatically and renewed before they expire. You never need to manually renew or rotate certificates.

## Custom domains

By default, your site is published to `yourproject.docs.docsio.co`. If you want your documentation at your own domain like `docs.acme.com`, you can connect a custom domain.

See [Custom Domains](/docs/features/custom-domains) for setup instructions.

## Performance

Your documentation is served from a global CDN. Pages load fast for readers around the world, regardless of their location.

Assets are optimized and cached for maximum performance. Your documentation site is fast and responsive.

## See also

- [Quick start](/docs/getting-started/quickstart), get your first site live in 30 seconds.
- [Custom Domains](/docs/features/custom-domains), point your own domain at your documentation.
- [Live Preview](/docs/features/live-preview), test your site before publishing.
