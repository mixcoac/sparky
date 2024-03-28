# Sparky
![Image of two Black Box terminals using Sparky, displaying the commands pfetch and colours each as a demonstration. Font used is Intel One Mono, and a custom edit of The Spark's album cover is used as the wallpaper.](ast/sc.png)

Sparky is a colour palette/theme inspired by Enter Shikari's [The Spark](https://album.link/mx/i/1263896001) made with accessibility and PMS compliance in mind. It features a range of 28 colours, and resembles palettes like Solarized or Nord.

Its palette was swatched from Enter Shikari album covers (TS and NiR&EiP), completed using a harmonic colour wheel, adjusted for contrast balance; and accessibility for colourblind users, and then matched to their closest Pantone equivalents.

Note that for some specific types of colourblindness, distinguishing between main and bright variants of colours may be more complicated.

Sparky averages a [WCAG 2.1](https://www.w3.org/TR/WCAG21/#contrast-minimum) contrast rating of 7.5:1 (AAA).

## Palette
Sparky has in total 28 colours, 8 "main", 8 "bright", 5 "background", 5 "foreground" and 2 blacks.

PMS | Hex | 🎨 | WCAG
---|---|---|---
178 C | `#FF585d` | ![#FF585D](https://placehold.co/15x15/f03c15/f03c15.png) | AA/4.9
805 C | `#FF7276` | ![#FF7276](https://placehold.co/15x15/FF7276/FF7276.png) | AA/5.7
1495 C | `#FF8F1C` | ![#FF8F1C](https://placehold.co/15x15/FF8F1C/FF8F1C.png) | AA/6.6
1375 C | `#FF9E1B` | ![#FF9E1B](https://placehold.co/15x15/FF9E1B/FF9E1B.png) | AAA/8.2
7488 C | `#78D64B` | ![#78D64B](https://placehold.co/15x15/78d64b/78d64b.png) | AAA/9.1
7487 C | `#8EDD65` | ![#8EDD65](https://placehold.co/15x15/8EDD65/8EDD65.png) | AAA/9.1
114 C | `#FBDD40` | ![#FBDD40](https://placehold.co/15x15/FBDD40/FBDD40.png) | AAA/11.1
100 C | `#F6EB61` | ![#F6EB61](https://placehold.co/15x15/F6EB61/F6EB61.png) | AAA/12.1
[319 C](https://x.com/ENTERSHIKARI/status/1200107247973609473?s=20) | `#2DCCD3` | ![#2DCCD3](https://placehold.co/15x15/2DCCD3/2DCCD3.png) | AAA/7.6
3115 C | `#00C1D5` | ![#00C1D5](https://placehold.co/15x15/00C1D5/00C1D5.png) | AA/6.9
7688 C | `#4698CB` | ![#4698CB](https://placehold.co/15x15/4698CB/4698CB.png) | AA/4.7
292 C | `#69B3E7` | ![#69B3E7](https://placehold.co/15x15/69B3E7/69B3E7.png) | AA/6.6
7438 C | `#D59ED7` | ![#D59ED7](https://placehold.co/15x15/D59ED7/D59ED7.png) | AA/6.9
210 C | `#F99FC9` | ![#F99FC9](https://placehold.co/15x15/F99FC9/F99FC9.png) | AAA/7.7
10367 C | `#9B704D`| ![#9B704D](https://placehold.co/15x15/9B704D/9B704D.png) | Fail/3.4
4715 C | `#956C58` | ![#956C58](https://placehold.co/15x15/956C58/956C58.png) | Fail/3.3
546 C | `#072B31` | ![#072B31](https://placehold.co/15x15/072B31/072B31.png) | Fail/1.0
547 C | `#00313C` | ![#00313C](https://placehold.co/15x15/00313C/00313C.png) | Fail/1.08
547 CP | `#003C46` | ![#003C46](https://placehold.co/15x15/003C46/003C46.png) | Fail/1.24
309 C | `#003B49` | ![#003B49](https://placehold.co/15x15/003B49/003B49.png) | Fail/1.2
7705 C | `#00778B` | ![#00778B](https://placehold.co/15x15/00778B/00778B.png) | Fail/2.8
FFFFF | `#FFFFFF` | ![#FFFFFF](https://placehold.co/15x15/FFFFFF/FFFFFF.png) | AAA/15.0
P 179-1 | `#F5F5F1` | ![#F5F5F1](https://placehold.co/15x15/F5F5F1/F5F5F1.png) | AAA/13.7
11-0601 Tcx| `#F4F5F0` | ![#F4F5F0](https://placehold.co/15x15/F4F5F0/F4F5F0.png) | AAA/13.7
141-9 C | `#DEE6DE` | ![#DEE6DE](https://placehold.co/15x15/DEE6DE/DEE6DE.png) | AAA/11.8
7541 C | `#D9E1E2` | ![#D9E1E2](https://placehold.co/15x15/D9E1E2/D9E1E2.png) | AAA/11.3
7540 C | `#4B4F54` | ![#4B4F54](https://placehold.co/15x15/4B4F54/4B4F54.png) | Fail/1.8
419 C | `#212322` | ![#212322](https://placehold.co/15x15/212322/212322.png) | Fail/1.05

## Install
Sparky was planned as only a colour palette to build themes from, so there aren't any "official" Sparky themes.

However, Sparky themes are available in a few odd ways, mainly for terminals.

### Terminals

#### Gogh (recommended)
[Gogh](https://gogh-co.github.io/Gogh/) is a repository of themes that can be installed running a single command and picking a theme. You can find Sparky there.

```
bash -c  "$(wget -qO- https://git.io/vQgMr)"
```

#### terminal.sexy/manual
Using [terminal.sexy](https://terminal.sexy), configurations for Sparky are available for many terminal emulators. You can also fine tune and customise Sparky's colours to your liking by importing [`sparky.xresources`](src/sparky.xresources) into terminal.sexy.

You can find some exported/generated config files on `src` and instructions on how to install them in your terminal [here](src/INSTALL.md).

### Base16 and Base24
Sparky is available as a Base16 and as a Base24 scheme; refer to [`sparky16.yml`](src/sparky16.yml) for Base16, or [`sparky24.yml`](src/sparky24.yml) for Base24.

This allows you to import Sparky into basically anything with a Base16/24 builder/manager like [Tinty](https://github.com/tinted-theming/tinty) or [Themix (Base16 only)](https://github.com/themix-project/themix-gui).

Note that due to Base16 only using 16 colours (who would've guessed) and due to its format, bright variants of colours and darks were removed.

### Community-sourced Themes
You can find Sparky community themes searching for [#sparky-theme](https://github.com/search?q=sparky-theme) in Github.

Currently there are none but one can have dreams.

## Credits
This theme was possible thanks to the following themes and people:
- [Adobe Color](https://color.adobe.com/) - used for its colour wheel and colourblind safety checks
- [Eric's Color Blender](https://meyerweb.com/eric/tools/color-blend/) - used alongside AC's colour wheel to find colours
- [iColorpalette](https://icolorpalette.com) - used for converting HEX codes for Pantone and finding alternative shades
- [terminal.sexy](https://terminal.sexy/) - used for live-testing, and exporting configs found in `src`
- [Enter Shikari Discord](https://discord.com/invite/yuPuTsQARE) - for encouraging me to continue developing the scheme
- [@tinted-theming](https://github.com/tinted-theming) - for hosting info, schemes and tools for B16/24
- [@maisymoe](https://github.com/maisymoe) - for getting me into Enter Shikari, and saving my life

## License
Sparky is released under the [Unlicense](https://unlicense.org) license, meaning that Sparky is released under the public domain, and you can do literally anything you want with the files provided here and the colour scheme swatched by me.