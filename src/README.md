# Installing Sparky in your terminal emulator

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
Run `sparky_guake.sh`.

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

## MinTTY
Follow the instructions from [this gist](https://gist.github.com/mohnish/fbdb87bd8f5c7ecc46de519fbdd4b68c) because nobody fucking knows how to install a theme in MinTTY.

## PuTTY
Follow the instruction from [this repository](https://gist.github.com/mohnish/fbdb87bd8f5c7ecc46de519fbdd4b68c).

## Terminal.app
To install Sparky in Terminal.app, you need to go to **Preferences > Profiles**, click on the gear icon, select **Import**, and select `sparky.terminal`.

## Terminator
To install Sparky in Terminator... just copy&paste the contents of `sparky.config` into your `~/.config/terminator/config` file, or yeet it all together and do

```sh
mv -f sparky.config ~/.config/terminator/config
```

## Termite
Same as with Terminator, copy&paste the contents of `sparky.termite-theme` into your `~/.config/termite` folder, or ball and do
```sh
mv -f sparky.termite-theme ~/config/termite/config
```

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

## XShell
If you use this obscure as fuck thing, you probably already know how.

## XResources
There are multiple ways to install Sparky for XResources, you can either do it:

### The Terminator Way**
Copy&paste the contents of `sparky.xresources` into your `~/.Xresources` file, and reload your settings with `xrdb`.

### The `#include` Way**
Move `sparky.xresources` anywhere you want, for this example we'll use `~/.config/`, and add the following line to your `~/.Xresources` file.

```
#include "~/.config/sparky.xresources"
```