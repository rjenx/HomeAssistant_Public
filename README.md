# HomeAssistant_Public
 Public Version of my Home Assistant Installation 

This is my fifth major version of Home Assistant. It controls around 50 devices and over 200 sensor entities. More detail on the devices and features of my implementation can be found below. The only components missing are those with sensitive information such as secrets.yaml. 

Yaml is broken up into entity and sometimes function groups, this assists with working on specific objectives e.g. focus on security. However it makes it slightly more difficult where functionality affects multiple entities.

**Features and hardware used in my Implenentation**

**Integrations:**

**Audio visual** - Sonos, Alexa, Spotify and Plex (suspended for now), with two Samsung Tabs and a generic tablet providing kiosk duties for security pin entry and monitoring

**Security** - Sensors for motion and access, water leak, CO and smoke detection, Cameras and Doorbell, and Hive motion and access sensors. Manufacturers include Aqara, heimann and hive

**Access Control** - Security access is controlled by pin and NFC tags

**Lighting** - Combination of hive, lohas, INNR and Extsud bulbs

**Technology** - Docker on NUC running HA and Portainer, Speedtest and Unifi router monitoring and IFTTT. Backup is automated and rsynced to Synology NAS 

**Vehicle** - BMW integration for monitoring car parameters

**Weather** - Met office, Openweather and Climacell providing real time and forecasted weather for the home area and real time air quality

**Future projects:**

Replace the hive rad thermostats with zigbee devices to all radiators (in progress with three different valves under test) 

Displace hive sensors with zigbee native to improve reliability and speed of response, (all hive sensors, excluding thermostat, are now linked to ZHA and not Hive hub)

Replace "standard" Lovelace UI with something a bit more custom / snazzy and works on both laptop, mobile and tablet.

Build my first python integration!
