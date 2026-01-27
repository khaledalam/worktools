# WorkTools - Productivity Extension

A lightweight Chrome extension designed for developers and teams who work with JIRA and GitHub daily.

## Features

### JIRA Tools

**Quick JIRA Access**
- Open any JIRA ticket instantly from the popup or address bar
- Type `jira` in your address bar followed by the ticket ID (e.g., `jira PROJ-123`)
- Recently accessed tickets are saved for quick re-access

**RTL Support**
- Automatic right-to-left text direction for Hebrew, Arabic, and other RTL languages
- Applies to descriptions, comments, and custom fields

### GitHub Tools

**PR Patch Download**
- Adds a `.patch` button to pull request pages
- Download patch files directly for use with `git apply`

## Installation

Install from the [Chrome Web Store](#)

## Settings

- **JIRA Base URL**: Configure your JIRA instance (e.g., `https://company.atlassian.net`)
- **RTL Support**: Toggle on/off
- **PR Patch Download**: Toggle on/off

Settings sync across your Chrome devices.

## Permissions

This extension only requests permissions for the sites it needs:
- `*.atlassian.net` - For JIRA features
- `github.com` - For GitHub features
- `storage` - To save your settings

**No data is collected or sent to external servers.**

## Feedback & Suggestions

Have an idea for a new tool? Found a bug?

[Open an issue](https://github.com/khaledalam/WorkTools/issues/new/choose)

## Author

Made by [Khaled Alam](https://khaledalam.net)

## License

MIT License
