# Vim Repository

## Purpose

The purpose of this repository is to save and backup my regular Vim configuration.

## Why not Neovim?

Neovim, in my experience, was harder for me to set up, so I prefer Vim for its minimalism and simplicity.

---

# Setup

- [autocmds.vim](autocmds.vim) => Commands that run automatically at a certain time or event
- [mappings.vim](mappings.vim) => Configured keybindings
- [options.vim](options.vim) => Tweaks to the editor overall
- [statusline.vim](statusline.vim) => Separate statusline file
- [vimrc](vimrc) => Plain text `.vimrc` template; mainly sources and reads the files above

## How to Use

> Make sure to back up your previous .vimrc before using this configuration.
> But, this configuration's modularity makes it easier to add or remove to your Vim editor.

```bash
git clone https://github.com/stephenjamesada/.vim.git
cd .vim
cp -r vimrc ~/.vimrc # or wherever your .vimrc is
```
