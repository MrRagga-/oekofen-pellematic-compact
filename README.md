# Ökofen Pellematic Integration for Home Assistant

[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration) | [![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=dominikamann&repository=oekofen-pellematic-compact&category=integration)

Home Assistant integration `oekofen-pellematic-compact` is designed for Ökofen Pellematic Heaters with enabled TCP/JSON-Interface.
It communicates locally with the heater. This is not an official integration by Ökofen.

![grafik](https://user-images.githubusercontent.com/29973737/215227936-d4a86fa2-6906-48e2-8a7c-fa123d33babd.png)

![grafik](https://user-images.githubusercontent.com/29973737/215228078-2f2bd422-aa7a-485c-bad3-116d7d86a73e.png)

## Installation

Copy the content of the 'custom_components' folder to your home-assistant folder 'config/custom_components' or install through HACS.
After reboot of Home-Assistant, this integration can be configured through the integration setup UI

Click here to install over HACS:
[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=dominikamann&repository=oekofen-pellematic-compact&category=integration)

![grafik](https://user-images.githubusercontent.com/29973737/211389542-0800d1cf-6df9-45d4-8607-5f90689a8628.png)

## Enable JSON-Interface on your Ökofen Pellematic

Go to your Ökofen Pellematic 
  -> Touchscreen -> Open General Settings -> Network Settings
    -> Scroll down -> Activate JSON Interface
    
    IMPORTANT: Do not activate the compatibility mode. This mode is not supported/recommended.

 Use the provided URL as HOST in Component-Configuration (<http://[ip]:[port]/[password]/all>)
