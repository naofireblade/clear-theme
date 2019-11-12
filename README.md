# Clear Theme
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)
[![GitHub last commit](https://img.shields.io/github/last-commit/naofireblade/clear-theme)](https://github.com/naofireblade/clear-theme)

This is a theme for [Home Assistant](https://www.home-assistant.io/). You can install it [manually](#installation) or via [HACS](https://hacs.xyz/).

Feel free to leave any feedback [here](https://github.com/naofireblade/clear-theme/issues).

## Installation

1. Copy the folders `themes` and `www` into your home-assistant folder
2. Add this under section `frontend` in your `config.yaml`:
    ```
    frontend:
      themes: !include_dir_merge_named themes
    ```
3. Restart Home Assistant
4. Enable the theme in your user profile (bottom left in Home Assistant)
 
## Screenshot
![image](https://user-images.githubusercontent.com/12081369/68705076-b85f4380-058d-11ea-9534-04ae69f1a6d4.png)

## Optional custom cards from the screenshot
- [Button Card](https://github.com/rodrigofragadf/lovelace-cards/tree/master/tiles-card)
- [Animated Weather Card](https://github.com/bramkragten/custom-ui/tree/master/weather-card)
- [Graph Card](https://github.com/kalkih/mini-graph-card)
- [Slim Header](https://github.com/maykar/compact-custom-header/)

## Attributions
- Background Image from [visme](https://visme.co/blog/simple-backgrounds/)
