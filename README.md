# kickstart.nvim

[original repo](https://github.com/nvim-lua/kickstart.nvim/tree/master?tab=readme-ov-file)

## Installation

1. Install Neovim
2. Install External Dependencies

- Basic utils: `git`, `make`, `unzip`, C Compiler (`gcc`)
- [ripgrep](https://github.com/BurntSushi/ripgrep#installation)
- Clipboard tool (xclip/xsel/win32yank or other depending on the platform)
- A [Nerd Font](https://www.nerdfonts.com/): optional, provides various icons
  - if you have it set `vim.g.have_nerd_font` in `init.lua` to true

3. Install Kickstart

- Remove `lazy-lock.json`
- Clone kickstart.nvim

```sh
git clone https://github.com/dvsource/kickstart.nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

4. Post Installation
5. Start Neovim

```sh
nvim
```

- Use `:Lazy` to view the current plugin status.
- Hit `q` to close the window.

### Getting Started

[The Only Video You Need to Get Started with Neovim](https://youtu.be/m8C0Cq9Uv9o)

### FAQ

[Original Readme]([https://github.com/nvim-lua/kickstart.nvim/tree/master?tab=readme-ov-file](https://github.com/nvim-lua/kickstart.nvim/blob/master/README.md))


