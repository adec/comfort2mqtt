# comfort2mqtt - A  Comfort alarm panel / MQTT bridge

The ultimate goal is to provide access to most of the [Comfort serial protocol](http://www.cytech.biz/serial_interface_protocol.html) functionality via an MQTT server, so that it can be integrated into home automation systems such as [Home Assistant](https://home-assistant.io).

This project's goal is to provide a simple Comfort/MQTT bridge (via a Comfort serial UCM) that supports communication in both directions with the Comfort alarm panel.

It is currently very much a work in progress.

By default comfort2mqtt will make an unauthenticated connection to the MQTT broker. If you wish to use an authenticated connection, either amend the MQTT_USER and MQTT_PASSWORD constants in the script or pass these parameters on the command line using the -u and -p options respectively. You will also need to set the MQTT_SIMPLE_ALLOW_INSECURE_LOGIN environment to 1 as the script currently does not support TLS.


