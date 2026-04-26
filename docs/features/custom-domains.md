---
title: Custom Domains
sidebar_position: 6
sidebar_custom_props:
  icon: globe
---

Point your own domain at your documentation site with a simple CNAME record. Automatic SSL provisioning and renewal included. No server configuration needed.

## Prerequisites

- A domain you control with access to its DNS provider
- Your documentation site must be published at least once

## Add the domain

1. Open **Settings → Domains** in the editor.
2. Click **Add custom domain**.
3. Enter your full domain name (e.g., `docs.acme.com`).
4. Copy the CNAME target shown in the dialog.

The CNAME target is a unique value that routes traffic from your domain to your Docsio documentation site.

:::note
Subdomains like `docs.acme.com` are recommended. Apex domains (`acme.com`) work but cannot share DNS with other services.
:::

## Configure DNS

Add a CNAME record at your DNS provider pointing to the target from the previous step.

| Field | Value |
| --- | --- |
| Type | `CNAME` |
| Name | `docs` (or your chosen subdomain) |
| Target | the value from the previous step |
| TTL | `3600` (or "auto") |

Here's an example:

```
Type:   CNAME
Name:   docs
Value:  cname.docsio.co
TTL:    3600
```

DNS propagation usually completes in 5-15 minutes but can take up to 24 hours. During propagation, your site remains accessible at `yourproject.docs.docsio.co`.

:::tip
Use `dig docs.acme.com` from your terminal or visit [whatsmydns.net](https://whatsmydns.net) to watch the CNAME record propagate across regions.
:::

## SSL certificate

Once your DNS CNAME record is in place and propagates, Docsio automatically provisions an SSL certificate for your custom domain. This usually happens within 5-10 minutes.

You'll see a green **Connected** badge in **Settings → Domains** when the certificate is active. Your custom domain now has HTTPS enabled.

:::warning
If the certificate fails to provision after 30 minutes, the DNS is usually misconfigured. Double-check your CNAME record at your DNS provider. If it looks correct, delete and re-add the domain from Settings to retry.
:::

## Automatic renewal

SSL certificates are renewed automatically before they expire. You never need to manually renew or rotate certificates. It just works.

## Multiple domains

You can connect multiple custom domains to the same documentation site. Each domain points to the same site content.

To add another domain, repeat the steps above in **Settings → Domains**.

## Removing a domain

To remove a custom domain:

1. Open **Settings → Domains**.
2. Click the **Remove** button next to the domain.
3. The domain is disconnected immediately.

Your site remains accessible at `yourproject.docs.docsio.co` and any other connected custom domains.

## See also

- [Publishing](/docs/features/publishing), deploy your site with one click.
- [Quick start](/docs/getting-started/quickstart), get your first site live in 30 seconds.
