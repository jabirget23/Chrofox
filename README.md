# Chrofox

> **Chrome Web Store compatibility for Firefox.**

**WORK IN PROGRESS**

Chrofox is an experimental Firefox extension that aims to install and run Chrome Web Store extensions on Firefox by providing compatibility layers and automatic conversion where possible.

**This project is currently in beta and is NOT stable. Do not expect every extension to work.**

## Supported Firefox Versions

Chrofox is currently supported **only** on:

* Firefox Developer Edition (**Recommended**)
* Firefox Nightly
* Firefox ESR

Firefox Stable is **not officially supported** at this time. Chrofox relies on experimental and developer-focused Firefox features that may not be available in Stable releases. 

You **will** encounter:

* Bugs
* Crashes
* Installation failures
* Broken extensions
* Missing features
* Performance issues
* Incomplete compatibility

---

# Features

* Install supported Chrome extensions from the Chrome Web Store
* Compatibility layer for common Chromium APIs
* Automatic extension analysis
* Automatic compatibility patches (when possible)
* Native **Add to Firefox** button on Chrome Web Store pages
* Manifest V2 support
* Partial Manifest V3 support
* Automatic permission translation
* Local processing (no online conversion service)

---

# Compatibility

Chrofox aims for maximum compatibility, but Firefox and Chromium implement different APIs and browser behavior.

Extensions that rely on:

* Chrome-exclusive APIs
* Enterprise APIs
* Native Messaging
* Proprietary Google services
* Unsupported Manifest V3 APIs
* Browser-specific behavior

may fail, install with reduced functionality, or require additional compatibility work.

Compatibility is expected to improve as development progresses.

---

# Installation

# Requirements:
1. Firefox Developer Edition

Download the latest `.xpi` release from the GitHub Releases page.

In Firefox Developer:
1. Open `about:config`, Click "Accept the Risk and Continue", if there is a disclaimer, if not, continue.
2. Search "xpinstall.signatures.required" and set it to false by double clicking it. Now exit `about:config`.
3. Open `about:addons`.
2. Click the settings (gear) icon.
3. Select **Install Add-on From File...**
4. Choose the downloaded `.xpi` file.
5. Grant the requested permissions if Firefox Developer Edition does request for any permission

> **Note:** Firefox Developer Edition is the recommended browser for the best compatibility and access to the latest features.

---

# Reporting Bugs

Because Chrofox is in beta, bug reports are extremely valuable.

When opening an issue, please include:

* Firefox version (Developer, Nightly, or ESR)
* Operating system
* Extension name
* Chrome Web Store URL
* Error logs
* Screenshots (if applicable)
* Steps to reproduce the issue

---

# License

MIT License.

---

# Disclaimer

Chrofox is an independent open-source project.

It is **not affiliated with, endorsed by, or sponsored by Google, Mozilla, or their respective projects.**

Chrome, Chrome Web Store, Chromium, and Firefox are trademarks of their respective owners.

This software is provided **"as is"**, without warranty of any kind. As beta software, it may contain significant bugs, compatibility issues, and breaking changes between releases.
