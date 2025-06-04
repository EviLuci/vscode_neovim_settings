# VSCode Neovim Settings & Keymaps

This repository contains my personal VSCode settings and keybindings for integrating Neovim with VSCode using the `vscode-neovim` extension, along with `harpoon` and `which-key` for some quality of life improvements.

![VSCode](https://github.com/EviLuci/vscode_neovim_settings/blob/main/assets/vscode_whichkey.png)

![VSCode](https://github.com/EviLuci/vscode_neovim_settings/blob/main/assets/vscode_with_file_explorer.png)

This setup is for those who:

- Use Neovim personally but prefer VSCode for professional collaboration.
- Want to replicate Neovim-like keybindings in VSCode without sacrificing its default behavior.
- Prefer minimal UI customization to keep VSCode familiar for teams.

> _Note: This is not a VSCode setup that's heavily customized to be like neovim. Honestly, I don't see a point in trying to make `VSCode` look and feel like `Neovim`. This is an attempt to create a simple productive workflow in `VSCode` that's similar to my `Neovim` setup._

## Why This Setup?

I just started using Neovim (with [LazyVim](https://lazyvim.org/)) mostly for personal work or projects, but VSCode is more common in workplace settings, so I still prefer using VScode for professional collaboration. The insert mode is basically just default VSCode, so anybody can use it like they usually do while I am able to have familiar neovim like environment that works just fine.

## Extensions
To fully utilize this setup, install the following extensions:

- [VSCode Neovim](https://github.com/vscode-neovim/vscode-neovim) - Enables Neovim as the backend for VSCode.
- [VSpaceCode - Which Key](https://github.com/VSpaceCode/vscode-which-key) - Provides a popup displaying available keybindings.
- [vscode-harpoon](https://github.com/tobias-z/vscode-harpoon) - A vscode extension inspired by the neovim plugin Harpoon created by The Primeagen

> _Note: `vscode-neovim` is the only essential plugin required for this setup. `whichkey` and `harpoon` are just needed for some quality of life improvements. You can setup similar keybinds without `whichkey` extension as well._

## Installation
1. Install [Neovim](https://neovim.io/) and ensure it is available in your system's PATH.
2. Install VSCode and the required extensions listed above.
3. Apply the settings and keybindings to your VSCode configuration.

## Neovim Plugins
I use lazyvim extras `vscode` extension that is also recommended in the `vscode-neovim` official github to use neovim specific plugins that doesn't interfere with default VSCode. It's not perfect but for my use-case it works just fine. You can take a look at my neovim config as well.

- [EviLuci's Neovim Config](https://github.com/EviLuci/dotfiles/tree/main/.config/nvim)