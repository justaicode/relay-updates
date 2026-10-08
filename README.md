# Relay for macOS

[Download Relay 0.3.12 for macOS](https://github.com/justaicode/relay-updates/releases/download/v0.3.12/Relay-0.3.12-macOS.dmg) · [Release notes and all assets](https://github.com/justaicode/relay-updates/releases/tag/v0.3.12)

Requires macOS 14 or later. Supports Intel and Apple Silicon. The app and drag-to-Applications installer are Developer ID signed and notarized by Apple.

Relay 0.3.12 moves clipboard items you reuse to the top without adding duplicates. It includes Contacts search and opening with one click, System Settings search, file previews and copy/path/folder actions, Launch at Login, and optional automatic updates.

If a protected password field blocks your shortcut, open **Clipboard & Snippets** from Relay’s menu bar, then choose **Paste**. The reported field-specific shortcut issue is still being investigated.

## Install

1. Download and open **Relay-0.3.12-macOS.dmg**.
2. Save any open Relay drafts and quit Relay if it is already running.
3. Drag **Relay.app** into **Applications**, replacing the older version when prompted, then open it.
4. For sync, use the same Apple Account on your Macs with iCloud Passwords & Keychain enabled.
5. Allow Relay under **System Settings → Privacy & Security → Accessibility** for text expansion and direct paste.

Your existing library and settings are preserved. Version 0.2.0 requires this manual upgrade once. Starting with 0.3.0, use **Check for Updates…** in Relay to install later versions. Optional **Automatically download and install future updates** is under **Library & Settings → Settings → General → Software Updates**; automatic installs normally finish when Relay quits.

This repository contains public installers and the signed update feed. Application source remains private. The appcast and update archives are signed with Relay’s Ed25519 update key. Do not edit `appcast.xml` after signing.
