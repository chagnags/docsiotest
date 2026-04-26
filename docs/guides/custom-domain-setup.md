---
title: Custom domain setup
sidebar_position: 3
sidebar_custom_props:
  icon: link-simple
---

Connect your own domain like `docs.acme.com` to your Docsio documentation site. This guide walks through the DNS setup process step by step.

## Before you start

- You must own the domain or have access to manage its DNS records
- Your documentation site must be published at least once
- You need access to your domain registrar's DNS settings

Common registrars include GoDaddy, Namecheap, Route 53, Cloudflare, and Google Domains. The process is similar for all of them.

## Step 1: Add the domain in Docsio

1. Open your project in Docsio.
2. Click **Settings** in the top right.
3. Click **Domains** in the left sidebar.
4. Click **Add custom domain**.
5. Enter your domain name (e.g., `docs.acme.com`).
6. Click **Add domain**.

Docsio generates a CNAME target for your domain. Copy this value, you'll need it in the next step.

```
docs.acme.com → cname.docsio.co
```

:::note
The CNAME target is unique to your project. Don't share it with others or use it for different domains.
:::

## Step 2: Update your DNS

Log in to your domain registrar and find the DNS settings. You need to add a CNAME record.

**For subdomains like `docs.acme.com`:**

| Field | Value |
| --- | --- |
| Type | `CNAME` |
| Name | `docs` |
| Target | the value from Docsio |
| TTL | `3600` (or "auto") |

**Example for GoDaddy:**
1. Go to your domain settings
2. Click **DNS** or **Manage DNS**
3. Click **Add** to create a new record
4. Select `CNAME` as the record type
5. Enter `docs` as the name
6. Enter the CNAME target from Docsio
7. Click **Save**

**Example for Cloudflare:**
1. Go to your domain's DNS settings
2. Click **Add record**
3. Select `CNAME` as the record type
4. Enter `docs` as the name
5. Enter the CNAME target from Docsio
6. Click **Save**

The exact steps vary by registrar, but the process is always the same: create a CNAME record with the name and target from Docsio.

:::warning
Make sure you're adding a CNAME record, not an A record or other record type. CNAME is required for Docsio to work.
:::

## Step 3: Wait for propagation

DNS changes take time to propagate across the internet. This usually takes 5-15 minutes but can take up to 24 hours.

During propagation, your site remains accessible at `yourproject.docs.docsio.co`. You can start using your custom domain as soon as it propagates.

**Check propagation:**
- Use `dig docs.acme.com` from your terminal
- Visit [whatsmydns.net](https://whatsmydns.net) and enter your domain
- Both tools show you the CNAME record status across different regions

## Step 4: Verify the connection

Once DNS propagates, Docsio automatically provisions an SSL certificate for your custom domain.

1. Go back to **Settings → Domains** in Docsio.
2. Look for your domain in the list.
3. You should see a green **Connected** badge.

Your custom domain is now live with HTTPS enabled. Your documentation is accessible at `docs.acme.com`.

:::tip
Test your custom domain by visiting it in your browser. You should see your documentation site with a green lock icon in the address bar (HTTPS).
:::

## Troubleshooting

**Domain not connecting after 30 minutes?**

1. Double-check your CNAME record at your DNS provider
2. Make sure the name and target match exactly what Docsio shows
3. Verify you created a CNAME record, not an A record
4. Try deleting and re-adding the domain in Docsio to retry

**SSL certificate not provisioning?**

1. Wait 30 minutes after DNS propagates
2. The certificate should provision automatically
3. If it still fails, delete and re-add the domain to retry

**Still having issues?**

Check that:
- The CNAME record exists at your DNS provider
- The name matches your subdomain (e.g., `docs`)
- The target matches the value from Docsio exactly
- You're using a CNAME record, not an A record

## See also

- [Custom Domains](/docs/features/custom-domains), feature overview.
- [Publishing](/docs/features/publishing), deploy your site with one click.
