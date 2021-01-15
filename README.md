# vim-anywhere

Fork of [vim-anywhere](https://github.com/cknadler/vim-anywhere)

Uses nvim instead of gvim.

![demo](assets/demo.gif)

Once [invoked](#keybinding), vim-anywhere will open a buffer. Close it and its
contents are copied to your **clipboard** and your previous application is
refocused.

## Installation

**Linux:**

- Gnome (or a derivative)
- nvim

#### Install

```bash
curl -fsSL https://raw.github.com/gitx-xx/vim-anywhere/master/install | bash
```

#### Update

```bash
~/.vim-anywhere/update
```

#### Uninstall

```bash
~/.vim-anywhere/uninstall
```

**Linux:** ( default = `ctrl+alt+v` )

_Gnome_

```bash
$ gconftool -t str --set /desktop/gnome/keybindings/vim-anywhere/binding <custom binding>
```
