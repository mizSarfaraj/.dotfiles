# DOTFILES

---

## Content

- [Prerequisites](#Prerequisites)
- [Installation](#Installation)
- [Setup](#Setup)

## Prerequisites

To install these dotfiles you would need :<br>
[stow](https://www.gnu.org/software/stow/) <br>
[git](https://git-scm.com/)

## Installation

```
git clone git@github.com:RamizSarfaraj/.dotfiles.git $HOME/.dotfiles/
```

## Setup

```setup
cd ~/.dotfiles
stow */    #'/' ignore the README file while establishing symlinks
```

Or you could do induvidually for every configuration.

```example
stow zsh   # for zsh
stow Home  # for file in home directory
stow kitty   # for kitty configuration
```

---
