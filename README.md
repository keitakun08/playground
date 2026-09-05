# Playground

Dev container setup for building and testing with an agentic coding CLI (OpenCode) plus browser-based agent testing (agent-browser).

## Getting started

1. Open this folder in VS Code.
2. Install the **Dev Containers** extension if you haven't already.
3. Cmd+Shift+P → **Dev Containers: Reopen in Container**.
4. VS Code builds the container and runs `.devcontainer/setup.sh`, which installs:
   - `opencode-ai` and `agent-browser` (via npm)
   - Chromium (for `agent-browser` to drive)
   - The `agent-browser` skill for OpenCode

## What's inside

- `.devcontainer/devcontainer.json` — container image, env vars, and the command that runs setup
- `.devcontainer/setup.sh` — installs OpenCode, agent-browser, and Chromium
