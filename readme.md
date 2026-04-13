# Westwardfishdme's nvim configuration
Essentially what I use in my day to day nvim config. I use AstroNvim with Lazy/Mason.
Most things are pretty default-- with the exception of some theming options and a change
in the message that gets displayed by default. Enjoy.

## What's in it?
Mostly color themes, some changes to AstroCore, LaTeX live compilation via vimtex.

> Note: I use Zathura for reading pdfs, so by default it will use zathura, you can change this inside of `./nvim/init.lua`.
```lua
-- on line 22...
vim.g.vimtex_view_method = "zathura"
```

## Themes
I also included some other themes from the [Astrocommunity](https://docs.astronvim.com/recipes/colorscheme/) 
repository if you want to switch themes (as I almost always do).

Personally, I really enjoy `everforest`; the muted colors are soft on the eyes, and color palette is overall
really pretty to look at.
