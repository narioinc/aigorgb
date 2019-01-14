# AIGO RGB controller hacks
This repo consists of all my reserach on the AIGO icestrom dr12 RGB enabled PC case fans,
I intend to create my own controller for this project with some of the below features:

a.	Better power delivery section
b.	Fuses and over-current protection
c.	Esp32 based RGB controller
d.	PWM control for fan
e.	Support for controller-to-controller daisy chaining
f.	REST API and BLE API for controller

I will be updating these pages as and when i progress. as usual commits and critical comments are welcome

I am not creating anything new or extraordinarily great, These are great fans for a very affordable price and I thought why not create a better software for these things.

Almost all of the companies creating these low cost fans (except some big players, who want to use a proprietary protcol) use the ws2812x protocol (alt. neopixel) and hence my controller design will be along those lines.
