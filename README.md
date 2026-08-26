# dimmer-ext

MV3 extension playground: page reading-time estimator

Small but I use it weekly.

## Highlights

- Manifest V3, service worker based
- Per-tab time persisted to chrome.storage
- No remote calls, everything stays local
- Popup shows today's total focus time

## Installation

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## How to use

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── pull_request_template.md
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
npm test
```

## License

MIT licensed, see LICENSE.
