# CLAUDE.md — `cess.vaked.dev`

## Commands
- **Local Dev Server**: `python3 -m http.server 8785` (open `http://localhost:8785`)
- **Deploy**: Cloudflare Pages / Static Hosting on `cess.vaked.dev`.

## Architecture
- `index.html`: Self-contained HTML5/CSS3/JavaScript semantic Q&A portal and monograph explorer.
- Inference: `https://coder.vaked.dev/v1/chat/completions` with client-side deterministic reasoning fallback.
