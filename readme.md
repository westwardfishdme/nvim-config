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

# Made up FAQ:
Below are just some made up bs FAQ questions. I know for some orgs they actually HAVE some FAQ, but does anyone
really ask these? Or are these just for end-user comfort? Who knows!

### Why upload this now?
Newer lazy packages and Mason LSPs kept breaking my nvim configuration, because I was running on a 3 year old install
for AstroNvim. Decided that if I'm gonna have to keep tinkering might as well share some dotfiles with y'all because
it's nice to see how other people set things up :)

### Why not just upload all of your config files in one place?
This repository might just turn into that, I just used it for neovim for now because lord knows how many config files
I have in my XDG config directory. 

Actually I just checked with `du -sh` and it's like 8GiB in total. You think I want to clean that up? No-- but you know
what I will do? Add them here when I feel comfortable sharing them. AND finding them in that monster of a directory.

### What's the meaning of "burn half as long twice as bright?"

```
Zeke: Half as long...
Cole: Twice as bright.
Zeke: I gotta try.
Cole: I know.
```

Ball knowers know that it came from the old PS3 game InFamous, it's the saying that Cole McGrath and Zeke Dunbar used to
tell each other as a "motto" of a sort. REAL ball knowers know that the quote is actually a quote from the 1982 film 
Blade Runner. It's a modification of Eldon Tyrell's quote:

>"The light that burns twice as bright burns half as long - and you have burned so very, brightly..."

But the proverb itself has been used around for quite some time; but no one knows where it really originates from.
It's rather ironic if you think about it long enough, because when I hear the proverb, I imagine a burning star.

Stars when they die, emit loads of cosmic radiation exploding in their supernovae. Their death is a violent, but beautiful 
thrashing of elements that then create the circumstances for new stars to form. A non-organic death to create the possibilities 
for organic life to form long after the star has disappeared from existence. 

Human life in a sense mimics this process, we live until our bodies can no longer function and then when we go, 
our bodies are then used by the Earth and other organisms to survive, and sustain the life. It's this never ending
cycle that will never end until the heat death of the universe. Biology and physics are not that far apart when you
think of in that manner; the universe always tries to achieve this balance in some way. This insanely complex, but simple
balancing act of matter and energy.

Life is cruel; but it is just and balanced. Therefore when a star that burns twice as bright, it will only burn half as long;
it is but the first law of thermodynamics-- the conservation of energy.

I have it as the title for vim because it's a reminder of my own existence. I won't be around forever; so when I go when the time comes, 
these projects will be around for someone to pick up; Like the star that gave life to other planets; I'll no longer be around, but there
are possibilities that what I've worked on will give others inspiration. 
