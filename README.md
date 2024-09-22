# powercalc-custom-models
PowerCalc (Home Assistant custom component) custom model library for (my) devices not having unique product name and thus won't be accepted as part of official PowerCal model library. Tuya, Ledvance etc. devices which uses either generic product name or uniquish name but still the same name for multiple products in the offering.

## Generic models
* LEDVANCE SMART+ WiFi Tube T8EM 1200 18W 865
* LEDVANCE SMART+ WiFi Tube T8EM 1500 24W 865

## Usage
Put powercalc/ folder to Home Assistant config folder (where configuration.yaml also resides). Enable debug logging for the PowerCalc and find out exact manufacturer model name it detects and create symlink from generic model to your exact model i.e. tuya/LEDVANCE SMART+ WiFi Tube T8EM 1200 18W 865 -> tuya/Tuya generic (bf1bb78706514ab592qoon) and restart Home Assistant.
