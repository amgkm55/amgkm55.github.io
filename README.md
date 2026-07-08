# Web Page & AI Chat Archive (웹페이지 + AI 채팅 아카이브)

A Chrome extension that saves web pages and AI chat conversations (ChatGPT, Claude, Gemini,
Perplexity, Grok) to your own computer — as full HTML/MHTML snapshots or Markdown transcripts.
All processing happens locally in your browser; no data is ever sent to a server operated by the
developer or any third party.

- **Chrome Web Store:** https://chromewebstore.google.com/detail/apghhflhfdmelpgmjhijepngmjpejano
- **Privacy Policy:** [privacy.html](./privacy.html)
- **Contact:** blackcows4444@gmail.com

## What this site is

This repository is published via GitHub Pages (`amgkm55.github.io`) and hosts only two public
pages for the Chrome Web Store listing:

| Page | Purpose |
|---|---|
| [`index.html`](./index.html) | Landing page with links to the Web Store listing and the privacy policy |
| [`privacy.html`](./privacy.html) | Privacy Policy (English / 한국어), required by the Chrome Web Store |

## Privacy summary

- No personal or sensitive user data is collected, transmitted, sold, or shared.
- The extension only reads the active tab's content when the user explicitly triggers a save.
- Generated files are written only to the user's local Downloads folder.
- Settings and custom parsing rules are stored locally via `chrome.storage`.
- See [privacy.html](./privacy.html) for the full policy, including the permissions table.
