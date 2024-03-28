# Installing Sparky to your terminal emulator

Although the recommended way to install Sparky as your terminal theme is through [Gogh](https://gogh-co.github.io/Gogh/), its understandable that sometimes you'd just prefer modifying your terminal's config file or installing things manually. Each to their own.

Note that the following configs and files were auto-generated using [terminal.sexy](https://terminal.sexy), and that you might need to modify things a bit so you can actually use the theme on your terminal depending on how you have it configured.

## Alacritty
To install Sparky in Alacritty, you need to move `sparky.toml` to your `.config/alacritty/themes` folder.

```sh
mv src/sparky.toml ~/.config/alacritty/themes
```

And add the following line to your `alacritty.toml` file.

```t
import = [
    "~/.config/alacritty/themes/sparky.toml"
]
```

## GNOME Terminal
To install Sparky in GNOME Terminal, you just need to need to run `sparky_gterm.sh`.

We all hate you GTerm, shame you're one of the best emulators.

## Guake
Run the following commands.

```
gconftool-2 -s -t string /apps/guake/style/background/color '#07072b2b3131'
gconftool-2 -s -t string /apps/guake/style/font/color '#f4f4f5f5f0f0'
gconftool-2 -s -t string /apps/guake/style/font/palette '#212123232222:#ffff58585d5d:#7878d6d64b4b:#fbfbdddd4040:#46469898cbcb:#d5d59e9ed7d7:#2d2dccccd3d3:#dedee6e6dede:#4b4b4f4f5454:#ffff72727676:#8e8edddd6565:#f6f6ebeb6161:#6969b3b3e7e7:#f9f99f9fc9c9:#0000c1c1d5d5:#d9d9e1e1e2e2'
```

## iTerm2
*Instructions taken from [iterm2colorschemes.com](https://iterm2colorschemes.com)*

Launch iTerm 2.
Type CMD+i
Navigate to Colors tab
Click on Load Presets
Click on Import
Select sparky.itermcolors
Click on Load Presets and choose a color scheme

## Konsole
To install Sparky in Konsole, copy `sparky.colorscheme` into your `~/.local/share/konsole/` folder, reload Konsole, go to **Settings > Manage Profiles** and click on **New**, open the **Appearance** tab and select *Sparky*.

## Linux console
Add `sparky.sh` to your `.bashrc` or whatever thing your shell uses at startup. Congrats.

## Terminal.app
To install Sparky in Terminal.app, you need to go to **Preferences > Profiles**, click on the gear icon, select **Import**, and select `sparky.terminal`.

## Tilix/Black Box
Both Tilix and Black Box use the same JSON format for themes, and installation is pretty much identical.

For Tilix, run:
```sh
mv sparky.json ~/config/tilix/schemes/
```

For Black Box, run:
```sh
mv sparky.json ~/.var/app/com.raggesilver.BlackBox/data/blackbox/schemes/
```

## XFCE4 Terminal
Copy `sparky.theme` to `~/.local/share/xfce4/terminal/colorschemes/`.

## XResources
There are multiple ways to install Sparky for XResources, you can either do it:

### The Terminator Way**
Copy&paste the contents of `sparky.xresources` into your `~/.Xresources` file, and reload your settings with `xrdb`.

### The `#include` Way**
Move `sparky.xresources` anywhere you want, for this example we'll use `~/.config/`, and add the following line to your `~/.Xresources` file.

```
#include "~/.config/sparky.xresources"
```