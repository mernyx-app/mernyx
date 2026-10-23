<p align="center">
  <img src="assets/icon.png" width="112" height="112" alt="Mernyx app icon">
</p>

<h1 align="center">Mernyx</h1>

<p align="center">
  <strong>Visual Mermaid, Natively</strong><br>
  Native macOS editor for Mermaid diagrams. Move a node and the source follows —
  no WebView, no JavaScript bridge, no Electron.
</p>

<p align="center">
  <a href="https://mernyx.com">Website</a> ·
  <a href="https://mernyx.com/pricing/">Pricing</a> ·
  <a href="https://mernyx.com/support/">Support</a> ·
  <a href="https://x.com/isacedx">X</a>
</p>

## What this repository is

This is the public home for Mernyx feedback and release builds.

- **Issues** — bug reports and feature requests.
- **Discussions** — questions, workflows and diagrams you have made.
- **Releases** — signed and notarised direct-download builds, when available.

The application source is not public. This repository does not contain the app's source code, and an issue is not a request to open-source it.

## The app

Mernyx opens `.mmd` and `.mermaid` files and renders all 34 diagram families locally. The free tier is a complete viewer and source editor: editing, Quick Look, Finder thumbnails, cursor ↔ canvas linkage, and PNG/SVG/PDF export at 1×, with no watermark and no account.

Mernyx Pro is a one-time $19 licence that unlocks canvas editing, style and label editing, AI generation and repair (bring your own key), 2×/3× export, margins, batch export and presets. Updates are included for the life of the app. Pro is sold on mernyx.com; the Mac App Store listing is a separate channel.

Requirements: macOS 14 or later, Apple silicon or Intel.

## Install

Homebrew:

```sh
brew tap mernyx-app/mernyx
brew install --cask mernyx
```

Or download the signed and notarised build from [mernyx.com](https://mernyx.com).

The Homebrew cask installs the **standalone (direct) build**, which uses a licence
key instead of the Mac App Store receipt. It uses the same bundle identifier as
the App Store edition, so only one copy can be installed at a time — installing
one replaces the other, and store purchases do not carry over.

The app updates itself; Homebrew is the install path, not the update channel.

## Before filing an issue

- Check the [support page](https://mernyx.com/support/) and the FAQ.
- For a rendering or parsing problem, include the diagram source (it is only text), the Mernyx version, and your macOS version.
- Do not paste API keys, licence keys or anything else you would not want to be public.

## Security

Please do not report security issues in a public issue. Email [hi@mernyx.com](mailto:hi@mernyx.com) instead.

## Licence

The Mernyx application is proprietary software. This repository's contents are provided for feedback and distribution purposes; no licence to the application source is granted.
