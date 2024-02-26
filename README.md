# nvim-config

This is my nvim config, the config is based on **[NvChad](https://nvchad.com)** for the base configuration.

## Useful commands

 - `:MasonInstallAll`
 - `:TSInstall python`
 - `<leader> ch`
 -  `<ctrl> n`

## Install

**Linux**

```bash
git clone https://github.com/TheTreeSee/nvim-config ~/.config/nvim --depth 1 && nvim
```

**Windows**

```powershell
git clone https://github.com/TheTreeSee/nvim-config $ENV:USERPROFILE\AppData\Local\nvim --depth 1 && nvim
```

## Uninstall
**Linux**
```bash
rm -rf ~/.config/nvim
rm -rf ~/.local/share/nvim
```


**Windows**
```powershell
rm -Force ~\AppData\Local\nvim
rm -Force ~\AppData\Local\nvim-data
```

## Useful info

Default `<leader>` key is `<space>`

## Common errors

 - [nvim cant find C compiler](https://www.reddit.com/r/neovim/comments/14oozmu/neovim_cant_find_c_compiler/)
 - nvim isnt the latest version (at least v0.9.2)
