# MuxRemix
Not a fancy theme, just a clean design of muOS standard layout with custom color palettes, font and good spacing. Based on OneTwo by bulkh.

|![Stock](/preview/layoutStock.png)|![Grid](/preview/layoutGrid.png)|![Console](/preview/layoutExplore.png)|
|:---------------------------------|:-------------------------------|:-------------------------------------|

### What this theme has (and doesn't)
- [x] Clean aesthetics, stunning color palettes
- [x] Fast theme switching between alternatives
- [x] Support all device resolutions from MuOS, with optimal font size
- [x] Support most MuOS configurations
- [x] Not language dependent
- [ ] Color images for Content Grid Artwork aren’t supported (theme recoloring require monochrome images)

### Color scheme & structure

There are 10 color schemes (4 coming soon). Scheme files is very customizable and easy to add new color scheme later on.

|![ClassicDark](/preview/ClassicDark.png)   |![Nightly](/preview/Nightly.png)      |![BluePrint](/preview/BluePrint.png)|
|:------------------------------------------|:-------------------------------------|:-----------------------------------|
|![ClassicBright](/preview/ClassicLight.png)|![NicePastel](/preview/NicePastel.png)|![BlueSky](/preview/BlueSky.png)    |
|![Mustard](/preview/Mustard.png)           |![PinkNeon](/preview/PinkNeon.png)    |![RedWine](/preview/RedWine.png)    |
|![GreenBoy](/preview/GreenBoy.png)         |![PinkCandy](/preview/PinkCandy.png)  |![Tomato](/preview/Tomato.png)      |
|![JustBlack](/preview/JustBlack.png)       |![JustWhite](/preview/JustWhite.png)  |                                    |

To customize or create your own color scheme, the colors and layout are separated into different files. You can use the [Figma file](https://drive.google.com/file/d/1StkURvHPk3fyv9ksOYesrgm5YTDEbgNH/view?usp=sharing) as a guide. Below is the file structure and where to make changes.

```txt
...
├── alternate
│   └── {color}.ini        (Color schemes go here)
...
├── {resolution}
│   ├── font
│   │   └── default.bin    (Font file for specific resolution)
│   ├── scheme
│   │   └── default.ini    (General and listed layout)
│   │   └── muxlaunch.ini  (Grid layout for main menu)
│   │   └── muxlplore.ini  (Grid layout for explore)
```

Use this theme however you like, or treat it as a starting point for your own theme.

Icon glyphs and console images from [OneTwo](https://github.com/bulkh/OneTwo) theme. Big shout out to bulkh!

### Download
|Release      |Theme version                                                     |
|:------------|:-----------------------------------------------------------------|
|Pixie        |[v1.2.2](https://github.com/D98Jay/MuxRemix/releases/tag/v1.2.2)  |
|Goose        |[v1.2.2](https://github.com/D98Jay/MuxRemix/releases/tag/v1.2.2)  |
|Jacaranda    |[Latest](https://github.com/D98Jay/MuxRemix/releases/latest)      |
