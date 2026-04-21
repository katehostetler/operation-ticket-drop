# Operation: Bieber Drop

A tactical briefing document prepared by four autonomous agents in advance of the SWAG III US Tour onsale window.

> This document is for operational planning only. It does not constitute a guarantee of outcome.

## Live

Deployed via GitHub Pages. Open the site to view the briefing — includes a countdown to the next Friday 10:00 AM PT, an interactive pre-flight checklist, a dark-mode toggle, and a classified-style video transmission with a pulsing border synced to the beat.

## Local preview

```sh
python3 -m http.server 5173
open http://127.0.0.1:5173/
```

Must be served over HTTP (not `file://`) — the YouTube IFrame API needs a valid origin for its `postMessage` handshake.

## Credits

- Design: handoff from Claude Design (claude.ai/design)
- Implementation: [Claude Code](https://claude.com/claude-code)
- Fonts: Fraunces + JetBrains Mono (Google Fonts)
- Subject: Biebs
