# Material for RetroArch

## About

This theme aims to bring a Material Design interface to RetroArch, at least, you know, as far as customizability goes. I obviously can't redesign the whole UI.

## Note

Don't use this yet, this is unfinished as fuck.

## Creation

The SVG icons were converted to PNG files using [svgexport](https://github.com/shakiba/svgexport) and the following command: `svgexport src\icon.svg png\icon.png pad 256:256`.

The wallpaper JPG was cropped to a 16:9 aspect ratio and converted to a PNG file using [ImageMagick](https://www.imagemagick.org/script/index.php) and the following command: `convert src\bg.jpg -resize 1920x1080^ -gravity center -extent 1920x1080 png\bg.png`.

I also put some minimal effort into this and reduced the size of some icons by 0.5, done via `convert icon.png -resize 128x128 -background none -gravity center -extent 256x256 icon.png`.

## Licenses

The icons are part of the [**Material Design Icon Pack**](https://material.io/icons/) by **Google** and licensed under the **Apache License 2.0**.

The typeface, Roboto Light, and its family [**Roboto**](https://fonts.google.com/specimen/Roboto), also by **Google**, are licensed under the **Apache License 2.0**, too.