# Ökofen Pellematic Compact for Home Assistant

Currently in development. Not ready.

Meanwhile you can follow the following tutorial to get your Pellematic Compact connected
-> https://github.com/dominikamann/HomeAssistant-Oekofen-Pellematic-REST-Template

## Configuration

### Pellematic Compact

Go to your Ökofen Pellematic Compact 
  -> Touchscreen -> Open General Settings -> Network Settings 
    -> Scroll down -> Activate JSON Interface 
      -> Enter your IP-Address (Pellematic), Port & Password in the config section below

### Home Assistant Configuration.yaml

```
oekofen-pellematic-compact:
  update_interval: 1  # Optional, defaults to 1 minutes
  heater_url: http://[ip]:[port]/[password]/all
  heater_name: Pellematic Compact
```

## Installation

### HACS

Recommended as you get notifications of updates

* Add this repository [https://github.com/dominikamann/oekofen-pellematic-compact] to HACS as a "custom repository" with category "integration". This option can be found in the ⋮ menu
* Install the integration from within HACS
* Add a configuraton section to `configuration.yaml`
* Restart Home Assistant

### Manual

* Extract the Zip file in the `custom_components` directory
* Add a configuraton section to `configuration.yaml`
* Restart Home Assistant
