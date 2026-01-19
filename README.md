# 🌌 cyberdyne-port.nvim

A cyberpunk-inspired Neovim colorscheme based on the **Ghostty Cyberdyne** terminal theme.

Dark blue depths meet acid green highlights in this futuristic theme that brings the essence of cyberpunk aesthetics to your editor.

## Screenshots

![Code Example](screenshots/code-example.png)
![Dashboard](screenshots/dashboard.png)

## ✨ Features

- 🎨 Authentic Ghostty Cyberdyne color palette
- 🌳 Full TreeSitter support
- 🔍 LSP diagnostics integration
- 📦 Works with all major plugin managers
- 🎯 Support for popular plugins:
  - Telescope
  - Neo-tree / NvimTree
  - WhichKey
  - GitSigns
  - Dashboard / Alpha
  - Noice
  - Indent Blankline
  - and more!

## 🎨 Color Palette

| Color | Hex | Preview |
|-------|-----|---------|
| Background | `#151144` | ![#151144](https://via.placeholder.com/50x20/151144/151144.png) |
| Foreground | `#00ff92` | ![#00ff92](https://via.placeholder.com/50x20/00ff92/00ff92.png) |
| Black | `#080808` | ![#080808](https://via.placeholder.com/50x20/080808/080808.png) |
| Red | `#ff8373` | ![#ff8373](https://via.placeholder.com/50x20/ff8373/ff8373.png) |
| Green | `#00c172` | ![#00c172](https://via.placeholder.com/50x20/00c172/00c172.png) |
| Yellow | `#d2a700` | ![#d2a700](https://via.placeholder.com/50x20/d2a700/d2a700.png) |
| Blue | `#0071cf` | ![#0071cf](https://via.placeholder.com/50x20/0071cf/0071cf.png) |
| Magenta | `#ff90fe` | ![#ff90fe](https://via.placeholder.com/50x20/ff90fe/ff90fe.png) |
| Cyan | `#6bffdd` | ![#6bffdd](https://via.placeholder.com/50x20/6bffdd/6bffdd.png) |
| White | `#f1f1f1` | ![#f1f1f1](https://via.placeholder.com/50x20/f1f1f1/f1f1f1.png) |

## 📦 Installation

### [lazy.nvim](https://github.com/folke/lazy.nvim) (recommended)

```lua
{
  "followLemmi/cyberdyne-port.nvim",
  lazy = false,
  priority = 1000,
  config = function()
    vim.cmd([[colorscheme cyberdyne-port]])
  end,
}
```

### [packer.nvim](https://github.com/wbthomason/packer.nvim)

```lua
use {
  "followLemmi/cyberdyne-port.nvim",
  config = function()
    vim.cmd([[colorscheme cyberdyne-port]])
  end
}
```

### [vim-plug](https://github.com/junegunn/vim-plug)

```vim
Plug 'followLemmi/cyberdyne-port.nvim'

" In your init.vim or after plug#end()
colorscheme cyberdyne-port
```

### [pckr.nvim](https://github.com/lewis6991/pckr.nvim)

```lua
{
  "followLemmi/cyberdyne-port.nvim",
  config = function()
    vim.cmd([[colorscheme cyberdyne-port]])
  end
}
```

### [dein.vim](https://github.com/Shougo/dein.vim)

```vim
call dein#add('followLemmi/cyberdyne-port.nvim')

" After dein setup
colorscheme cyberdyne-port
```

## 🔧 Configuration

### Basic Usage

```lua
-- In your init.lua
vim.cmd([[colorscheme cyberdyne-port]])
```

### With AstroNvim

In your `~/.config/nvim/lua/plugins/astroui.lua`:

```lua
return {
  "AstroNvim/astroui",
  opts = {
    colorscheme = "cyberdyne-port",
  },
}
```

### With LazyVim

```lua
-- In ~/.config/nvim/lua/plugins/colorscheme.lua
return {
  {
    "followLemmi/cyberdyne-port.nvim",
  },
  {
    "LazyVim/LazyVim",
    opts = {
      colorscheme = "cyberdyne-port",
    },
  },
}
```

### With LunarVim

In your `~/.config/lvim/config.lua`:

```lua
lvim.colorscheme = "cyberdyne-port"
lvim.plugins = {
  { "followLemmi/cyberdyne-port.nvim" },
}
```

### With NvChad

In your `~/.config/nvim/lua/chadrc.lua`:

```lua
M.ui = {
  theme = "cyberdyne-port",
}

M.plugins = "custom.plugins"
```

And in `~/.config/nvim/lua/custom/plugins.lua`:

```lua
return {
  { "followLemmi/cyberdyne-port.nvim" },
}
```

## 🌟 Credits

This theme is a port of the [Ghostty](https://ghostty.org) Cyberdyne color scheme to Neovim.

## 📝 License

MIT License - see [LICENSE](LICENSE) for details

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## 🔗 Related

- [Ghostty Terminal](https://ghostty.org) - A fast, native, GPU-accelerated terminal emulator
---

Made with 💚 for the cyberpunk aesthetic
