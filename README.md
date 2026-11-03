# Baylani for Cursor

Baylani is fintech for grants and restricted funds: it connects to your bank, QuickBooks, or Xero and tracks every dollar against what the funding is for, what it requires, and what needs to happen next.

This plugin connects Cursor to Baylani's remote MCP server so the agent can read your Baylani workspace.

> **Early Access:** the Baylani MCP server is in Early Access. Tools and behavior may change.

## Tools (read-only)

| Tool | What it does |
| --- | --- |
| `get_workspace` | Your Baylani workspace overview |
| `search_opportunities` | Search funding opportunities |
| `list_applications` | List your grant applications |
| `get_application` | Details for one application |
| `list_requirements` | Requirements attached to your funding |
| `list_awards_and_deadlines` | Awards and upcoming deadlines |
| `search_institutional_memory` | Search your organization's saved knowledge |

All tools are read-only; the plugin cannot change data in Baylani.

## Connect

1. Install the plugin in Cursor.
2. When Cursor prompts for the `baylani` MCP server, sign in with your Baylani account (OAuth). No API keys or tokens are stored in this plugin.

You need a Baylani account to use the tools.

## Support

https://baylani.com
