# Luna OpenClaw Setup Guide

## Requirements

- Ubuntu Linux
- Node.js
- Docker
- OpenRouter API key
- Google Cloud VM

## Install OpenClaw

```bash
curl -fsSL https://openclaw.ai/install.sh | bash
```

## Configure OpenClaw

```bash
openclaw configure
```

## Start Gateway

```bash
systemctl --user restart openclaw-gateway
```

## View Logs

```bash
journalctl --user -u openclaw-gateway -f
```

## Run TUI

```bash
openclaw tui
```

## Recommended Free Models

- deepseek/deepseek-chat-v3-0324:free
- qwen/qwen3-32b:free

## Search Provider

Recommended:

- DuckDuckGo Search
