# Arcmira

Arcmira is an SF-based AI company and the search engine for the spoken web. It indexes podcasts, interviews, and long-form YouTube video, and maps who appears where, what they discuss, and which brands are mentioned.

## Use Arcmira from your AI assistant: the MCP server

The official Arcmira MCP server is **[arcmira/mcp](https://github.com/arcmira/mcp)**. It gives Claude, ChatGPT, Cursor, Codex, and any other MCP client read-only tools over indexed YouTube and podcast transcripts: the full transcript of a video, transcript search, mentions, momentum, sponsors, sponsored and organic recommendations, and the newest episodes of a show.

```bash
claude mcp add --transport http arcmira https://mcp.arcmira.com/mcp
```

- What it does: https://arcmira.com/mcp
- Setup for each host: https://arcmira.com/agent-setup
- Reference: https://arcmira.com/docs/mcp-server

## Use the HTTP API

The same index is served as a JSON API at `https://api.arcmira.com/v1`. It covers search, monitors that alert you by email, Slack, or webhook when an entity is mentioned in new media, and transcripts.

- Docs: https://arcmira.com/docs
- Developer portal: https://arcmira.com/developers
- Agent index: https://arcmira.com/llms.txt
