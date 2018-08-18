# Page Zsh Theme

_Page_ is a simple zsh theme with VCS support. The prompt shows 1 level of the current working directory, branch, and a color coded curved fat arrow.

The arrow color indicates version control status.
- No color indicates not in version controlled environment
- Blue indicates clean
- Yellow indicates dirty

![screenshot-hyper-ayu](screenshot.png)

## oh-my-zsh

### Installation

Run the [install script](install.sh):
```sh
source install.sh
```


### Usage

In `.zshrc`, change the `ZSH_THEME` to "page":
```
ZSH_THEME="page"
```


## Contribution

This is my personal zsh theme I maintain for myself. Feel free to fork!
