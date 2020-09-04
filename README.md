# zsh-prompt
My custom prompt for zsh

## Format

```
user@host short-path [git-branch] [current-time] %
```

## Install

Clone this repo:
```
git clone https://github.com/garus-dev/zsh-prompt.git "$ZSH_CUSTOM/themes/garus-dev-prompt" 
```

Symlink ```garus-dev.zsh-theme``` to your oh-my-zsh custom themes directory:
```
ln -s "$ZSH_CUSTOM/themes/garus-dev-prompt/garus-dev.zsh-theme" "$ZSH_CUSTOM/themes/garus-dev.zsh-theme"
```

Set ZSH_THEME="garus-dev" in your ```.zshrc```.