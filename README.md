# Setup

## Install Nerd Font

Download JetBrainsMono Nerd font from [here](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/JetBrainsMono.zip).

Move the folder content to `~/.local/share/fonts/` and rebuild font cache with `fc-cache -fv`.

## Install Starship

Run the following command

```
curl -sS https://starship.rs/install.sh | sh
```

### Set Nerd Font Icons

Run the following command on the shell

```
starship preset nerd-font-symbols -o ~/.config/starship.toml
```

[Link](https://starship.rs/presets/nerd-font) for more info.

## (Optional) Disable conda env name on terminal

To disable conda enc name (like `(base)`) use the following command

```
conda config --set changeps1 false
```
