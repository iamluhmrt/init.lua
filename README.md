# Neovim Config (`init.lua`)

A minimalist and modern Neovim setup using Lua and [lazy.nvim](https://github.com/folke/lazy.nvim) as plugin manager.

This config includes:

- 🌈 `catppuccin` – Beautiful theme  
- 📊 `lualine` – Statusline  
- 📁 `neo-tree` – File explorer  
- 🔍 `telescope` – Fuzzy finder  
- 🌲 `treesitter` – Better syntax highlighting  
- 🧩 Managed by `lazy.nvim`

> ✅ A great starting point for Arch Linux users who want a fast and clean Neovim config.

## 🛠 Folder Structure

~/.config/nvim/<br>
├── init.lua <br>
├── lazy-lock.json <br>
├── lua/ <br>
│ ├── plugins/ <br>
│ │ ├── catppuccin.lua <br>
│ │ ├── lualine.lua <br>
│ │ ├── neo-tree.lua <br>
│ │ ├── telescope.lua <br>
│ │ ├── treesitter.lua <br>
│ ├── plugins.lua <br>
│ └── vim-options.lua <br>


## 🚀 Getting Started

```bash
# Clone this repo into your Neovim config directory
git clone https://github.com/iamluhmrt/init.lua.git ~/.config/nvim

# Open Neovim and install plugins (if using Packer)
nvim
# Then inside Neovim, run:
:PackerSync

# Open Neovim
nvim
