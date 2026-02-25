# MuxRemix
Not a fancy theme, just a clean design of muOS standard layout with custom color palettes, font and good spacing. Based on OneTwo by bulkh.

|![Stock](/preview/layoutStock.png)|![Grid](/preview/layoutGrid.png)|![Console](/preview/layoutExplore.png)|
|:---------------------------------|:-------------------------------|:-------------------------------------|

### What this does
- [x] Clean aesthetics, stunning color palettes
- [x] Fast theme switching between alternatives
- [x] Support all device resolutions (include TUI-SP & TUI-Brick)
- [x] Optimal font size for each resolutions
- [x] Not language depend

### Color scheme & structure

There are 10 color schemes. Scheme files is very customizable and easy to add new color sheme later on.

|Classic                                     |Colorful                                |Monochrome                              |
|:-------------------------------------------|:---------------------------------------|:---------------------------------------|
|![ClassicDark](/preview/ClassicDark.png)    |![Nightly](/preview/Nightly.png)        |![MonoBlack](/preview/MonoBlack.png)    |
|![Mustard](/preview/Mustard.png)            |![TeamRed](/preview/TeamRed.png)        |![MonoWhite](/preview/MonoWhite.png)    |
|![ClassicBright](/preview/ClassicLight.png) |![MonoPink](/preview/Pink.png)          |                                        |
|![MonoGreen](/preview/GreenBoy.png)         |![TeamBlue](/preview/TeamBlue.png)      |                                        |

To customize or create your own color scheme, the colors and layout are separated into different files (as muOS recommends). You can use the [Figma file](https://drive.google.com/file/d/1StkURvHPk3fyv9ksOYesrgm5YTDEbgNH/view?usp=sharing) as a guide. Below is the file structure and where to make changes.

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
|Goose        |[v1.2.2](https://github.com/D98Jay/MuxRemix/releases/tag/v1.2.2)  |
|Jacaranda    |[v2.0](https://github.com/D98Jay/MuxRemix/releases/latest)        |
