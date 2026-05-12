# Luna AI Agent Architecture

## High-Level Workflow

User → OpenClaw Agent → Gateway → OpenRouter → AI Response

## Infrastructure

- Google Cloud VM
- Ubuntu 22.04 LTS
- OpenClaw Runtime
- OpenRouter Integration
- Docker Support
- VS Code Remote SSH

## Components

### Gateway
Handles:
- agent orchestration
- sessions
- memory
- hooks
- skills

### AI Provider
External inference handled using OpenRouter.

### Runtime
Persistent 24/7 runtime using systemd.

## Security

- Loopback binding
- Token authentication
- SSH security
- User-level isolation
