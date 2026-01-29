<p align="center">
  <a href="https://khaledalam.github.io/worktools/"><img src="https://img.shields.io/badge/website-live-brightgreen" alt="Website"></a>
  <img src="https://img.shields.io/badge/platforms-Chrome%20%7C%20Firefox%20%7C%20macOS-blue" alt="Platforms">
  <a href="https://chromewebstore.google.com/detail/worktools/amoikjkckimekcjfkdnkfianhajpdmgc"><img src="https://img.shields.io/chrome-web-store/v/amoikjkckimekcjfkdnkfianhajpdmgc" alt="Chrome Web Store"></a>
  <a href="https://addons.mozilla.org/en-US/firefox/addon/worktools/"><img src="https://img.shields.io/amo/v/worktools" alt="Firefox Add-ons"></a>
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
</p>

# WorkTools

> **[Visit Website](https://khaledalam.github.io/worktools/)** | Productivity tools for developers who work with JIRA, GitHub, and Slack daily.

<p align="center">
  <img src="assets/screenshots/popup.png" alt="WorkTools Popup" width="400">
</p>

## Platforms

| Platform | Status | Install |
| -------- | ------ | ------- |
| Chrome Extension | ✅ Available | [Chrome Web Store](https://chromewebstore.google.com/detail/worktools/amoikjkckimekcjfkdnkfianhajpdmgc) |
| Firefox Extension | ✅ Available | [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/worktools/) |
| Mac App | ✅ Available | `brew install khaledalam/worktools/worktools` |
| Windows App | 🚧 Coming Soon | - |
| Linux App | 🚧 Coming Soon | - |

---

## Feature Matrix

| Feature | Chrome | Firefox | Mac | Windows | Linux |
| ------- | :----: | :-----: | :-: | :-----: | :---: |
| Quick JIRA | ✅ | ✅ | ✅ | 🚧 | 🚧 |
| JIRA RTL Support | ✅ | ✅ | ❌ | ❌ | ❌ |
| JIRA Related PRs | ✅ | ❌ | ❌ | ❌ | ❌ |
| GitHub PR Patch | ✅ | ✅ | ❌ | ❌ | ❌ |
| Slack RTL Support | ✅ | ❌ | ❌ | ❌ | ❌ |
| Recent Tickets | ✅ | ✅ | ✅ | 🚧 | 🚧 |
| Keyboard Shortcut | ❌ | ❌ | ✅ | 🚧 | 🚧 |
| Menu Bar App | ❌ | ❌ | ✅ | 🚧 | 🚧 |

---

## Features

### Quick JIRA

Open JIRA tickets instantly without navigating through the browser.

- **Mac:** Menu bar app with keyboard shortcut `Cmd + Shift + J`
- **Browser:** Type `jira PROJ-123` in address bar (omnibox)
- Recent tickets history with timestamps

### JIRA RTL Support

Right-to-left text direction for Hebrew/Arabic content in JIRA.

- Automatic RTL for ticket descriptions, comments, and summaries
- Toggle on/off from extension popup

### JIRA Related PRs Viewer

View linked GitHub pull requests directly in JIRA ticket view.

- Automatically detects GitHub PR links in tickets
- Shows PR status (open, merged, closed, draft)
- Displays additions/deletions count
- Click to open PR in new tab
- Toggle on/off from extension popup

### GitHub PR Patch Download

Quick access to `.patch` files for pull requests.

<p align="center">
  <img src="assets/screenshots/github-pr-patch.png" alt="GitHub PR Patch Button" width="700">
</p>

- Adds `.patch` button to PR header
- One-click download of PR changes

### Slack RTL Support

Right-to-left text direction for Hebrew/Arabic content in Slack.

<p align="center">
  <img src="assets/screenshots/slack-rtl.png" alt="Slack RTL Support" width="500">
</p>

- Automatic RTL for messages, threads, and input
- Preserves LTR for code blocks
- Toggle on/off from extension popup

---

## Installation

### Chrome Extension

Install from [Chrome Web Store](https://chromewebstore.google.com/detail/worktools/amoikjkckimekcjfkdnkfianhajpdmgc)

**Features:**
- Quick JIRA with omnibox support
- JIRA RTL Support
- JIRA Related PRs Viewer
- GitHub PR Patch Download
- Slack RTL Support
- Recent tickets history
- Toggle features on/off from popup

### Firefox Extension

Install from [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/worktools/)

**Features:**
- Quick JIRA with omnibox support
- JIRA RTL Support
- GitHub PR Patch Download
- Recent tickets history
- Toggle features on/off from popup

### Mac App

```bash
brew install khaledalam/worktools/worktools
```

Or download from [Releases](https://github.com/khaledalam/worktools/releases).

**Features:**
- Menu bar app for quick JIRA access
- Recent tickets history with timestamps
- Keyboard shortcut: `Cmd + Shift + J`
- Settings for JIRA base URL configuration

---

## Configuration

Set your JIRA base URL in Settings:

```
https://company.atlassian.net
```

---

## Privacy

No data collected. All settings stored locally. See [Privacy Policy](PRIVACY_POLICY.md).

---

## Contributing

Issues and PRs welcome at [GitHub](https://github.com/khaledalam/worktools/issues).

---

## Author

**Khaled Alam** - [khaledalam.net](https://khaledalam.net)

---

## License

MIT
