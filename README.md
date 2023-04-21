# kickstart.nvim

### Introduction

A Fork for kickstart.nvim

### Installation

Kickstart.nvim targets *only* the latest ['stable'](https://github.com/neovim/neovim/releases/tag/stable) and latest ['nightly'](https://github.com/neovim/neovim/releases/tag/nightly) of Neovim. If you are experiencing issues, please make sure you have the latest versions. (Neovim >= 0.8.0, beware ubuntu users!)

* Backup your previous configuration
* (Recommended) Fork this repo (so that you have your own copy that you can modify).
* Clone the kickstart repo into `$HOME/.config/nvim/` (Linux/Mac) or `~/AppData/Local/nvim/` (Windows)
  * If you don't want to include it as a git repo, you can just clone it and then move the files to this location
* Start Neovim (`nvim`) and allow `lazy.nvim` to complete installation.
* Restart Neovim
* :MasonInstall clangd
* :MasonInstall pyright
* :MasonInstall typescript-language-server
* **You're ready to go!**

Additional system requirements:
- Make sure to review the readmes of the plugins if you are experiencing errors. In particular:
  - [ripgrep](https://github.com/BurntSushi/ripgrep#installation) is required for multiple [telescope](https://github.com/nvim-telescope/telescope.nvim#suggested-dependencies) pickers.
- See as well [Windows Installation](#Windows-Installation)
