# nepozs esphome-projects - information about bin files

Each file in a given zip archive contains a name consistent with the scheme:
`project-name_file-format_ESPHome-version_features(options).bin`
where:
- `project-name` any meaningful name (if possible matching associated with YAML file)
- `file-format ` can be `legacy` for ESPHome flasher https://github.com/esphome/esphome-flasher or `factory` for ESPHome web tools https://web.esphome.io/
- `ESPHome-version` compiled with ESPHome with this version number
- `features(options)` any meaningful names

examples:
esp01-ikea-vindriktning_legacy_2022_12_8.bin
project based on `esp01-ikea-vindriktning.yaml`, for ESPHome flasher, compiled with ESPHome 2022.12.8
cc2652p2lan-factory_ 2023_2_4_ble_nowebserver_espidf.bin
project based on `???.yaml`, for ESPHome web tools, compiled with ESPHome 2023.2.4, without web serwer, framework esp-idf

## License

Identical as ESPHome: https://raw.githubusercontent.com/esphome/esphome/dev/LICENSE

## Problems

Please report problems in repository build-in issuetracker: https://github.com/nepozs/esphome-projects/issues

## Future improvements

Planned compatibility with official Sharing ESPHome devices: https://esphome.io/guides/creators.html
