# Blinky Power Relay Tray
Many old heating systems have no way to remotely turn them on and off so it is not possible to interface a spot price device directly to an old heating system. Replacing the entire heating system just because the heating system is manually controlled  but is otherwise functioning perfectly. would be very wasteful. 

It is not advised to power control a heating system by just turning it on and off with an electrical switch (relay). Instead an electrical switch (relay) can be used to control the  small pump that is used to pump hot water though the radiators.

With Blinky Power Relay, a an electrical relay is placed in series with the power to the radiator water pump. The relay is directly controlled with [Blinky Power Relay cube](https://github.com/blinky-lite-energy-exchange/blinky-power-relay-cube). The Blinky Power Relay cube can be remotely controlled via a Blinky Power Relay tray which has access to the electric spot price and can talk and be controlled with an web app on the Blinky-Lite application box.

This tray receives user input and the spot price from the Blinky-Lite application box server and uses the Blinky-Bus interface to communicate serially with the cube. The serial communication in this tray is done over Bluetooth. The tray code is derived from the [Blinky-Bus tray](https://github.com/Blinky-Lite-Exchange/blinky-bus-tray) project

<img src="doc/blinkyRelay.png"/><br>
