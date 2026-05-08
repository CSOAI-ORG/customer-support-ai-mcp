<div align="center">

# Customer Support Ai MCP

**Customer Support AI MCP Server - Support Automation Intelligence**

[![PyPI](https://img.shields.io/pypi/v/meok-customer-support-ai-mcp)](https://pypi.org/project/meok-customer-support-ai-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-MCP_Server-purple)](https://meok.ai)

</div>

## Overview

Customer Support AI MCP Server - Support Automation Intelligence
Built by MEOK AI Labs | https://meok.ai

Ticket classification, response drafting, sentiment analysis,
escalation detection, and FAQ generation.

## Tools

| Tool | Description |
|------|-------------|
| `classify_ticket` | Classify a support ticket by category, priority, and routing. |
| `draft_response` | Draft a customer support response based on ticket category. |
| `analyze_sentiment` | Analyze customer message sentiment to gauge satisfaction. |
| `detect_escalation` | Detect if a support ticket needs escalation to management. |
| `generate_faq` | Generate FAQ entries from common support ticket patterns. |

## Installation

```bash
pip install meok-customer-support-ai-mcp
```

## Usage with Claude Desktop

Add to your Claude Desktop MCP config (`claude_desktop_config.json`):

```json
{
  "mcpServers": {
    "customer-support-ai": {
      "command": "python",
      "args": ["-m", "meok_customer_support_ai_mcp.server"]
    }
  }
}
```

## Usage with FastMCP

```python
from mcp.server.fastmcp import FastMCP

# This server exposes 5 tool(s) via MCP
# See server.py for full implementation
```

## License

MIT © [MEOK AI Labs](https://meok.ai)
