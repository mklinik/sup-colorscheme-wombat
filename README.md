wombat
======

A [sup](http://supmua.org/) colorscheme based on [vim's
wombat](http://dengmao.wordpress.com/2007/01/22/vim-color-scheme-wombat/).

Wombat comes in two flavors: normal and inverted. Index mode looks the same in both: 

![index-mode screenshot](https://raw.github.com/mklinik/sup-colorscheme-wombat/master/screenshots/index-view.png "index-mode screenshot")

The thread-view mode in normal flavor uses color-on-gray message patinas, while inverted uses gray-on-color.

### Normal

![thread-view normal screenshot](https://raw.github.com/mklinik/sup-colorscheme-wombat/master/screenshots/thread-view.png "thread-view normal screenshot")

### Inverted

![thread-view inverted screenshot](https://raw.github.com/mklinik/sup-colorscheme-wombat/master/screenshots/thread-view-inverted.png "thread-view inverted screenshot")

### Usage

Copy the file to ~/.sup/colors.yaml

Requires running sup in a 256-color terminal.  On the screenshots you see
rxvt-unicode-256color with the proggy square font:

```
$ grep 'urxvt.*ont' ~/.Xdefaults 
urxvt.font: xft:ProggySquareTT:style=Regular:pixelsize=16:antialias=false:hinting=true
urxvt.boldFont: xft:ProggySquareTT:style=Regular:pixelsize=16:antialias=false:hinting=true
```
