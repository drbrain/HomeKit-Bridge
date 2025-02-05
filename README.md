![](https://raw.githubusercontent.com/Colorado4Wheeler/WikiDocs/master/HomeKit-Bridge/header.png)

# HomeKit Bridge

This plugin for the [Indigo Domotics](http://www.indigodomo.com/) home automation platform that publishes Indigo devices and action groups to Homebridge so that you can use your Indigo devices and actions in HomeKit and with Siri.

## Supported HomeKit Devices

The following list represents all of the HomeKit devices (which is 99% of all of them) that are supported via this plugin.  Their ability to work with your Indigo devices depends on the type of device you are using.  At this point do not plan on custom plugin devices that do not use standard Indigo device types (switches, dimmers, sensors, thermostats, irrigation, fans, etc) to work as very little custom plugin mappings have been built into this plugin.  That being said, many users find that using a wrapper from another plugin, such as [Masquerade](http://www.indigodomo.com/pluginstore/34/) or [Device Extensions](http://www.indigodomo.com/pluginstore/126/), has aided them in getting their custom device to work.

* Action Groups
* [Air Purifier](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#airpurifier)
* [Air Quality Sensor](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#airqualitysensor)
* [Battery Service (3rd Party and Siri Only)](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#batteryservice)
* [Camera RTP Stream](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#camerartpstreammanagement)
* [Carbon Dioxide (CO2) Sensor](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#carbondioxidesensor)
* [Carbon Monoxide (CO) Sensor](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#carbonmonoxidesensor)
* [Contact Sensor](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#contactsensor)
* [Door](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#door)
* [Doorbell (Experimental & Unsupported)](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#doorbell)
* [Fan (Original)](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#fan)
* [Fan](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#fanv2)
* [Faucet (3rd Party and Siri Only)](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#faucet)
* [Filter Maintenance (3rd Party and Siri Only)](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#filtermaintenance)
* [Garage Door Opener](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#garagedooropener)
* [Heater / Cooler](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#heatercooler)
* [Humidifier / Dehumidifier](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#humidifierdehumidifier)
* [Humidity Sensor](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#humiditysensor)
* [Irrigation System](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#irrigationsystem)
* [Leak Sensor](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#leaksensor)
* [Light Sensor](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#lightsensor)
* [Lightbulb](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#lightbulb)
* [Lock Mechanism](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#lockmechanism)
* [Microphone (3rd Party and Siri Only)](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#microphone)
* [Motion Sensor](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#motionsensor)
* [Occupancy Sensor](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#occupancysensor)
* [Outlet](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#outlet)
* [Playback Device Service (3rd Party Only)](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#playbackdeviceservice)
* [Security System](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#securitysystem)
* [Slat (3rd Party and Siri Only)](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#slat)
* [Smoke Sensor](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#smokesensor)
* [Speaker (3rd Party, Mute control in Home, Full Siri)](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#speaker)
* [Stateless Programmable Switch](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#statelessprogrammableswitch)
* [Switch](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#switch)
* [Temperature Sensor](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#temperaturesensor)
* [Thermostat](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#thermostat)
* [Valve](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#valve)
* [Window](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#window)
* [Window Covering](https://github.com/Colorado4Wheeler/HomeKit-Bridge/wiki/HomeKit-Model-Reference#windowcovering)

## Known Issues

You should always refer to the Git issues section to see what the outstanding problems are before reporting a new issue.  Reporting issues via Git is the preferred method of making sure your issue gets resolved as it's easy to get lost in the Indigo forums.

The biggest current issue is only for new installations, please read the quick start guide in the Wiki to familiarize yourself with that issue that requests that you disable Homebridge Buddy prior to installing HomeKit Bridge (you can re-enable it after the initial installation).  Since this is a very small audience of people it may not get addressed as it's be very difficult to reproduce the problem.
