<h1 align="center">NvChad</h1>

<div align="center">
	<a href="https://nvchad.github.io/">Home</a>
  <span> • </span>
    	<a href="https://nvchad.github.io/quickstart/install">Install</a>
  <span> • </span>
       	<a href="https://nvchad.github.io/contribute">Contribute</a>
  <span> • </span>
	<a href="https://github.com/NvChad/NvChad#gift_heart-support">Support</a>
  <span> • </span>
        <a href="https://nvchad.github.io/Features">Features</a>
  <p></p>
</div> 

<div align="center">
 
[![Super Linter](https://img.shields.io/github/workflow/status/NvChad/NvChad/Super-Linter/main?style=flat-square&logo=github&label=Build&color=8DBBE9)]()
<a href="https://github.com/NvChad/NvChad/blob/main/LICENSE"
        ><img
            src="https://img.shields.io/github/license/NvChad/NvChad?style=flat-square&logo=GNU&label=License&color=df967f"
            alt="License"
    />
[![Neovim Minimum Version](https://img.shields.io/badge/Neovim-0.8.2-blueviolet.svg?style=flat-square&logo=Neovim&color=90E59A&logoColor=white)](https://github.com/neovim/neovim)



  </div>

## Showcase

![neovim_config_screenshot](https://github.com/charudatta10/NeovimConfigV1/blob/main/neovim_config_screenshot.png))


## What is it?

- config is a fork of NvChad Neovim config written in Lua aiming to provide a base configuration with very beautiful UI and blazing fast startuptime (around 0.02 secs ~ 0.07 secs). It tweaks UI plugins such as Telescope, Nvim-Tree, Bufferline, etc well to provide an aesthetic UI experience. 

- Lazy loading is done 93% of the time, meaning that plugins will not be loaded by default, they will be loaded only when required also at specific commands, events etc. This lowers the startuptime.

- It's supposed to be used as a "base" config, so users can tweak the defaults well, can also remove the things they don't like in the default config and build their config on top of it. Users can tweak the entire default config while staying in their custom config (lua/custom dir). This is the control center of the user's config and gitignored so the users can stay update to-date with NvChad's latest config (main branch) while still controlling it with their chadrc (file that controls entire custom dir)



## UI related plugins used

<details><summary> <b>Images (Click to expand!)</b></summary>

<h3> Nvim-tree.lua </h3>

Fast file tree:

<kbd><img src="https://github.com/NvChad/nvchad.github.io/blob/src/static/img/features/nvimtree.png"></kbd><hr>

<h3> Telescope-nvim </h3>

A fuzzy file finder, picker, sorter, previewer and much more:

<kbd><img src="https://github.com/NvChad/nvchad.github.io/blob/src/static/img/features/tel.png"></kbd><hr>

<h3> Indent-blankline.nvim </h3>

Adds indentline:

<kbd><img src="https://github.com/NvChad/nvchad.github.io/blob/src/static/img/features/blanklineNvim.png"></kbd><hr>

<h3> Our own statusline written from scratch  </h3>

[NvChad UI](https://github.com/NvChad/ui)

<kbd><img src="https://github.com/NvChad/nvchad.github.io/blob/src/static/img/features/statusline.png"></kbd><hr>
<kbd><img src="https://github.com/NvChad/nvchad.github.io/blob/src/static/img/features/statusline_modes.png"></kbd><hr>

<h3> Tabufline (our own pertab bufferline) </h3>

<kbd><img src="https://github.com/NvChad/nvchad.github.io/blob/src/static/img/features/tabufline1.png"></kbd><hr>
<kbd><img src="https://github.com/NvChad/nvchad.github.io/blob/src/static/img/features/tabufline2.png"></kbd><hr>
<kbd><img src="https://github.com/NvChad/nvchad.github.io/blob/src/static/img/features/tabufline3.png"></kbd><hr>

<h3> Nvim-web-devicons </h3>

Lua fork of Vim Devicons which offers more file icon customisability:

<kbd><img src="https://github.com/NvChad/nvchad.github.io/blob/src/static/img/features/devicons.png"></kbd><hr>

<h3> Nvim-treesitter </h3

NeoVim Treesitter configurations and abstraction layer. We mostly use this for syntax highlighting. The pretty syntax highlighting you see in all of our screenshots has gotten possible due to treesitter

</details>

## Plugins list

- Many beautiful themes, theme toggler by [our base46 plugin](https://github.com/NvChad/base46)
- Inbuilt terminal toggling & management with [Nvterm](https://github.com/NvChad/nvterm)
- NvChad updater, hide & unhide terminal buffers with [NvChad extensions](https://github.com/NvChad/extensions)
- Lightweight & performant ui plugin with [NvChad UI](https://github.com/NvChad/ui)
- File navigation with [nvim-tree.lua](https://github.com/kyazdani42/nvim-tree.lua)
- Managing tabs, buffers with [bufferline.nvim](https://github.com/akinsho/bufferline.nvim)
- Beautiful and configurable icons with [nvim-web-devicons](https://github.com/kyazdani42/nvim-web-devicons)
- Git diffs and more with [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim) 
- NeoVim Lsp configuration with [nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) and [mason.nvim](https://github.com/williamboman/mason.nvim)
- Autocompletion with [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)
- File searching, previewing image and text files and more with [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim).
- Syntax highlighting with [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
- Autoclosing braces and html tags with [nvim-autopairs](https://github.com/windwp/nvim-autopairs)
- Indentlines with [indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim)
- Useful snippets with [friendly snippets](https://github.com/rafamadriz/friendly-snippets) + [LuaSnip](https://github.com/L3MON4D3/LuaSnip).
- Popup mappings keysheet [whichkey.nvim](https://github.com/folke/which-key.nvim)

 




## Credits

- https://github.com/NvChad/NvChad
