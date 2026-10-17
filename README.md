# Vega

A free, private AI assistant for Windows. Website: https://vegastudio.pages.dev/ The AI runs on your own PC through [Ollama](https://ollama.com); no account and no subscription.

**[Download the latest version](https://github.com/testactfrln-ui/vega/releases/latest/download/Vega-Assistant-Setup.exe)** · [All releases](https://github.com/testactfrln-ui/vega/releases)

## This repo

- `site/` is the website (plain HTML, no build step).
- `wrangler.jsonc` deploys `site/` to Cloudflare Pages (vegastudio.pages.dev). No build step.
- **Releases** hold the Windows installer. Every installed copy of Vega checks them and updates itself, so this repo must stay public.

New versions are published from the admin app (JARVIS → Settings → About → Publish Vega).
