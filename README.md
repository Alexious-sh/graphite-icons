# Monochrome Icons Graphite Extension

A Home Assistant theme extension that replaces weather condition icons with
monochrome SVGs from the [Weather Icons project](https://github.com/erikflowers/weather-icons).

## Installation

1. In Home Assistant, open **HACS** and add this GitHub repository as a custom
   repository with the category **Theme**.
2. Download the theme.
3. Make sure Home Assistant loads themes from the `themes` directory, for
   example with:

   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```

4. Reload themes or restart Home Assistant, then select
   **Monochrome Icons Graphite Extension** in your profile's theme setting.

## Weather Icons attribution

The weather SVG artwork is from [Weather Icons](https://github.com/erikflowers/weather-icons).
The project credits the original icon designs to Lukas Bischoff. Its icon
artwork is licensed under the [SIL Open Font License 1.1](http://scripts.sil.org/OFL).
