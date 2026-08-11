<p align="center">
  <a href="https://easybar.dev">
    <img src="https://raw.githubusercontent.com/easybar-app/docs/main/content/assets/icons/apple-touch-icon.png" width="96" height="96" alt="EasyBar logo">
  </a>
</p>

<h1 align="center">EasyBar</h1>

<p align="center">
  Lightweight, scriptable macOS menu bars built with SwiftUI and Lua.
</p>

<p align="center">
  <a href="https://easybar.dev">Documentation</a> ·
  <a href="https://easybar.dev/products/">Choose a product</a> ·
  <a href="https://easybar.dev/widget-store/catalog/">Widget Store</a> ·
  <a href="https://github.com/easybar-app/easybar/issues">Issues</a>
</p>

EasyBar provides a customizable full-width bar with native and Lua widgets. EasyBar Native keeps the
normal macOS menu bar and hosts Lua widgets as individual menu-bar items. Both use the same Lua API
and official widget packages.

## Install EasyBar

```sh
brew tap easybar-app/tap
brew install --cask easybar-app/tap/easybar
open -a EasyBar
```

## Projects

| Project                                                             | Purpose                                        |
| ------------------------------------------------------------------- | ---------------------------------------------- |
| [`easybar`](https://github.com/easybar-app/easybar)                 | Customizable full-width macOS bar              |
| [`easybar-native`](https://github.com/easybar-app/easybar-native)   | Lua widgets in the normal macOS menu bar       |
| [`easybar-kit`](https://github.com/easybar-app/easybar-kit)         | Shared Swift and Lua widget platform           |
| [`widgets`](https://github.com/easybar-app/widgets)                 | Official Lua widgets and libraries             |
| [`registry`](https://github.com/easybar-app/registry)               | Official package discovery index               |
| [`widget-template`](https://github.com/easybar-app/widget-template) | Starting point for standalone widget packages  |
| [`docs`](https://github.com/easybar-app/docs)                       | Unified documentation published at easybar.dev |
| [`homebrew-tap`](https://github.com/easybar-app/homebrew-tap)       | Homebrew distribution for EasyBar products     |

## Documentation

- [EasyBar quick start](https://easybar.dev/products/easybar/quick-start/)
- [EasyBar Native quick start](https://easybar.dev/products/easybar-native/quick-start/)
- [Lua widgets](https://easybar.dev/lua/overview/)
- [Create and contribute packages](https://easybar.dev/widget-store/create-and-contribute/)
- [Development](https://easybar.dev/internals/development/)

EasyBar is open source under the
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
