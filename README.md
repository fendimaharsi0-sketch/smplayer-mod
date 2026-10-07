# SMPlayer Mod

A personal fork of [SMPlayer](https://github.com/smplayer-dev/smplayer) for adding new features through the GUI — things upstream only exposes via config files or mpv commands, made into proper controls.

## Features

### Color temperature slider

The Video Equalizer dialog gains a **Temperature (K)** slider next to Contrast, Brightness, Hue, Saturation, and Gamma (1000–12000 K, 6500 K neutral). It's shader-safe: user GLSL shaders (FSR, nlmeans, ArtCNN, …) keep working while it's active.

## Windows builds

Two manual GitHub Actions workflows: **Build Windows Portable (x64)** (`.7z`) and **Build Windows Setup EXE (x64)** (unsigned NSIS installer). Run from the Actions tab against the `temperature-slider` branch.

## Releases

- [v1.1-temperature-slider](https://github.com/fendimaharsi0-sketch/smplayer-mod/releases/tag/v1.1-temperature-slider) (current)
- [v1.0-temperature-slider](https://github.com/fendimaharsi0-sketch/smplayer-mod/releases/tag/v1.0-temperature-slider) (superseded)

## Credits

Based on [SMPlayer](https://github.com/smplayer-dev/smplayer) by Ricardo Villalba and contributors.
