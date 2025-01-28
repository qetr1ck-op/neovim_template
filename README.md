# My AstroNvim Template

A template for getting started with [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```

#### Clone the repository

```shell
git clone https://github.com/qetr1ck-op/neovim_template ~/.config/nvim
```

#### Start Neovim

```shell
nvim
```

#### Setup MacOS

Dissable unwanted latter accents pop-up:
```shell
defaults write -g ApplePressAndHoldEnabled -bool false
```

Change keybord sensivity in settings

## 🏋🏼 Commands / Lifehacks

Toggle hidden files in `neo-tree`:
```shell
Shift + h
```

[Find and replace in file](https://aaronbos.dev/posts/find-and-replace-neovim):
```shell
:[range]s/<string-to-find>/<string-to-replace>/[flags]

:%s/foo/bar/g
```

[Find and replace globaly](https://www.youtube.com/watch?v=9JCsPsdeflY):
```shell
// telescope find a word
leader + f + w

// pass to quick link
ctrl + q

:cfdo :%s/foo/bar/g | update
```

[Mappings](https://docs.astronvim.com/mappings/#terminal-mappings):
- open lazygit - `Leader + tl`
