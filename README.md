# Lindo AI — Codex Plugin

Create websites, pages, and blog posts with AI. Manage clients, credits, and domains — all through conversation.

## Install

### From a marketplace (when available)

```
codex
/plugins
# Search for "Lindo AI"
```

### From GitHub

```bash
codex plugin marketplace add lindoai/codex-plugin
```

### Local install

```bash
# Clone the repo
git clone https://github.com/lindoai/codex-plugin.git

# Add to your personal marketplace (~/.agents/plugins/marketplace.json):
{
  "name": "local-plugins",
  "interface": { "displayName": "My Plugins" },
  "plugins": [{
    "name": "lindo-ai",
    "source": { "source": "local", "path": "./path/to/codex-plugin" },
    "policy": { "installation": "AVAILABLE", "authentication": "ON_INSTALL" },
    "category": "Productivity"
  }]
}
```

## Setup

Set your Lindo AI API key:

```bash
export LINDO_API_KEY=lindo_sk_live_...
```

Or the plugin will open a browser login flow on first use.

Get an API key from your workspace settings at [app.lindo.ai](https://app.lindo.ai).

## What you can do

- **Create websites** — "Build a portfolio website for a photographer"
- **Add pages** — "Add a pricing page to my website"
- **Write blog posts** — "Write a blog post about SEO tips"
- **Manage clients** — "Create a client for Acme Corp"
- **Allocate credits** — "Give 500 credits to my client"
- **Custom domains** — "Add example.com to my website"
- **Analytics** — "Show me traffic for my website"

## Skills

| Skill | Description |
|-------|-------------|
| create-website | Create a new website with AI |
| create-page | Add a page to an existing website |
| create-blog | Generate a blog post with AI |
| manage-clients | Create, list, assign, and manage clients |
| manage-websites | View, update, and configure websites |
| manage-content | Publish, edit, and manage pages and blogs |

## Requirements

- [Lindo AI](https://lindo.ai) account with Business or Whitelabel plan
- Node.js 18+

## Links

- [Lindo AI](https://lindo.ai)
- [Documentation](https://lindo.ai/docs)
- [API Reference](https://api.lindo.ai/docs)

## License

MIT
