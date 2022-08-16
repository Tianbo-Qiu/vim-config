## Vim Config

1. Install neovima or build from source

https://github.com/neovim/neovim/wiki/Building-Neovim

validate with `nvim --version`

2. Install a plugin manager

https://github.com/junegunn/vim-plug

3. Install tree-sitter

https://github.com/nvim-treesitter/nvim-treesitter

Tree-sitter parses a source file and builds a syntax tree for it on the fly.
Features are provided by "modules" and each module provides a distinct
tree-sitter based feature such as highlighting, indentation, or folding. Plugins
are also available.

_Install parsers for each language_

list info: `:TSInsatallInfo`
install a parser: `:TSInstall <language>`
update a parser: `:TSUpdate {language}`

_Enable features/modules_

list module info: `:TSModuleInfo`
enable: `:TSEnable`

4. Install coc.nvim

https://github.com/neoclide/coc.nvim

coc.nvim provides auto-completion, code navigation, etc.

Other included plugins

NERDTree: a file system explorer

https://github.com/preservim/nerdtree

fugitive.vim: git wrapper

https://github.com/tpope/vim-fugitive

5. Install FZF

a general-purpose fuzzy finder

https://github.com/junegunn/fzf

language servers

ccls: https://github.com/MaskRay/ccls/wiki

### Changes

Sun Aug 14 11:23:20 PDT 2022

    - Upgrade to  nvim 0.8.0
