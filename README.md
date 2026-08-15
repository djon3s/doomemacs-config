# Doom Emacs Config

My personal Doom Emacs configuration.

## Setup
```
git clone https://github.com/djon3s/doomemacs-config ~/.doom.d

 ~/.config/emacs/bin/doom sync
```

## Features

- Go development with LSP
- Custom test runner: `C-c l t t` runs test for function at point
- exec-path-from-shell for proper PATH on macOS

## Git alias

This repo is being tracked on sourcehut and github. 

To make life easier after clone in .git/config add the following two lines 

```
[include]
	path = ../.gitaliases
```
