# Home Assistant LaMetric SKY Integration

Note: This project is currently broken due to some changes in the LaMetric Firmware. This may be fixed when this issue here gets resolved: https://github.com/home-assistant/core/issues/110058

This is an extended version of the LaMetric Integration for Home Assistant with support for SKY specific features, such as toggling the Display on and off

## Screenshots
![image](https://github.com/spyfly/ha-lametric-sky/assets/2892832/b32977a8-3b65-46b5-bd37-7e818a149fef)

## Installation

You can install this integration via [HACS](#hacs) or [manually](#manual).

### HACS

Visit the HACS Integrations page and click on the options menu with the three dots. Select custom repositories and copy this repositories URL `https://github.com/spyfly/ha-lametric-sky` and select the Integration category.

After adding the repository, click on LaMetric SKY Integration and select Install.

Reboot Home Assistant and configure the LaMetric integration via the integrations page or press the blue button below.

[![Open your Home Assistant instance and start setting up a new integration.](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=lametric)


### Manual

Download the release.zip and extract it to the `lametric` directory inside your custom_components folder. Reboot Home Assistant and configure the LaMetric integration via the integrations page or press the blue button below.

[![Open your Home Assistant instance and start setting up a new integration.](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=lametric)

## Credits

Based on the implementation of [homeassistant/core](https://github.com/home-assistant/core/tree/dev/homeassistant/components/lametric).
