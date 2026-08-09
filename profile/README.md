<p align="center">
  <a href="https://easybar.dev">
    <img src="https://raw.githubusercontent.com/easybar-app/docs/main/content/assets/icons/apple-touch-icon.png" width="96" height="96" alt="EasyBar logo">
  </a>
</p>

<h1 align="center">EasyBar</h1>

<p align="center">
  A lightweight, scriptable macOS status bar built with SwiftUI and Lua.
</p>

<p align="center">
  <a href="https://easybar.dev">Documentation</a> ·
  <a href="https://easybar.dev/getting-started/quick-start/">Quick start</a> ·
  <a href="https://easybar.dev/lua/overview/">Lua widgets</a> ·
  <a href="https://github.com/easybar-app/easybar/issues">Issues</a>
</p>

EasyBar combines native macOS widgets with a Lua runtime, installable widget packages, a shared
inbox, themes, AeroSpace integration, and a command-line interface for automation and diagnostics.

## Install

```sh
brew tap easybar-app/tap
brew install --cask easybar-app/tap/easybar
open -a EasyBar
```

See the [installation guide](https://easybar.dev/getting-started/installation/) for requirements,
upgrades, verification, and removal.

## Projects

| Project                                                             | Use it to                                                       |
| ------------------------------------------------------------------- | --------------------------------------------------------------- |
| [`easybar`](https://github.com/easybar-app/easybar)                 | Build the app, CLI, Lua runtime, and themes                     |
| [`docs`](https://github.com/easybar-app/docs)                       | Maintain and publish the documentation at easybar.dev           |
| [`homebrew-tap`](https://github.com/easybar-app/homebrew-tap)       | Install EasyBar, its helper agents, and WiFiSnitch via Homebrew |
| [`widgets`](https://github.com/easybar-app/widgets)                 | Browse and contribute official Lua widgets and libraries        |
| [`registry`](https://github.com/easybar-app/registry)               | Resolve package releases through the official discovery index   |
| [`widget-template`](https://github.com/easybar-app/widget-template) | Create, test, and release a standalone EasyBar widget           |

## Contribute

- Read the [development guide](https://easybar.dev/internals/development/) to contribute to EasyBar.
- Use the [widget template](https://github.com/easybar-app/widget-template) to start a package.
- Follow the [widget contribution guide](https://easybar.dev/lua/guides/contributing-widget/) to
  propose an official widget.

EasyBar is open source under the
[Apache License 2.0](https://github.com/easybar-app/easybar/blob/main/LICENSE).
