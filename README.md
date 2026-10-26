# Pilot5 MCP server

Pilot5 runs a panel of AI models from different providers on a decision and returns one recommendation, with its sources and the strongest counter-argument.

This repository holds connection details only. Pilot5 is a hosted service; there is nothing to install or run.

- **Server URL:** `https://mcp.pilot5.ai/mcp` (Streamable HTTP)
- **Sign-in:** OAuth 2.1 with Dynamic Client Registration. Your client registers itself and opens the Pilot5 sign-in; there is no key to paste.
- **Account:** sign up at [pilot5.ai](https://pilot5.ai). Runs use credits from your Pilot5 account.
- **MCP Registry name:** `ai.pilot5/pilot5`

## Modes

- **The Expert:** one model, 1-2 minutes.
- **The A-Team:** five models, 10-20 minutes. It can stop once after Round 1 to ask you one detail.
- **The Dream Team:** five models. It pauses after every round so you can steer.

Before The A-Team or The Dream Team starts, you see the question exactly as the panel will receive it. The run starts only when you confirm.

## Connect

Step-by-step instructions for Claude, ChatGPT, VS Code, Perplexity and Le Chat: [pilot5.ai/docs/mcp](https://pilot5.ai/docs/mcp).

## Support

[support@pilot5.ai](mailto:support@pilot5.ai) · [Privacy](https://pilot5.ai/privacy) · [Terms](https://pilot5.ai/terms)

Pilot5 is operated by Pilot5 Inc.
