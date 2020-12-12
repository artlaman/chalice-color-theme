# Chalice color themes for [Visual Studio Code](http://code.visualstudio.com)

[![License: MIT](https://img.shields.io/badge/license-MIT-orange.svg)](https://github.com/artlaman/chalice-color-theme/blob/master/LICENSE)
[![Marketplace Version](https://vsmarketplacebadge.apphb.com/version/artlaman.chalice-color-theme.svg)](https://marketplace.visualstudio.com/items?itemName=artlaman.chalice-color-theme)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/artlaman.chalice-color-theme.svg)](https://marketplace.visualstudio.com/items?itemName=artlaman.chalice-color-theme)

Designed to facilitate the needs of those sneaking through hundreds of those themes available in the Extension Marketplace, shiny and ugly, unable to concentrate on just writing code. Recommended to use with [Chalice icon theme](https://marketplace.visualstudio.com/items?itemName=artlaman.chalice-icon-theme)

## Dark theme preview

<img src="https://github.com/artlaman/chalice-color-theme/raw/master/preview-dark.png" title="Chalice dark preview" />

## Light theme preview

<img src="https://github.com/artlaman/chalice-color-theme/raw/master/preview.png" title="Chalice light preview" />

## Whys

Chalice doesn’t:

- use font variations (italics, bold, etc.)
- make your eyes bleed

Chalice highlights only:

- strings
- numbers, symbols, keywords, Booleans
- comments
- global definitions

and doesn’t highlight anything else. Because it’s totally better this way. Motivated by the same reasons the Alabaster theme has. Yet while Nikita did great with syntax highlighting, Chalice focuses on other things like UI and nice color combinations, (also it has a dark mode option).

## Additionally

You can download color profiles for OS X Terminal.app for a more consistent experience here: [dark color profile](https://github.com/lysyi3m/macos-terminal-themes/blob/master/schemes/Chalice%20Dark.terminal), [light color profile](https://github.com/lysyi3m/macos-terminal-themes/blob/master/schemes/Chalice.terminal)

Consider using these settings to reduce visual noize:

```js
{
  "breadcrumbs.enabled": false,
  "editor.cursorSmoothCaretAnimation": true,
  "editor.minimap.enabled": false,
  "editor.renderLineHighlight": "gutter",
  "editor.smoothScrolling": true,
  "explorer.decorations.colors": false,
  "window.autoDetectColorScheme": true,
  "workbench.activityBar.visible": false,
  "workbench.editor.showIcons": false,
  "workbench.editor.tabSizing": "shrink",
  "workbench.preferredDarkColorTheme": "chalice-color-theme-dark",
  "workbench.preferredLightColorTheme": "chalice-color-theme-light",
  "workbench.statusBar.visible": false,
  "workbench.tree.indent": 10,
}
```

Or if you are wicked

```js
{
  "editor.occurrencesHighlight": false,
  "editor.suggestOnTriggerCharacters": false,
  "editor.parameterHints": false,
  "editor.quickSuggestions": false,
  "editor.renderIndentGuides": false,
  "workbench.preferredDarkColorTheme": "chalice-color-theme-dark-mono",
  "workbench.preferredLightColorTheme": "chalice-color-theme-light-mono",
}
```

## What to do next

- If you found something ugly and have an idea how to make it better please [create an issue](https://github.com/artlaman/chalice-color-theme/issues/new/choose) or submit a pull request.
- If everything's fine, you can [buy me a coffee](https://www.buymeacoffee.com/artlaman)!
