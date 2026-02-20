# Changelog

All notable changes to WorkTools will be documented in this file.

## [2.0.0] - 2026-02-20

### Added (Mac App)

- **System Monitor** - Real-time memory and CPU usage monitoring
  - Per-process breakdown with instance grouping
  - Kill processes directly from the monitor
  - Configurable display settings (opacity, font size, theme)
  - Always-on-top mode with resizable, position-saved window
- **Clipboard Manager** - Persistent clipboard history
  - Automatic clipboard tracking (up to 50 entries)
  - Pin important items, one-click copy from history
  - Clear history while preserving pinned items
- **Network Monitor** - Real-time network activity
  - Live bandwidth monitoring per interface (upload/download)
  - Wi-Fi signal quality, SSID, channel, and TX rate
  - IP address display for all active interfaces
- **Quick Notes** - Multi-tab note-taking from the menu bar
  - Multiple notes with tab management
  - Persistent storage across sessions
- **Color Picker** - Color selection tool for developers
  - HSL, RGB, and HEX color format support
  - Recent colors history and saved palettes
  - One-click copy color values to clipboard
- **Show in Dock** setting - Toggle macOS Dock icon visibility

### Changed

- Updated popup window to include Tools section with all 5 new tools
- Expanded settings window with Dock visibility toggle
- Bumped version to 2.0.0

## [1.0.5] - 2026-01-30

### Added

- **Trello RTL Support** - Right-to-left text direction for Hebrew/Arabic content in Trello
  - Automatic RTL for boards, cards, comments, and checklists
  - Preserves LTR for code blocks
  - Toggle on/off from extension popup and settings

### Changed

- Updated extension description to include Trello
- Updated landing page and documentation

## [1.0.4] - 2026-01-30

### Added
- Show warning in omnibox when JIRA URL is not configured
- Notification and auto-open settings when trying Quick JIRA without configuration

### Fixed
- Quick JIRA now provides feedback when URL is not set instead of silently failing

## [1.0.3] - 2026-01-29

### Added
- **JIRA Related PRs Viewer** - View linked GitHub PRs directly in JIRA ticket view
  - Automatically detects GitHub PR links in tickets
  - Shows PR status (open, merged, closed, draft)
  - Displays additions/deletions count
  - Click to open PR in new tab
- **Slack RTL Support** - Right-to-left text direction for Hebrew/Arabic content in Slack
  - Automatic RTL for messages, threads, and input
  - Preserves LTR for code blocks

### Changed
- Updated README with screenshots and badges
- Improved documentation with feature matrix

## [1.0.2] - 2026-01-28

### Added
- Initial Slack RTL Support feature

### Fixed
- Version display consistency across all UI components

## [1.0.1] - 2026-01-27

### Changed
- Shortened extension name from "WorkTools - Productivity Extension" to "WorkTools"
- Updated Chrome Web Store listing

### Fixed
- Host permissions to comply with Chrome Web Store policies

## [1.0.0] - 2026-01-26

### Added
- **Quick JIRA** - Open JIRA tickets instantly from browser omnibox
  - Type `jira PROJ-123` in address bar
  - Recent tickets history
- **JIRA RTL Support** - Right-to-left text direction for Hebrew/Arabic in JIRA
  - Automatic RTL for ticket descriptions, comments, and summaries
- **GitHub PR Patch Download** - Quick access to `.patch` files for pull requests
  - Adds `.patch` button to PR header
  - One-click download of PR changes
- Extension popup with feature toggles
- Settings page for JIRA base URL configuration
