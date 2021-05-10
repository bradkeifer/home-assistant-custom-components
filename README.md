# home-assistant-custom-components
A proving ground for new Home Assistant components that I'm working on.

##### Component Overview
* [HAL CA1006 Multi-zone Amplifier](#hal)

### hal
Support for the HAL CA1006 multi-zone amplifier.

Based on top of a python module I wrote, [halca1006](https://github.com/bradkeifer/halca1006).
I am successfully running this in my own Home Assistant system, so feel free to use it at your
own risk. 


The component supports the config_flow style of configuration.
It creates one device for the HAL unit and one device for each zone that has connected speakers.
It also creates one `media_player` entity for each zone that has connected speakers.
The device and entity names are user defined in order to make them user friendly and fit for 
purpose for the specific installation.
