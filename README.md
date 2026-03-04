# Awesome Chrome Extension Development [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Discord](https://img.shields.io/badge/Discord-Zovo-blueviolet.svg?logo=discord)](https://discord.gg/zovo)
[![Website](https://img.shields.io/badge/Website-zovo.one-blue)](https://zovo.one)
[![GitHub Stars](https://img.shields.io/github/stars/theluckystrike/awesome-chrome-extensions-dev?style=social)](https://github.com/theluckystrike/awesome-chrome-extensions-dev)

> A curated list of tools, libraries, frameworks, and resources for building Chrome extensions.

**Maintained by [Zovo](https://zovo.one)** &mdash; makers of 18+ Chrome extensions. Contributions welcome!

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
- [Build Tools](#build-tools)
- [Utilities](#utilities)
- [Documentation](#documentation)
- [Browser Compatibility](#browser-compatibility)
- [Communities](#communities)

---

## Analysis & Validation

- **[crx-permission-analyzer](https://github.com/theluckystrike/crx-permission-analyzer)** &mdash; Analyze Chrome extension permissions and flag dangerous combinations. Risk scoring, 40+ permission database, CLI + library. *By Zovo.*
- **[crx-manifest-validator](https://github.com/theluckystrike/crx-manifest-validator)** &mdash; Validate manifest.json files against MV2/MV3 specs. Catches missing fields, deprecated keys, dangerous host permissions, and CWS review flags. *By Zovo.*
- **[crx-extension-size-analyzer](https://github.com/theluckystrike/crx-extension-size-analyzer)** &mdash; Analyze extension bundle size. Reports per-file sizes, detects bloat, and recommends code splitting and image optimization. *By Zovo.*

## Boilerplates & Starters

- **[chrome-extension-starter-mv3](https://github.com/theluckystrike/chrome-extension-starter-mv3)** &mdash; Production-ready MV3 template with TypeScript, React, Tailwind CSS, message passing, and CI/CD. *By Zovo.*
- [Plasmo](https://github.com/PlasmoHQ/plasmo) &mdash; Browser extension framework with React/Vue/Svelte support.
- [WXT](https://github.com/wxt-dev/wxt) &mdash; Next-gen web extension framework.
- [Chrome Extension Boilerplate React](https://github.com/lxieyang/chrome-extension-boilerplate-react) &mdash; React 18 + TypeScript boilerplate.
- [Extension.js](https://github.com/extension-js/extension.js) &mdash; Zero-config cross-browser extension development.

## Storage

- **[chrome-storage-plus](https://github.com/theluckystrike/chrome-storage-plus)** &mdash; Type-safe storage wrapper with schema validation, migrations, reactive subscriptions, and quota management. Zero deps. *By Zovo.*
- [webext-storage](https://github.com/nicedoc/webext-storage) &mdash; Unified storage API for web extensions.

## Analytics

- **[extension-analytics](https://github.com/theluckystrike/extension-analytics)** &mdash; Privacy-first, local-only analytics for Chrome extensions. No external dependencies, no tracking servers. *By Zovo.*

## Content Scripts

- **[content-script-toolkit](https://github.com/theluckystrike/content-script-toolkit)** &mdash; Shadow DOM injection, element observers, page context bridge, floating UI panels, and text selection handlers. *By Zovo.*
- [webext-content-scripts](https://github.com/nicedoc/webext-content-scripts) &mdash; Utilities for MV3 dynamic content scripts.

## Migration Tools

- **[mv3-migrate](https://github.com/theluckystrike/mv3-migrate)** &mdash; Automatically migrate MV2 extensions to MV3. CLI + library. *By Zovo.*
- [Chrome Extension Migration Guide](https://developer.chrome.com/docs/extensions/develop/migrate) &mdash; Official Google migration docs.

## Tab Management

- **[tab-manager-api](https://github.com/theluckystrike/tab-manager-api)** &mdash; Tab grouping, session save/restore, deduplication, memory monitoring, and suspend helpers. Zero deps. *By Zovo.*

## Publishing & Deployment

- **[extension-publisher](https://github.com/theluckystrike/extension-publisher)** &mdash; CLI for manifest validation, version bumping, changelog generation, and CWS-ready packaging. *By Zovo.*
- [Chrome Webstore Upload](https://github.com/nicedoc/chrome-webstore-upload-cli) &mdash; Automated CWS publishing for CI.
- [web-ext](https://github.com/nicedoc/web-ext) &mdash; Mozilla's CLI for building and testing extensions.

## JSON Tools

- **[json-toolkit-cli](https://github.com/theluckystrike/json-toolkit-cli)** &mdash; Format, validate, diff, query, and convert JSON from the command line. *By Zovo.*

## Cookie Management

- **[cookie-inspector](https://github.com/theluckystrike/cookie-inspector)** &mdash; Audit cookies, generate privacy reports, check GDPR compliance, and export/import in multiple formats. *By Zovo.*

## UI Frameworks

- [Chakra UI](https://chakra-ui.com/) &mdash; Component library that works well in extension popups.
- [Radix UI](https://www.radix-ui.com/) &mdash; Unstyled accessible components.
- [shadcn/ui](https://ui.shadcn.com/) &mdash; Copy-paste components with Tailwind.

## Testing

- [Sinon Chrome](https://github.com/nicedoc/sinon-chrome) &mdash; Chrome API mocking for unit tests.
- [Puppeteer](https://github.com/puppeteer/puppeteer) &mdash; E2E testing for Chrome extensions using headless Chrome.
- [Playwright](https://playwright.dev/) &mdash; Cross-browser automation for testing extensions.
- [jest-webextension-mock](https://github.com/nicedoc/jest-webextension-mock) &mdash; TypeScript-friendly mocks for extension APIs.

## Build Tools

- [webpack-target-webextension](https://github.com/nicedoc/webpack-target-webextension) &mdash; Webpack target for browser extensions.
- [Vite Plugin Web Extension](https://github.com/nicedoc/vite-plugin-web-extension) &mdash; Vite plugin for building web extensions.
- [esbuild-plugin-web-extension](https://github.com/nicedoc/esbuild-plugin-webextension) &mdash; esbuild plugin for web extensions.

## Utilities

- [webext-bridge](https://github.com/nicedoc/webext-bridge) &mdash; Simple message passing between extension contexts.
- [webext-messenger](https://github.com/nicedoc/webext-messenger) &mdash; Type-safe messaging between extension contexts.
- [@webext-core/messaging](https://github.com/nicedoc/awesome-webextensions) &mdash; Modern messaging for web extensions.

## Documentation

- [Chrome Extensions Documentation](https://developer.chrome.com/docs/extensions/) &mdash; Official Chrome extension docs.
- [Chrome Extension Samples](https://github.com/GoogleChrome/chrome-extensions-samples) &mdash; Official sample extensions by Google.
- [MDN Web Extensions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions) &mdash; Cross-browser extension docs.

## Browser Compatibility

- [webextension-polyfill](https://github.com/nicedoc/webextension-polyfill) &mdash; Browser polyfill for cross-browser extensions.
- [Browser Compatibility Data](https://github.com/mdn/browser-compat-data) &mdash; MDN browser compat data for extension APIs.

## Communities

- [r/chrome_extensions](https://www.reddit.com/r/chrome_extensions/) &mdash; Reddit community for Chrome extension developers.
- [Chrome Extension Dev Discord](https://discord.gg/ext) &mdash; Discord community.

---

## Contributing

Contributions welcome! Please open a PR to add tools, libraries, or resources.

Requirements for submissions:

- Must have a README and license.
- Must be relevant to Chrome/browser extension development.
- Add entries in alphabetical order within their category.

## See Also

### Related Zovo Repositories

- [zovo-extension-template](https://github.com/theluckystrike/zovo-extension-template) &mdash; Boilerplate for building privacy-first Chrome extensions.
- [zovo-types-webext](https://github.com/theluckystrike/zovo-types-webext) &mdash; Comprehensive TypeScript type definitions for browser extensions.

### Zovo Chrome Extensions

- [Zovo Tab Manager](https://chrome.google.com/webstore/detail/zovo-tab-manager) &mdash; Manage tabs efficiently.
- [Zovo Focus](https://chrome.google.com/webstore/detail/zovo-focus) &mdash; Block distractions.
- [Zovo Permissions Scanner](https://chrome.google.com/webstore/detail/zovo-permissions-scanner) &mdash; Check extension privacy grades.
- [Zovo Cookie Manager](https://chrome.google.com/webstore/detail/zovo-cookie-manager) &mdash; Advanced cookie management.

Visit [zovo.one](https://zovo.one) for more information.

## License

MIT &mdash; [Zovo](https://zovo.one)
