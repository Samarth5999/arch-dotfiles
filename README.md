# Samarth's Arch Dotfiles

This directory contains the dotfiles for my system

## Requirements

### Git

```
pacman -S git
```

### Stow

```
pacman -S stow
```

## Setup

1. Create a folder in the home directory
```
mkdir ${HOME}/dotfiles
```


2. Move the dot files from home to this folder. For example:
```
mv .zshrc ~/dotfiles
```

3. Run 
```
stow .
```
###### Maintain the directory structure of the home directory i.e. if a file normally resides at the top level of the home directory, it would go into the top level of the program's subdirectory.


