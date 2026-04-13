# Customer Support AI MCP Server

**Support Automation Intelligence**

Built by [MEOK AI Labs](https://meok.ai)

---

An MCP server for customer support teams. Classify tickets by category and priority with SLA routing, draft professional responses, analyze customer sentiment trends, detect escalation triggers, and generate FAQ entries from resolved ticket patterns.

## Tools

| Tool | Description |
|------|-------------|
| `classify_ticket` | Classify tickets by category, priority, and route to correct team with SLA |
| `draft_response` | Draft professional support responses with customizable tone |
| `analyze_sentiment` | Analyze customer message sentiment with trajectory tracking |
| `detect_escalation` | Detect escalation triggers including legal threats and frustration |
| `generate_faq` | Generate FAQ entries from common support ticket patterns |

## Quick Start

```bash
pip install customer-support-ai-mcp
```

### Claude Desktop

```json
{
  "mcpServers": {
    "customer-support-ai": {
      "command": "python",
      "args": ["-m", "server"],
      "cwd": "/path/to/customer-support-ai-mcp"
    }
  }
}
```

### Direct Usage

```bash
python server.py
```

## Rate Limits

| Tier | Requests/Hour |
|------|--------------|
| Free | 60 |
| Pro | 5,000 |

## License

MIT - see [LICENSE](LICENSE)

---

*Part of the MEOK AI Labs MCP Marketplace*
