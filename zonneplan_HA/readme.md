To see all items on this menu, you need to:

- install Zonneplan integration for Home Assistant through hacs. https://github.com/fsaris/home-assistant-zonneplan-one
- install lovelace-mushroom through hacs. https://github.com/piitaya/lovelace-mushroom
- install lovelace-card-mod through hacs. https://github.com/thomasloven/lovelace-card-mod
- install plotly-graph-card through hacs. https://github.com/dbuezas/lovelace-plotly-graph-card
- install stack-in-card through hacs. https://github.com/custom-cards/stack-in-card
- install apexcharts-card through hacs. https://github.com/RomRider/apexcharts-card
- add zonneplan.yaml to /config/packages
- install extra menu item (pencil - + (new item) - three dots - bewerken in yaml - copy and replace all the code from menu_ha.yaml to the text field in the new menu item)
- for some graphics you need Solcast installed and configured. (hacs). https://github.com/BJReplay/ha-solcast-solar
- install manual solcast (dutch): https://www.duurzamerhand.nl/zonnepanelen-blogs/zonne-opwek-en-voorspelling-visualiseren-home-assistant/
- configure the apexcharts forecast graphics with your own inverter data sensors  (I have a SMA)
- dont forget to restart homeassistant if something not working ;-)
- have fun