# Awesome WebExtensions Overview

A curated list of awesome resources for WebExtensions development.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/fregante/Awesome-WebExtensions/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 fregante/Awesome-WebExtensions](https://github.com/fregante/Awesome-WebExtensions) · ⭐ 1.3K · 🏷️ Platforms

[ [Daily](/content/fregante/Awesome-WebExtensions/README.md) / [Weekly](/content/fregante/Awesome-WebExtensions/week/README.md) / Overview ]

---

# Awesome WebExtensions [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources for WebExtensions development.

WebExtensions are a cross-browser system for developing browser add-ons. To a large extent the system is compatible with the extension API supported by Google Chrome. Extensions written for this browser will in most cases run in Firefox with just [a few changes](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Porting_a_Google_Chrome_extension).

Follow [@fregante](https://fregante.com) for more webext-related news.

## Contents

*   [Getting started](#getting-started)
*   [Community](#community)
*   [Libraries and Frameworks](#libraries-and-frameworks)
*   [Tools](#tools)
*   [Testing](#testing)
*   [Boilerplates](#boilerplates)
*   [Sample Extensions](#sample-extensions)

## Getting started

*   [Chrome Extensions documentation](https://developer.chrome.com/docs/extensions/reference) - Documentation for the original Chrome extension model.
*   [Mozilla's WebExtensions documentation](https://developer.mozilla.org/en-US/Add-ons/WebExtensions) - MDN wiki for the WebExtensions API.
*   [Browser support for WebExtensions](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Browser_support_for_JavaScript_APIs) - Compatibility table for Chrome, Edge, Firefox, and Opera.
*   [Safari Extensions documentation](https://developer.apple.com/safari/extensions/) - Developer documentation on building Safari extensions. Technically not WebExtensions, the API is completely different.
*   [Opera API support](https://dev.opera.com/extensions/apis/) - Detailed WebExtensions support for Opera.
*   [Browser Extension Standard](https://browserext.github.io/browserext/) - Standard for the API, supported by Mozilla, Opera and Microsoft.

## Community

*   [Google Groups](https://groups.google.com/a/chromium.org/forum/#!forum/chromium-extensions) - Discussions.
*   [Mozilla Discourse](https://discourse.mozilla.org/c/add-ons) - Discussions.
*   [`#addons:mozilla.org`](https://matrix.to/#/#addons:mozilla.org) - Matrix channel by Mozilla.
*   [`google-chrome-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/google-chrome-extension) - Relevant questions.
*   [`firefox-addon-webextensions` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/firefox-addon-webextensions) - Relevant questions.
*   [`microsoft-edge-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/microsoft-edge-extension) - Relevant questions.

## Libraries and Frameworks

Code meant become part of the extension.

*   [webext-options-sync (⭐147)](https://github.com/fregante/webext-options-sync) - Helps you manage and autosave your extension's options.
*   [webext-storage-cache (⭐80)](https://github.com/fregante/webext-storage-cache) - Map-like promised cache storage with expiration.
*   [webext-dynamic-content-scripts (⭐84)](https://github.com/fregante/webext-dynamic-content-scripts) - Automatically inject your `content_scripts` on custom domains.
*   [mozilla/webextension-polyfill (⭐2.6k)](https://github.com/mozilla/webextension-polyfill) - Polyfill to support the standardized promise based API in the `browser` namespace.
*   [@types/firefox-webext-browser](https://www.npmjs.com/package/@types/firefox-webext-browser) - Supplies TypeScript types for the `browser` namespace.
*   [redux-webext (⭐108)](https://github.com/ivantsov/redux-webext) - Uses Redux for managing the state of your WebExtension.
*   [ExtPay (⭐455)](https://github.com/Glench/ExtPay) - Take secure payments in extensions without needing to run a server backend.
*   [inject-react-anywhere (⭐42)](https://github.com/OlegWock/inject-react-anywhere) - Inject React components into 3rd party sites with convenient API and styles isolation.
*   [More… (⭐95)](https://github.com/fregante/webext-fun)

## Tools

Apps that help you manage your extensions.

*   [Chrome Webstore Upload (⭐378)](https://github.com/fregante/chrome-webstore-upload-cli) - Upload the extension to the Chrome Web Store via cli (or on Travis, automatically).
*   [mozilla/web-ext (⭐2.6k)](https://github.com/mozilla/web-ext) - Command line tool to help build, run, and test WebExtensions.
*   [chromepet (⭐31)](https://github.com/ZenHubIO/chromepet) - Get notified when your new version has been published.
*   [chrome-ext-downloader (⭐49)](https://github.com/jiripospisil/chrome-ext-downloader) - Download any extension on Chrome Web Store to see how they do it.
*   [chrome-store-api (⭐28)](https://github.com/acvetkov/chrome-store-api) - Chrome Web Store API wrapper.
*   [Chrome extension source viewer (⭐1.4k)](https://github.com/Rob--W/crxviewer) - WebExtension to view source code of extensions directly on the store.
*   [@wext/shipit (⭐127)](https://github.com/LinusU/wext-shipit) - Tool to automatically publish to Chrome Web Store, Mozilla Addons and Opera Addons.
*   [wext-manifest-loader (⭐24)](https://github.com/abhijithvijayan/wext-manifest-loader) - Webpack loader that lets you specify `manifest.json` properties to appear only in specific browsers.
*   [webextension-manifest-loader (⭐7)](https://github.com/jsmnbom/webextension-manifest-loader) - Webpack loader that loads browser tailored manifest.json. It also imports all importable properties, allowing you to have 'manifest.json' as your only webpack entry point.
*   [webpack-extension-reloader (⭐494)](https://github.com/rubenspgcavalcante/webpack-extension-reloader) - A Webpack plugin to automatically reload browser extensions during development.
*   [webpack-target-webextension (⭐43)](https://github.com/awesome-webextension/webpack-target-webextension) - Adds code-splitting support to WebExtensions build with Webpack.
*   [Extension.js (⭐3.5k)](https://github.com/cezaraugusto/extension.js) - Plug-and-play, zero-config, cross-browser extension development tool.

## Testing

*   [sinon-chrome (⭐434)](https://github.com/acvetkov/sinon-chrome) - Mocks the Chrome Extensions API for testing.
*   [addons-linter (⭐306)](https://github.com/mozilla/addons-linter) - Validate an extension against Mozilla's guidelines.
*   [webextensions-jsdom (⭐18)](https://github.com/stoically/webextensions-jsdom) - Load popup, sidebar and background with JSDOM based on the manifest.json.
*   [webextensions-api-fake (⭐16)](https://github.com/stoically/webextensions-api-fake) - In-memory WebExtensions API Fake Implementation (includes TypeScript types).
*   [webextensions-api-mock (⭐4)](https://github.com/stoically/webextensions-api-mock) - WebExtensions API as sinon stubs (includes TypeScript types).
*   [webextensions-schema (⭐3)](https://github.com/stoically/webextensions-schema) - Programmatically consume the WebExtensions Schema JSON files.

## Boilerplates

*   [browser-extension-template (⭐763)](https://github.com/fregante/browser-extension-template) - Barebones boilerplate with parcel, options handler and auto-publishing.
*   [create-webextension (⭐22)](https://github.com/rpl/create-webextension) - Yarn WebExtension generator.
*   [generator-web-extension (⭐292)](https://github.com/webextension-toolbox/generator-web-extension) - WebExtension generator that creates everything you need to get started with cross-browser web-extension development.
*   [WXT (⭐3.3k)](https://github.com/wxt-dev/wxt) - Next-gen framework for developing web extensions

## Sample Extensions

These are simple and modern WebExtensions repositories that could help you figure out where pieces go, including automatic deployment via Travis CI.

*   [npmhub (⭐753)](https://github.com/npmhub/npmhub)
*   [Hide Files on GitHub (⭐320)](https://github.com/sindresorhus/hide-files-on-github)
*   [mdn/webextension-examples (⭐4k)](https://github.com/mdn/webextensions-examples) - Various example extensions curated for the MDN documentation.

