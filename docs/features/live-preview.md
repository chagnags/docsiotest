---
title: Live Preview
sidebar_position: 3
sidebar_custom_props:
  icon: eye
---

Every change you make renders instantly in a live preview. No waiting for builds, no refreshing tabs. What you see is exactly what your readers will get when you publish.

## How it works

Your documentation site runs in an isolated sandbox with a real development server. When you make a change, the preview updates immediately through hot-reload. There's no build step, no compilation delay, just instant feedback.

The preview is a fully interactive documentation site. You can click links, open the sidebar, navigate between pages, and test dark mode exactly as your readers will experience it.

:::note
The live preview is completely isolated from your published site. Changes in the preview don't affect your live documentation until you click Publish.
:::

## Real-time updates

When you use the AI agent to make changes, the preview updates in real time as the agent works. You see each file being read and each change being applied. By the time the agent finishes, the preview is already showing the result.

```
Working...
Reading custom.css
Updated navbar colors
Added dark mode toggle
Done. Preview is live.
```

If you edit pages manually in the editor, the preview updates instantly when you save.

## Testing your site

The live preview lets you test your documentation before publishing:

**Navigate between pages**, Click sidebar links and verify that navigation works correctly.

**Test dark mode**, Toggle between light and dark themes to ensure both look good.

**Check mobile layout**, Switch to mobile viewport to verify responsive design on smaller screens.

**Verify links**, Click internal links to make sure they point to the right pages.

**Review code blocks**, Check that code examples are properly formatted and copy-pasteable.

**Test search**, Use the search bar to verify that pages are indexed and searchable.

## Mobile responsiveness

Click the mobile icon in the preview toolbar to switch between desktop and mobile viewports. This lets you verify that your documentation looks good on phones and tablets before publishing.

The preview shows exactly how your site will render on different screen sizes. If something looks wrong on mobile, you can ask the AI agent to fix it before publishing.

:::tip
Test your documentation on both light and dark mode, and on both desktop and mobile. This ensures your readers have a good experience regardless of their device or theme preference.
:::

## Isolated sandbox

Each documentation project runs in its own isolated sandbox. Your changes don't affect other projects or users. The sandbox is completely separate from your published site.

When you publish, your documentation is built and deployed from the sandbox to a live URL. The sandbox stays available for further editing.

## See also

- [Quick start](/docs/getting-started/quickstart), get your first site live in 30 seconds.
- [AI Editing Agent](/docs/features/ai-agent), make changes without code.
- [Publishing](/docs/features/publishing), deploy your site with one click.
