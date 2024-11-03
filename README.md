# homeassistant addon cups airprint
CUPS addon with working Avahi in reflector mode and BRLaser drivers added

Tested with Home Assistant version **2023.9**

CUPS administrator login: **print**, password: **print** (can be changed in the Dockerfile)

Configuration data is stored in **/data/cups** folder

To access the web IF go to `https://homeassistant.local:631` adn accept any cert warnings. Ingress does not work at this stage though I am looking at it.

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fsmbm%2Fhomeassistant-addon-cups-airprint)
