# Week 2 Build Lab

This portfolio completes the brief's minimum of two projects in each of four sections. Open `index.html` for the project launcher. Each project has a `prompts.md` build log. The two Chrome extensions include installation guides. The phone projects are installable web apps (PWA format) and store data locally.

## Run

For the static tools and design pages, open their HTML files in a browser. For PWA offline caching, serve this folder locally over `http://localhost` or deploy it to a static HTTPS host once; then install Bill Book or Auto Rally from the browser. Chrome extensions are loaded from `youtube-focus` or `job-clipper` via `chrome://extensions` → **Developer mode** → **Load unpacked**. They require Chrome.

## Privacy and scope

Resume, test, bill and focus data stays in browser-local storage. The extensions need Chrome's local storage; Job Clipper also asks for page access and notifications. No paid API or account is used. Bill Book creates a UPI payment intent link; its QR image is not included yet.
