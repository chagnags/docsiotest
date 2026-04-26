---
title: Editing with the AI Agent
sidebar_position: 2
sidebar_custom_props:
  icon: magic-wand
---

The AI agent makes editing your documentation easy. Describe what you want to change in plain English and the agent handles the implementation. No code required.

## Open the editor

1. Go to your project in Docsio.
2. Click the **Editor** tab.
3. You'll see your documentation on the left and the live preview on the right.
4. At the bottom, click **Ask the agent** to start chatting.

## Make a change

Describe what you want to change in plain English. Be specific about what you want:

**Good:** "Change the primary color to teal and update all links to match"
**Better:** "Change the primary color from brown to teal (#008080) and update all links and buttons to use the new color"

**Good:** "Add a new page called Troubleshooting"
**Better:** "Create a new page called 'Troubleshooting' in the Guides section with common issues and solutions"

The more specific you are, the better the agent understands what you want.

## Watch it work

As the agent works, you see each step happen in real time:

```
Working...
Reading custom.css
Updated navbar colors
Added dark mode toggle
Done. Navbar and links now use your brand color. 
Dark mode toggle added to the top right. Preview is live.
```

The live preview updates as the agent makes changes. By the time it finishes, you can already see the result.

## Common edits

**Change a color:**
> "Change the primary color to blue"

The agent updates your CSS and applies the new color throughout light and dark mode.

**Add a page:**
> "Create a new page called 'API Reference' with endpoint documentation"

The agent creates the page, adds it to the sidebar, and updates navigation.

**Edit content:**
> "Rewrite the Quick Start page to include Docker setup instructions"

The agent reads the current page, rewrites it with the new content, and updates the preview.

**Reorganize navigation:**
> "Move the Guides section to the top of the sidebar"

The agent updates the sidebar structure and navigation order.

**Embed media:**
> "Add a demo video to the homepage"

The agent adds a responsive video embed to the page.

**Update branding:**
> "Change the logo to the new one I uploaded"

The agent updates your logo throughout the site.

## Edit limits

The free plan includes 20 AI agent edits per month. Each change counts as one edit.

If you need unlimited edits, upgrade to Pro for $60/month per site.

:::note
You can also edit pages manually in the editor without using the AI agent. Manual edits don't count against your edit limit.
:::

## Manual editing

If you prefer to edit pages directly without using the AI agent:

1. Click on a page in the sidebar.
2. Click **Edit** to open the page editor.
3. Make your changes directly in the Markdown editor.
4. Click **Save** to update the page.

Manual edits appear in the live preview instantly. This is a good option if you want to make small changes without using an AI edit.

## Tips for better results

**Be specific**, Describe exactly what you want, not just "make it better".

**Use product terminology**, Use the same terms your product uses for features and concepts.

**Ask for one thing at a time**, Instead of "redesign the whole site", ask for specific changes like "change the primary color" or "add a new page".

**Review the result**, Always check the live preview to make sure the change is what you wanted.

**Iterate**, If the result isn't quite right, ask the agent to adjust it. "Make the heading larger" or "use a different color".

## See also

- [AI Editing Agent](/docs/features/ai-agent), detailed feature overview.
- [Live Preview](/docs/features/live-preview), see changes instantly.
- [Quick start](/docs/getting-started/quickstart), get your first site live in 30 seconds.
