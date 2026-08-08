<p align="center">
  <a href="https://easybar.dev">
    <img src="https://raw.githubusercontent.com/easybar-app/easybar/main/docs/content/assets/icons/apple-touch-icon.png" width="96" height="96" alt="EasyBar logo">
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

| Repository                                                          | Purpose                                                 |
| ------------------------------------------------------------------- | ------------------------------------------------------- |
| [`easybar`](https://github.com/easybar-app/easybar)                 | The EasyBar app, CLI, Lua runtime, and documentation    |
| [`widgets`](https://github.com/easybar-app/widgets)                 | Official installable Lua widgets and reusable libraries |
| [`widget-registry`](https://github.com/easybar-app/widget-registry) | Package discovery and immutable release metadata        |
| [`widget-template`](https://github.com/easybar-app/widget-template) | Starting point for developing and releasing a widget    |
| [`homebrew-tap`](https://github.com/easybar-app/homebrew-tap)       | Homebrew distribution for EasyBar and its helper agents |

## Contribute

- Read the [development guide](https://easybar.dev/internals/development/) to contribute to EasyBar.
- Use the [widget template](https://github.com/easybar-app/widget-template) to start a package.
- Follow the [widget contribution guide](https://easybar.dev/lua/guides/contributing-widget/) to
  propose an official widget.

EasyBar is open source under the
[Apache License 2.0](https://github.com/easybar-app/easybar/blob/main/LICENSE).
