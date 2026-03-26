---
name: agent-browser
description: Use agent-browser CLI to control a remote or local Chrome instance via CDP. Provides AI-friendly snapshots with @ref handles for precise interaction. Use when standard fetch or playwright tools are insufficient for complex UI automation.
---

# Agent Browser Skill

This skill leverages the `agent-browser` Rust CLI to interact with the Zeabur-hosted headless browser.

## Configuration

- **Remote CDP Host**: `openclaw-sandbox-browser.zeabur.internal`
- **Port**: `9222`
- **Default Session**: Use `--auto-connect` to discovery the remote instance if possible, or explicit CDP flag.

## Key Workflows

1. **Connect and Open**:
   `agent-browser --cdp http://openclaw-sandbox-browser.zeabur.internal:9222 open <url>`

2. **AI Snapshot (The standard way to "see" the page)**:
   `agent-browser snapshot -i` (Interactive elements only)

3. **Interact using Refs**:
   `agent-browser click @e1`
   `agent-browser fill @e2 "some text"`

4. **Debugging**:
   `agent-browser screenshot`
   `agent-browser console`

## Notes
- The browser persists via a background daemon.
- Always use `&&` for chainable commands to maintain the same browser context in one execution.
- If connection fails, check if the `openclaw-sandbox-browser` service is running in Zeabur.
