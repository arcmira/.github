# Arcmira: YouTube Transcript Search

[API documentation](https://arcmira.com/docs) · [OpenAPI specification](https://api.arcmira.com/v1/openapi.json) · [Get an API key](https://arcmira.com/developers)

Give your AI the ability to find who said what with timestamps, discover what's being discussed across videos and livestreams, and distinguish organic recommendations from sponsored ad reads.

## Build with Arcmira

| Interface | Start here |
| --- | --- |
| HTTP API | [Search, transcripts and monitors](https://arcmira.com/docs) |
| TypeScript SDK and CLI | [arcmira/arcmira](https://github.com/arcmira/arcmira) |
| CLI with Homebrew | [Install from Arcmira's tap](https://github.com/arcmira/integrations/tree/master/Formula) |
| Python SDK | [arcmira/python](https://github.com/arcmira/python) |
| MCP and agent skills | [arcmira/mcp](https://github.com/arcmira/mcp) |
| LangChain and LangGraph for Python | [PyPI package](https://pypi.org/project/langchain-arcmira/) · [Quick start](https://github.com/arcmira/integrations/tree/master/packages/langchain-python) |
| Agent and workflow integrations | [Packages and previews](https://github.com/arcmira/integrations) |

## Connect your AI

Add the hosted MCP server to Claude Code:

```sh
claude mcp add --transport http arcmira https://mcp.arcmira.com/mcp
```

For ChatGPT, Cursor, Codex and other clients, use the [setup guide](https://arcmira.com/agent-setup). Try this prompt:

```text
Find recent discussions of open-source AI on YouTube. Show the relevant quotes, speakers where identified, and timestamped source links. Note any coverage gaps.
```

Paid reads, Premium transcripts included, use credits from your plan, then your on-demand budget. Monitor changes need write access. See the [MCP reference](https://arcmira.com/docs/mcp-server).

Arcmira is an SF-based AI company and the search engine for the spoken web.
