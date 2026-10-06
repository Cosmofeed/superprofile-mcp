# SuperProfile MCP server

The official, hosted [Model Context Protocol](https://modelcontextprotocol.io) server for [SuperProfile](https://superprofile.bio). Connect Claude, ChatGPT, Cursor, Codex, Gemini or any MCP client, then run your creator store and Instagram DM automation in plain language.

```
https://mcp.superprofile.bio/mcp
```

- **Transport:** Streamable HTTP (remote). Nothing to install.
- **Auth:** OAuth with dynamic client registration and PKCE. You sign in to SuperProfile and choose what the assistant may do.
- **Built and run by SuperProfile.** No Zapier or other third party sits in between.
- **Available to every SuperProfile creator.**

This repository holds the public listing metadata (`server.json`) for MCP directories and the official MCP Registry. The server itself is hosted by SuperProfile. There is no code to run locally.

## What you can do

- **Instagram and Facebook Messenger DM automation:**
  - comment-to-DM on Reels and posts
  - Story replies and Live comments
  - follow requests before the link
  - email capture into Kit, Mailchimp or Klaviyo
  - follow-ups
- **Products:** digital products and payment pages, online courses, webinars and events, 1:1 sessions and bookings, lead magnets, locked content, paid Telegram communities.
- **Reports:** analytics, sales and automation runs.

Example prompts:

- "Create a draft automation for my latest Reel that sends my guide when someone comments GUIDE."
- "Turn these five videos into a course with two modules and a completion certificate."
- "Set up a Zoom workshop next Sunday at 11 am with 50 tickets."

## Connect

| Assistant | Guide |
|---|---|
| Claude | [superprofile.bio/mcp/claude](https://superprofile.bio/mcp/claude) (also in [Claude's connector directory](https://claude.ai/directory/superprofile)) |
| ChatGPT | [superprofile.bio/mcp/chatgpt](https://superprofile.bio/mcp/chatgpt) |
| Cursor | [superprofile.bio/mcp/cursor](https://superprofile.bio/mcp/cursor) |
| Claude Code | [superprofile.bio/mcp/claude-code](https://superprofile.bio/mcp/claude-code) |
| OpenAI Codex | [superprofile.bio/mcp/codex](https://superprofile.bio/mcp/codex) |
| Gemini | [superprofile.bio/mcp/gemini](https://superprofile.bio/mcp/gemini) |
| VS Code (GitHub Copilot) | [superprofile.bio/mcp/vscode](https://superprofile.bio/mcp/vscode) |
| Windsurf, Perplexity, Notion, Muse | [superprofile.bio/mcp](https://superprofile.bio/mcp) |

Any other client that supports remote MCP servers with OAuth works too: add the URL above.

## You stay in control

- Preparing a change does not publish it: the assistant shows you a draft first.
- Editing, publishing, deleting, customer information and email activation are separate permissions.
- You can review or revoke access any time under **Connected agents** in your SuperProfile dashboard.
- Product-only access needs no Instagram account or Messenger Page.
- Instagram automations run on Meta's official messaging API, using the account you connect with Meta login. Meta's messaging rules apply.

## Links

- Product page: https://superprofile.bio/mcp
- Instagram DM automation through MCP: https://superprofile.bio/mcp/instagram-auto-dm
- FAQ: https://superprofile.bio/mcp/faq
- Developer reference: https://mcp.superprofile.bio/docs

## Security

To report a vulnerability, email developer@cosmofeed.com. Please do not open public reports.
