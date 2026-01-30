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

There are 10 color schemes. Scheme files is structured in very customizable way for new color sheme addition later on.

|Lighter                                     |Darker                                  |
|:-------------------------------------------|:---------------------------------------|
|![ClassicBright](/preview/ClassicLight.png) |![ClassicDark](/preview/ClassicDark.png)|
|![MonoGreen](/preview/GreenBoy.png)         |![Mustard](/preview/Mustard.png)        |
|![MonoWhite](/preview/MonoWhite.png)        |![MonoBlack](/preview/MonoBlack.png)    |
|![MonoPink](/preview/Pink.png)              |![Nightly](/preview/Nightly.png)        |
|![TeamBlue](/preview/TeamBlue.png)          |![TeamRed](/preview/TeamRed.png)        |

If you want to make changes or create your own color shceme, this theme seperate color sheme and layout structure into different files (as muOS suggested). You can use this [Figma file](https://drive.google.com/file/d/1StkURvHPk3fyv9ksOYesrgm5YTDEbgNH/view?usp=sharing) as a guide to create your version. Below is the file structure where to make changes.

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

Icons and images from [OneTwo](https://github.com/bulkh/OneTwo) theme. Big shout out to bulkh!

### Download
|Release      |Theme version                                                     |
|:------------|:-----------------------------------------------------------------|
|Goose        |[v1.2.1](https://github.com/D98Jay/MuxRemix/releases/tag/v1.2.1)  |
|Jacaranda    |Not ready!                                                        |
