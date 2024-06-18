# Refoss LAN
This homeassistant integration allows you to control your Refoss devices in a very flexible way.


## Installation
### HACS
In your HA frontend go to HACS -> Integrations, search for 'Refoss LAN' and hit 'Install' You'll have to restart HA to let it recognize the new integration.

### Manual installation
Download and copy the custom_components/refoss_lan directory into the custom_components folder on your homeassistant installation.

Depending on the type of HA installation you might have to follow specific instructions.

This is working for a standard 'core' installation but should work for any other flavour: remember to set the appropriate ownership and access rights on your copied files so the homeassistant user running your instance is able to read and execute the integration code.

Restart HA to let it play.

## Supported device models

| Model | Version            |             
| ----------- |--------------------|
| `Refoss Smart Wi-Fi Switch, R10`    | `all`              |
| `Refoss Smart Energy Monitor, EM06` | `v2.3.8 and above` |

