# Neovim config

This is my neovim configuration, with a starting point in [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim). The config is pretty minimal as I don't use neovim as my primary code editor (that would be [Zed](https://github.com/zed-industries/zed)).

## Usage

Clone this repository into a folder based on your operating system. Possibly more up to date instructions can be found in [the kickstart.nvim README](https://github.com/nvim-lua/kickstart.nvim?tab=readme-ov-file#clone-kickstartnvim).

### Linux and Mac

```sh
git clone git@github.com:Kiwow/neovim-config.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

### Windows

If you're using `cmd.exe`:

```
git clone git@github.com:Kiwow/neovim-config.git "%localappdata%\nvim"
```

If you're using `powershell.exe`

```
git clone git@github.com:Kiwow/neovim-config.git "${env:LOCALAPPDATA}\nvim"
```
