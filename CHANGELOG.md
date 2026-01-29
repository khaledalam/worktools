# Changelog

All notable changes to WorkTools will be documented in this file.

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
