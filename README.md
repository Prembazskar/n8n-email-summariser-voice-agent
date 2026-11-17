# n8n AI Email Summariser and Voice AI Agent

Two AI workflows for n8n.

> Part of my Gen AI course practice work (Week 4, Day 1).

## Tech stack

- n8n
- OpenAI
- Gmail
- Telegram
- SerpAPI

## Features

- `workflows/ai-powered-unread-email-summariser.json` - fetches unread Gmail messages, summarises each with an AI agent, and emails a digest
- `workflows/voice-ai-agent.json` - Telegram bot that accepts text or voice (speech-to-text), uses an AI agent with memory, web search, Gmail and calculator tools, and replies with text or speech

## Getting started

1. Clone the repository:
   ```bash
   git clone https://github.com/Prembazskar/n8n-email-summariser-voice-agent.git
   cd n8n-email-summariser-voice-agent
   ```
2. In n8n choose Import from File and select a workflow, then connect your own credentials (Gmail, OpenAI, Telegram, SerpAPI).

## License

MIT, see [LICENSE](LICENSE).
