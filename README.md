# WorkTools

Productivity tools for developers who work with JIRA and GitHub daily.

## Platforms

| Platform | Status | Install |
| -------- | ------ | ------- |
| Mac App | ✅ Available | `brew install khaledalam/worktools/worktools` |
| Chrome Extension | ✅ Available | Chrome Web Store |
| Firefox Extension | ✅ Available | [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/worktools/) |
| Windows App | 🚧 Coming Soon | - |

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

### GitHub PR Patch Download

Quick access to `.patch` files for pull requests.

- Adds `.patch` button to PR header
- One-click download of PR changes

---

## Mac App

Menu bar app for quick JIRA access.

**Installation:**

```bash
brew install khaledalam/worktools/worktools
```

Or download from [Releases](https://github.com/khaledalam/worktools/releases).

**Features:**

- Open JIRA tickets instantly from menu bar
- Recent tickets history with timestamps
- Keyboard shortcut: `Cmd + Shift + J`
- Settings for JIRA base URL configuration

---

## Chrome Extension

Browser extension for JIRA and GitHub productivity.

**Features:**

- **Quick JIRA:** Type `jira PROJ-123` in address bar to open tickets
- **RTL Support:** Right-to-left text for Hebrew/Arabic in JIRA
- **PR Patch Download:** `.patch` button on GitHub pull requests
- Recent tickets history
- Toggle features on/off from popup

---

## Firefox Extension

Browser extension for JIRA and GitHub productivity.

**Installation:** [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/worktools/)

**Features:**

- **Quick JIRA:** Type `jira PROJ-123` in address bar to open tickets
- **RTL Support:** Right-to-left text for Hebrew/Arabic in JIRA
- **PR Patch Download:** `.patch` button on GitHub pull requests
- Recent tickets history
- Toggle features on/off from popup

---

## Configuration

Set your JIRA base URL in Settings:

```text
https://company.atlassian.net
```

## Privacy

No data collected. All settings stored locally. See [Privacy Policy](PRIVACY_POLICY.md).

## Contributing

Issues and PRs welcome at [GitHub](https://github.com/khaledalam/worktools/issues).

## Author

[Khaled Alam](https://khaledalam.net)

## License

MIT
