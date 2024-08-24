# RC_ControllerJr
Small PCB that uses ESP32 to control RC Devices

![](https://github.com/crabbedh/RC_ControllerJr/blob/main/PCB%20Image.jpeg)

This PCB was originally designed to power the small Mini-Dump designed by Professor Boots.
The advantage of this PCB is that it supports a 2S Lipo and a "Power Switch" that can
be controlled through software.

It includes:
1) Two motor driver outputs suitable for small DC motors, or LED circuits
2) Support for a Pololu 2808 "Power Switch", OR a physical power switch (don't install both!)
3) Support for two Servo connections
4) Monitoring of the battery using the onBoard ESP32 ADC
5) Power supply can be anything from 7-10v. Higher might damage the ESP32 ADC input. (Designed for 2S Lipo)
6) Powered by 30 pin ESP32 DevKit V1 module
7) Uses 5v switching regulator that can provide 2A of current

PCB has been tested in a Mini-Dump Junior remix for functionality.
You are free to download the Zip file to a PCB manufacturer, such as JCLPCB.COM, for your personal
use, or for educational use. You are not permitted to sell products with this PCB. You are not allowed 
to distribute the gerber files. Please link to this repository.

A component Zip file shows all componenets and images of the assembly.

Dave Crabbe
Aug 2024
