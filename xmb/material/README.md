# Material for RetroArch

[![As seen on TV](https://forthebadge.com/images/badges/as-seen-on-tv.svg)](https://forthebadge.com) [![Designed in MS Paint](https://forthebadge.com/images/badges/designed-in-ms-paint.svg)](https://forthebadge.com) [![Uses Badges](https://forthebadge.com/images/badges/uses-badges.svg)](https://forthebadge.com) [![Compatibility: Club Penguin](https://forthebadge.com/images/badges/compatibility-club-penguin.svg)](https://forthebadge.com)

[![Material for RetroArch: Preview](https://my.mixtape.moe/xgkgcc.png)]()

## About

This theme aims to bring a Material Design interface to RetroArch, at least, you know, as far as customizability goes. I obviously can't redesign the whole UI.

I work on this whenever I have some free time and feel like it.

## Note

~~Don't use this yet, this is unfinished as fuck.~~

Actually you can do that now, some icons just aren't themed yet, but we're getting there.

## Creation

The SVG icons were converted to PNG files using [svgexport](https://github.com/shakiba/svgexport) and the following command: `svgexport src\icon.svg png\icon.png pad 256:256`.

The wallpaper JPG was cropped to a 16:9 aspect ratio and converted to a PNG file using [ImageMagick](https://www.imagemagick.org/script/index.php) and the following command: `convert src\bg.jpg -resize 1920x1080^ -gravity center -extent 1920x1080 png\bg.png`.

I also put some minimal effort into this and reduced the size of some icons by 0.5, done via `convert icon.png -resize 128x128 -background none -gravity center -extent 256x256 icon.png`.

Note: I only now learned about [this helpful table](https://docs.libretro.com/guides/themes/#tips-tricks-for-creating-icons) so I assume not all icons are in their correct size. I'll fix this some day.

## Licenses

The icons are part of the [**Material Design Icon Pack**](https://material.io/icons/) by **Google** and licensed under the **Apache License 2.0**.

The typeface, Roboto Light, and its family [**Roboto**](https://fonts.google.com/specimen/Roboto), also by **Google**, are licensed under the **Apache License 2.0**, too.
