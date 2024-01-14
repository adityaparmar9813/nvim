# Vim Configuration

## Prerequisites

Before using this Vim configuration, make sure you have the following prerequisites installed:

1. **Neovim:** Ensure that you have Neovim installed with a version equal to or greater than v0.7.0.

2. **Packer:** Packer is used as the plugin manager for this configuration. You can install it by running the following command:

    ```bash
    git clone --depth 1 https://github.com/wbthomason/packer.nvim ~/.local/share/nvim/site/pack/packer/start/packer.nvim
    ```

## Installation

1. Clone this repository into your `.config` folder inside your home directory:

    ```bash
    git clone https://github.com/adityaparmar9813/nvim.git ~/.config/nvim
    ```

2. Traverse to `lua/adityaparmar/packer.lua` and source the file to ensure everything is set up correctly.

3. Run `PackerSync` to download the required dependencies. This will install the plugins specified in the configuration.

4. Optionally, you can run `lua ColorMyPencils` to keep your existing terminal colors. Note that this will be removed every time you run `PackerSync`.

## Features

This Vim configuration comes with the following features and plugins:

- **Telescope:** A highly extensible fuzzy finder.

- **RosePine:** A color scheme for Vim.

- **Tresitter:** Syntax trees for highlighting, indenting, and more.

- **Harpoon:** A navigation and session management plugin.

- **Undotree:** Visualize and navigate through your undo tree.

- **Vim Fugitive:** Git integration.

- **LSP (lsp_zero):** Language Server Protocol support.

- **Dashboard:** A start page for Neovim.

- **Vim Commentary:** Commenting plugin.

- **Nerdtree:** File system explorer.

- **BufferTerm:** Terminal in a buffer.

- **Vim-Airline:** A lightweight status/tabline.

- **Co-pilot:** Assists in writing code.

- **Tag and Bracket Closer (DelimitMate):** Automatic closing of tags and brackets.

## Screenshots

![Screenshot 1](https://drive.google.com/uc?export=view&id=1fm-qvymUoYNLsUbnlVWf4FOmlmlcn1vb)
*Maintaining original terminal color*

![Screenshot 2](https://drive.google.com/uc?export=view&id=18PlpYU0_MtL33uSog-QMzGGft1ZMAiyO)
*Rosepine Telescope*

![Screenshot 3](https://drive.google.com/uc?export=view&id=1LLvEr__NJeuEKPBDhws8IX0oMiucB7i2)
*Running PackerSync*

...

Feel free to customize and contribute to make this Vim configuration even more awesome!
