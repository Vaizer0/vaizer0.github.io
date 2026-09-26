# Browser Agent Harness

Fast, mobile-friendly AI coding chat for Android and PC browsers.

Live page:
https://vaizer0.github.io/browser-agent-harness/

## Modes

- Free Anonymous: public legacy OpenAI-compatible endpoint, no site login or API key required by the harness.
- OpenAI Compatible: custom base URL, key and model.
- Anthropic Messages: custom compatible endpoint.
- Gemini Web2API: use `http://127.0.0.1:8081/v1` and an exposed Gemini model.

## Notes

The GitHub Pages frontend is static. It cannot start a Termux/Python process. A local Gemini Web2API server must already be running, or the user must provide a remote HTTPS endpoint.

Chats are persisted locally in the browser. API keys are intentionally not written to localStorage.
