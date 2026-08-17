# Featurebase for Claude

Connect Claude Code to your Featurebase workspace through Featurebase's hosted MCP server.

## What you can do

- Search, summarize, and manage support conversations and tickets.
- Explore customer feedback and recurring themes.
- Look up contacts, companies, and their related activity.
- Work with help center collections and articles.
- Draft and send updates using the context already stored in Featurebase.

## Install

After the plugin is published to the Claude community marketplace:

```text
/plugin marketplace add anthropics/claude-plugins-community
/plugin install featurebase@claude-community
```

For local testing from a clone of this repository:

```bash
claude --plugin-dir .
```

Open `/mcp` inside Claude Code and follow the browser flow to authorize access to your Featurebase workspace. Featurebase uses OAuth; no API key is required.

## Example prompts

- Summarize all currently open support conversations and identify the most urgent ones.
- Find recent customer feedback about a feature and summarize recurring themes.
- Look up a customer company and show its contacts, conversations, and related feedback.
- Draft a reply to a support conversation using the customer and conversation context.
- Find potentially outdated help center articles and suggest improvements.

## Links

- [Featurebase](https://www.featurebase.app)
- [Developer documentation](https://developers.featurebase.app)
- [Privacy policy](https://help.featurebase.app/articles/4744036-privacy-policy)
- [Terms of service](https://help.featurebase.app/en/help/articles/5917992-terms-of-service)
- [Support](https://feedback.featurebase.app/tickets)
