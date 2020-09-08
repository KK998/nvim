# Nvim config

Basic setup is located in init.vim.

``` bash
sudo apt-get update -y && apt-get install neovim -y
cd ~/.config/nvim
git clone git@github.com:KK998/nvim.git
```

Check for CocList for all the extensions... add those you need!
init file already has some global default's.

## Adding extra extensions to the Coc.nvim:

``` vim
:CocInstall coc-json coc-html coc-python
```

Just list the extensions, check their docs if they need some [config]('https://github.com/neoclide/coc.nvim/wiki/Using-coc-extensions#implemented-coc-extensions').

For ease of use, you can make a new mapping for CocList -> extensions, symbols etc..

> [!NOTE]
> Coc.nvim documentation has many more conf's if you need. Add as necessary.
