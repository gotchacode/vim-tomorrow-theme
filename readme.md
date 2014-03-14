# Vim Tomorrow Theme

This is a vim only project for the awesome [Tomorrow theme](https://github.com/chriskempson/tomorrow-theme). I couldn't find any Vim specific repo which eases the install using Bundles, NeoBundles etc.


## Installation:

In order to install the theme, add the lines on your `.vimrc`:

```vimL
" Add bundle for Tomorrow theme
Bundle 'vinitkumar/vim-tomorrow-theme'
```
and then do this:

```bash
vim +BundleInstall +qall
```

It will install Tomorrow theme colors in your vim configuration. Now, add the colorscheme to your `.vimrc` and you are good to go:

```vimL
set background=light
colorscheme Tomorrow  
let g:colors_name="Tomorrow"
```

## Credits:

Full credit goes to [Chris Kempson](https://github.com/chriskempson/tomorrow-theme) for creating the Tomorrow theme.
