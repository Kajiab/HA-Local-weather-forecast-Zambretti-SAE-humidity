
Per observation, due to Zambretti not so suitable for tropical climate which weather have local change.
So, it's not so precised forecast from pressure need to more fine tune by integrate humidity and temperature to Z calculation. 
Or need to develop shorterm forecast by humidity and temperature model.
Using file subfix HTD (Humidity Temperature Dewpoint) for tropical area


Refered and modified code from
https://github.com/HAuser1234/homeassistant-local-weather-forecast

Installation
Please contribute ANY upgrades to the card or algorithm - this helps everybody!

copy weather_forecast.yaml into your custom yaml integrations folder how to make a integrations folder:
add this to your configuration.yaml:

homeassistant:
  packages: !include_dir_named integrations

create a folder named 'integrations' in your config directory
copy local_forecast.yaml in this folder
make changes for your individual setup (edit settings marked in weather_forecast.yaml
copy the card as a manual yaml config into lovelace. !mushroom required, vertical-stack-in-card required!
