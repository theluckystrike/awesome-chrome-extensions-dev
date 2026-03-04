# Awesome Chrome Extension Development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, libraries, frameworks, and resources for building Chrome extensions.

**Maintained by [Zovo](https://zovo.one)** -- makers of 18+ Chrome extensions. Contributions welcome!

## Contents

- [Analysis & Validation](#analysis--validation)
- [Boilerplates & Starters](#boilerplates--starters)
- [Storage](#storage)
- [Analytics](#analytics)
- [Content Scripts](#content-scripts)
- [Migration Tools](#migration-tools)
- [Tab Management](#tab-management)
- [Publishing & Deployment](#publishing--deployment)
- [JSON Tools](#json-tools)
- [Cookie Management](#cookie-management)
- [UI Frameworks](#ui-frameworks)
- [Testing](#testing)
- [Documentation](#documentation)
- [Browser Compatibility](#browser-compatibility)
- [Build Tools](#build-tools)
- [Utilities](#utilities)
- [Communities](#communities)

---

## Analysis & Validation

- **[crx-permission-analyzer](https://github.com/theluckystrike/crx-permission-analyzer)** -- Analyze Chrome extension permissions and flag dangerous combinations. Risk scoring, 40+ permission database, CLI + library. _By Zovo_
- **[crx-manifest-validator](https://github.com/theluckystrike/crx-manifest-validator)** -- Validate manifest.json files against MV2/MV3 specs. Catches missing fields, deprecated keys, dangerous host permissions, CWS review flags. _By Zovo_
- **[crx-extension-size-analyzer](https://github.com/theluckystrike/crx-extension-size-analyzer)** -- Analyze extension bundle size. Reports per-file sizes, detects bloat, recommends code splitting and image optimization. _By Zovo_

## Boilerplates & Starters

- **[chrome-extension-starter-mv3](https://github.com/theluckystrike/chrome-extension-starter-mv3)** -- Production-ready MV3 template with TypeScript, React, Tailwind CSS, message passing, and CI/CD. _By Zovo_
- [Plasmo](https://github.com/PlasmoHQ/plasmo) -- Browser extension framework with React/Vue/Svelte support.
- [WXT](https://github.com/wxt-dev/wxt) -- Next-gen web extension framework.
- [Chrome Extension Boilerplate React](https://github.com/lxieyang/chrome-extension-boilerplate-react) -- React 18 + TypeScript boilerplate.
- [Extension.js](https://github.com/extension-js/extension.js) -- Zero-config cross-browser extension development.

## Storage

- **[chrome-storage-plus](https://github.com/theluckystrike/chrome-storage-plus)** -- Type-safe storage wrapper with schema validation, migrations, reactive subscriptions, and quota management. Zero deps. _By Zovo_
- [webext-storage](https://github.com/fregante/webext-storage) -- Unified storage API for web extensions.

## Analytics

- **[extension-analytics](https://github.com/theluckystrike/extension-analytics)** -- Privacy-first, local-only analytics for Chrome extensions. No external dependencies, no tracking servers. _By Zovo_

## Content Scripts

- **[content-script-toolkit](https://github.com/theluckystrike/content-script-toolkit)** -- Shadow DOM injection, element observers, page context bridge, floating UI panels, and text selection handlers. _By Zovo_
- [webext-content-scripts](https://github.com/fregante/webext-content-scripts) -- Utilities for MV3 dynamic content scripts.

## Migration Tools

- **[mv3-migrate](https://github.com/theluckystrike/mv3-migrate)** -- Automatically migrate MV2 extensions to MV3. CLI + library. _By Zovo_
- [Chrome Extension Migration Guide](https://developer.chrome.com/docs/extensions/develop/migrate) -- Official Google migration docs.

## Tab Management

- **[tab-manager-api](https://github.com/theluckystrike/tab-manager-api)** -- Tab grouping, session save/restore, deduplication, memory monitoring, and suspend helpers. Zero deps. _By Zovo_

## Publishing & Deployment

- **[extension-publisher](https://github.com/theluckystrike/extension-publisher)** -- CLI for manifest validation, version bumping, changelog generation, and CWS-ready packaging. _By Zovo_
- [Chrome Webstore Upload](https://github.com/fregante/chrome-webstore-upload-cli) -- Automated CWS publishing for CI.
- [web-ext](https://github.com/mozilla/web-ext) -- Mozilla's CLI for building and testing extensions.

## JSON Tools

- **[json-toolkit-cli](https://github.com/theluckystrike/json-toolkit-cli)** -- Format, validate, diff, query, and convert JSON from the command line. _By Zovo_

## Cookie Management

- **[cookie-inspector](https://github.com/theluckystrike/cookie-inspector)** -- Audit cookies, generate privacy reports, check GDPR compliance, and export/import in multiple formats. _By Zovo_
- [Cookie Manager Pro](https://chrome.google.com/webstore/detail/cookie-manager-pro) -- Visual cookie management Chrome extension. _By Zovo_

## UI Frameworks

- [Chakra UI](https://chakra-ui.com/) -- Component library that works great in extension popups.
- [Radix UI](https://www.radix-ui.com/) -- Unstyled accessible components.
- [shadcn/ui](https://ui.shadcn.com/) -- Copy-paste components with Tailwind.

## Testing

- [Sinon Chrome](https://github.com/acvetkov/sinon-chrome) -- Chrome API mocking for unit tests.
- [Puppeteer with Extensions](https://github.com/puppeteer/puppeteer/blob/main/docs/api/puppeteer.page.md) -- E2E testing for Chrome extensions using Puppeteer.
- [Playwright](https://playwright.dev/) -- Cross-browser automation for testing extensions.
- [Jest Web Extension Mock](https://github.com/theluckystrike/jest-webextension-mock) -- TypeScript-friendly mocks for extension APIs.

## Documentation

- [Chrome Extensions Documentation](https://developer.chrome.com/docs/extensions/) -- Official Chrome extension docs.
- [Chrome Extension Samples](https://github.com/GoogleChrome/chrome-extensions-samples) -- Official sample extensions by Google.
- [MDN Web Extensions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions) -- Cross-browser extension docs.

## Browser Compatibility

- [webextension-polyfill](https://github.com/mozilla/webextension-polyfill) -- Browser polyfill for cross-browser extensions.
- [Browser Compatibility Data](https://github.com/mdn/browser-compat-data) -- MDN browser compat data for extension APIs.
- [webext-cross-browser](https://github.com/mozilla/webext-cross-browser) -- Handle cross-browser differences.

## Build Tools

- [webpack-target-webextension](https://github.com/theluckystrike/webpack-target-webextension) -- Webpack target for browser extensions.
- [Vite Plugin Web Extension](https://github.com/IndexXuan/vite-plugin-web-extension) -- Vite plugin for building web extensions.
- [esbuild-plugin-web-extension](https://github.com/kyfg/esbuild-plugin-webextension) -- esbuild plugin for web extensions.

## Utilities

- [webext-bridge](https://github.com/kyfg/webext-bridge) -- Simple message passing between contexts.
- [webext-messenger](https://github.com/henrikdahl/webext-messenger) -- Type-safe messaging between extension contexts.
- [@webext-core/messaging](https://github.com/AntoneWe/awesome-webextensions) -- Modern messaging for web extensions.

## Communities

- [r/chrome_extensions](https://www.reddit.com/r/chrome_extensions/) -- Reddit community for Chrome extension developers.
- [Chrome Extension Dev Discord](https://discord.gg/ext) -- Discord community.

---

## Contributing

Contributions welcome! Please open a PR to add tools, libraries, or resources.

Requirements for submissions:
- Must have a README and license
- Must be relevant to Chrome/browser extension development
- Add entries in alphabetical order within their category

## License

MIT -- [Zovo](https://zovo.one)

---

### Zovo Chrome Extensions

- [Zovo Tab Manager](https://chrome.google.com/webstore/detail/zovo-tab-manager) - Manage tabs efficiently
- [Zovo Focus](https://chrome.google.com/webstore/detail/zovo-focus) - Block distractions
- [Zovo Permissions Scanner](https://chrome.google.com/webstore/detail/zovo-permissions-scanner) - Check extension privacy grades
- [Zovo Cookie Manager](https://chrome.google.com/webstore/detail/zovo-cookie-manager) - Advanced cookie management

Visit [zovo.one](https://zovo.one) for more information.
