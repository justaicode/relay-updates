# Relay for macOS

[Download Relay 0.3.19 for macOS](https://github.com/justaicode/relay-updates/releases/download/v0.3.19/Relay-0.3.19-macOS.dmg) · [Release notes and all assets](https://github.com/justaicode/relay-updates/releases/tag/v0.3.19)

Requires macOS 14 or later. Supports Intel and Apple Silicon. The app and drag-to-Applications installer are Developer ID signed and notarized by Apple.

Relay 0.3.19 adds screenshot zoom: use the menu next to Discard for Fit, 100% actual pixels, or up to 400%. Scroll to reach the rest of the image while the controls stay visible. Command–0 selects Fit, Command–1 selects 100%, and Command–plus/minus zoom in/out. Zoom and resizing keep the current area centered; exported images retain their original resolution. The compact frame, soft shadow, padded text-size popup and Discard remain included. Discard closes without saving/copying; Copy & Close saves to Desktop and clipboard. Use V/A/D/R/T for tools and Shift+Enter for multiline text. The native area selector, size readout and Space-drag remain included. Further capture-smoothness improvements are still being investigated. The native editor supports arrows, drawing, rectangles and text. Copy or save the annotated PNG while keeping the editor open. Set your shortcut in Settings → General → Screenshot; macOS Screen Recording permission is required. Clipboard items you reuse move to the top without adding duplicates. It includes Contacts search and opening with one click, System Settings search, file previews and copy/path/folder actions, Launch at Login, and optional automatic updates.

If a protected password field blocks your shortcut, open **Clipboard & Snippets** from Relay’s menu bar, then choose **Paste**. The reported field-specific shortcut issue is still being investigated.

## Install

1. Download and open **Relay-0.3.19-macOS.dmg**.
2. Save any open Relay drafts and quit Relay if it is already running.
3. Drag **Relay.app** into **Applications**, replacing the older version when prompted, then open it.
4. For sync, use the same Apple Account on your Macs with iCloud Passwords & Keychain enabled.
5. Allow Relay under **System Settings → Privacy & Security → Accessibility** for text expansion and direct paste.

Your existing library and settings are preserved. Version 0.2.0 requires this manual upgrade once. Starting with 0.3.0, use **Check for Updates…** in Relay to install later versions. Optional **Automatically download and install future updates** is under **Library & Settings → Settings → General → Software Updates**; automatic installs normally finish when Relay quits.

This repository contains public installers and the signed update feed. Application source remains private. The appcast and update archives are signed with Relay’s Ed25519 update key. Do not edit `appcast.xml` after signing.
