# Quad Rotor Control Board

This source was built for the STM32F103RBT6 from ST Microelectronics using a GCC toolchain (jsnyder/arm-eabi-toolchain).  At the time of writing this
(and my stuff is always out of date!) I'm using GCC 4.5.2  Even while writing this, it's out of date (Could be using 4.6.0) but I'm not.


## Contents

* ChibiOS
* Quad Rotor Controller Source

## Description

This directory holds the source used to get my quad rotor off the ground.  It is the collection of many hours of work, and is totally experimental!
Any files used to make this work, such as EAGLE design files, will also be included within.  I hope I can come up with an easy to follow directory
structure, but if not send me an email to tell me a better way!

## To Do List
- Radio Communication
	* Debugging Information
	* Current 'Job'
	* Heading
	* Attitude and Altitude
- Sensor Interface
	+ Gyroscope
	+ Accelerometer
	* GPS
	* Motor Speed

----------

Copyright [Dan Collins](http://dancollins.github.com/) 2011.  Released under the POPL licence (see LICENCE.TXT)
