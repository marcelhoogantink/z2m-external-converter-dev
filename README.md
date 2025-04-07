# Zigbee2MQTT external converter development

Template to create external converters for Zigbee2MQTT in codespace.

# How to use

With your Github account, go to https://github.com/Nerivec/z2m-external-converter-dev and select `Use this template` > `Open in a codespace` in the top right corner.

# Codespace

https://docs.github.com/en/codespaces/quickstart

The codespace uses https://biomejs.dev/ for linting and formatting, with the [same configuration as zigbee-herdsman-converters](https://github.com/Koenkk/zigbee-herdsman-converters/blob/master/biome.json). A task is available to execute `npm run check` (`Terminal` > `Run task` > `npm: check`)

> [!TIP]
> If a new version of [zigbee-herdsman-converters](https://github.com/Koenkk/zigbee-herdsman-converters) is available but your codespace does not yet have it you can run `npm update --save zigbee-herdsman-converters` in the codespace to get it (`Terminal` > `Run task` > `npm: update-zhc`).
