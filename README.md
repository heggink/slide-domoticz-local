# Slide by Innovation in Motion

Plugin for Slide by Innovation in Motion.

This plugin uses the local API (beta).  

For a Domoticz plugin that uses the cloud API see:  
http://github.com/lokonli/slide-domoticz

## Version
This is beta release 0.0.1. <br/>

## Slide setup
First configure your slide using the Slide app for your own WiFi network.

Enable local API on your slide by pressing the reset button twice within 0.5 sec.<br/>


The reset button is in the hole left of the power connector, when you have the orange slide label on top.<br/>
The LED, right of the power connector, will flash a few time to indicate your slide switched to local API mode<br/>
<br/>

## Installation

Go to the Domoticz plugin folder.

    cd domoticz
    cd plugins

Clone the plugin repository:

    git clone https://github.com/lokonli/slide-domoticz-local

Restart Domoticz:

    sudo service domoticz restart

In Domoticz, add the slide-local hardware.

## Plugin configuration

The plugin uses two configuration fields:

Slide IP addresses: 1 or more IP addresses, semicolon separated.<br/>
Device codes: List of device codes, semicolon seperated. Number of codes must match number of IP addresses. Device code is printed on top of your Slide.<br/>

## Usage

Slide devices will be created automatically.

If you want to calibrate your slide go to the slide UI which can be found in the Custom->Slide screen in Domoticz.

## Todo

Wifi configuration for new slides.

## Links
[Domoticz forum](https://www.domoticz.com/forum/viewtopic.php?f=65&t=30449)

https://slide.store/