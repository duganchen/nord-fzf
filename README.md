# nord-fzf

A [Nord colour palette](https://www.nordtheme.com/) for the fzf command-line fuzzy finder tool.

These are the same colors used by Igloo: https://github.com/arcticicestudio/igloo/blob/master/snowblocks/zsh/pkgs/fzf/env.zsh

## Installation

Note: this works best when your terminal is also set to use a Nord colour palette. For example:

* [Nord iTerm2](https://github.com/arcticicestudio/nord-iterm2.git)
* [nord-kitty](https://github.com/connorholyday/nord-kitty)

Add the following your .(zsh|bash)rc configuration to set the colours used by fzf.

```
export FZF_DEFAULT_OPTS=$FZF_DEFAULT_OPTS'
    --color bg:#2e3440,bg+:#4c566a,fg:#e5e9f0
    --color fg+:#eceff4,hl:#88c0d0,hl+:#81a1c1
    --color preview-bg:#2e3440,preview-fg:#e5e9f0
    --color border:#4c566a,gutter:#3b4252,header:#88c0d0
    --color info:#88c0d0,marker:#88c0d0,pointer:#81a1c1
    --color prompt:#88c0d0,spinner:#88c0d0'
```
