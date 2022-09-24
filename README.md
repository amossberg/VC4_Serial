# VC4_Serial
Demonstration of using Crestron's VC-4 to access a local Serial Port on the host server

For this example, we are using SIMPL Windows to create a small project that connects to a Denon Receiver.

We set up the USB-Serial Port adapter as /dev/ttyUSB0 on AlmaLinux, and we use the socat utility to create a listening TCP port
to take the commands from the SIMPL Windows program and send them to the serial port adapter.

Any FTDI Serial Port adapter will probably work with AlmaLinux, like this one https://amzn.to/3Scr6D3

Crestron, VC-4, SIMPL Windows are trademarks of Crestron Electronics, Inc. See https://www.crestron.com/ for more information.


Andrew Mossberg/HumaneInterface.com September 2022
