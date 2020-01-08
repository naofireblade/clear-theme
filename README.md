# Clear Theme
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)
[![GitHub last commit](https://img.shields.io/github/last-commit/naofireblade/clear-theme)](https://github.com/naofireblade/clear-theme)

This is a theme for [Home Assistant](https://www.home-assistant.io/). You can install it [manually](#installation) or via [HACS](https://hacs.xyz/).

## Installation

1. Copy the folder `themes` into your home-assistant folder
2. Add this under the section `frontend` in your `config.yaml`:
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

## Known issues
1. Recorder throws error when saving the theme because of the embedded background image  
 **Solution:** Download the [background image](https://github.com/naofireblade/clear-theme/raw/master/www/clear.jpg), place into folder `/www/` and change the 3rd line in the file `themes/clear.yaml` to `  lovelace-background: 'center / cover no-repeat url(/local/clear.jpg) fixed'`

> Feel free to leave any feedback [here](https://github.com/naofireblade/clear-theme/issues).

## Donations
If you like this theme, I would be forever grateful for your support:

<a href="https://www.buymeacoffee.com/2D1nUuK36" target="_blank"><img src="https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png" alt="Buy Me A Coffee"></a>

## Attributions
- Background Image from [visme](https://visme.co/blog/simple-backgrounds/)
