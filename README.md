# M3CHPR1

MACH3 Charge Pump Relay v1

Smart relay which can detect charge pump signal (12.5kHz) from MACH3 CNC software. Relay is activated when "charge pump" signal is detected. 

## Typical usage
I use it in E-Stop circuit. NO contacts are connected in series with end stops and E-Stop buttons. 

## Why use this module?
If you have your CNC machine connected via LPT to PC. Imagine that you turn on your machine, but your computer is not ready yet. I realized that PC changes state of LPT pins unexpectedly. So it can be dangerous for your machine and even for you. We want to wait when MACH3 is ready - than we can unblock all moving parts of machine.
