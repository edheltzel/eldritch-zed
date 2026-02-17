<p align="center">
  <img src="https://raw.github.com/eldritch-theme/eldritch/master/assets/logo/logo.png" width="150" />
</p>

# Eldritch for [Zed](https://zed.dev)

> A community-driven dark theme inspired by Lovecraftian horror.

Ported from [eldritch.nvim](https://github.com/eldritch-theme/eldritch.nvim) with Neovim-matched syntax highlighting across 200+ languages.

For more information, see the main [Eldritch](https://github.com/eldritch-theme/eldritch) theme repository.

## Variants

| Variant | Description |
|---------|-------------|
| **Eldritch** | Default palette -- vibrant accents on dark backgrounds |
| **Eldritch Dark** | Official darker palette from `eldritch.nvim` -- deeper backgrounds with desaturated accents |
| **Eldritch Deeper** | Deeper backgrounds with the original vibrant accent colors |

## Showcase

| | |
|:---:|:---:|
| ![HTML with inline JS and CSS dark mode script](images/html-dark-mode-script.png) | ![JSON package.json for a SvelteKit project](images/json-package.png) |
| HTML — Dark mode script | JSON — package.json |
| ![TypeScript Supabase SSR server hooks](images/typescript-supabase-hooks.png) | ![CSS with nested rules and custom properties](images/css-nested-rules.png) |
| TypeScript — Supabase SSR hooks | CSS — Nested rules and custom properties |
| ![TypeScript Vite configuration](images/typescript-vite-config.png) | ![TSX React component with Tailwind classes](images/tsx-react-component.png) |
| TypeScript — Vite config | TSX — React component with Tailwind |
| ![TSX React component in Eldritch Dark variant](images/tsx-react-component-dark.png) | ![C++ split pane with mouse events and parser macros](images/cpp-split-pane.png) |
| TSX — React component (Dark variant) | C++ — Split pane with parser macros |
| ![C++ JSON config and fish terminal in multi-pane layout](images/cpp-json-terminal.png) | |
| C++ / JSON / Terminal — Multi-pane layout | |

## Installation

### From Zed Extensions (Recommended)

1. Open Zed
2. Open the Extensions panel (`cmd+shift+x`)
3. Search for "Eldritch"
4. Click **Install**
5. Open Settings (`cmd+,`) and set your theme:

```json
{
  "theme": {
    "mode": "dark",
    "dark": "Eldritch"
  }
}
```

### Manual Installation

1. Clone this repository
2. Copy `themes/eldritch.json` to `~/.config/zed/themes/`
3. Restart Zed and select the theme from Settings

## Color Palette

| Color | Default | Dark | Hex (Default) |
|-------|---------|------|---------------|
| Background | ![#212337](https://placehold.co/16x16/212337/212337) | ![#171928](https://placehold.co/16x16/171928/171928) | `#212337` / `#171928` |
| Foreground | ![#ebfafa](https://placehold.co/16x16/ebfafa/ebfafa) | ![#d8e6e6](https://placehold.co/16x16/d8e6e6/d8e6e6) | `#ebfafa` / `#d8e6e6` |
| Cyan | ![#04d1f9](https://placehold.co/16x16/04d1f9/04d1f9) | ![#0396b3](https://placehold.co/16x16/0396b3/0396b3) | `#04d1f9` / `#0396b3` |
| Green | ![#37f499](https://placehold.co/16x16/37f499/37f499) | ![#2dcc82](https://placehold.co/16x16/2dcc82/2dcc82) | `#37f499` / `#2dcc82` |
| Purple | ![#a48cf2](https://placehold.co/16x16/a48cf2/a48cf2) | ![#8b75d9](https://placehold.co/16x16/8b75d9/8b75d9) | `#a48cf2` / `#8b75d9` |
| Pink | ![#f265b5](https://placehold.co/16x16/f265b5/f265b5) | ![#d154a1](https://placehold.co/16x16/d154a1/d154a1) | `#f265b5` / `#d154a1` |
| Red | ![#f16c75](https://placehold.co/16x16/f16c75/f16c75) | ![#cc5860](https://placehold.co/16x16/cc5860/cc5860) | `#f16c75` / `#cc5860` |
| Yellow | ![#f1fc79](https://placehold.co/16x16/f1fc79/f1fc79) | ![#ccd663](https://placehold.co/16x16/ccd663/ccd663) | `#f1fc79` / `#ccd663` |
| Orange | ![#f7c67f](https://placehold.co/16x16/f7c67f/f7c67f) | ![#d4a666](https://placehold.co/16x16/d4a666/d4a666) | `#f7c67f` / `#d4a666` |

> **Eldritch Deeper** uses the darker backgrounds with the default (vibrant) accent colors.

## Disabling Italics

Zed supports per-token style overrides via `experimental.theme_overrides` in your settings. To disable italics without switching themes:

```json
{
  "experimental.theme_overrides": {
    "syntax": {
      "comment": { "font_style": "normal" },
      "comment.doc": { "font_style": "normal" }
    }
  }
}
```

## License

[MIT](LICENSE)
