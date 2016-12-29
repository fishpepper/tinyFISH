# tinyFISH -- tiny / light / f3 / integrated receiver

My approach to build a small and lightweight flight controller.

See [http://fishpepper.de/projects/tinyFISH](http://fishpepper.de/projects/tinyFISH) for more details.

![tinyFISH image](http://fishpepper.de/wp-content/uploads/2016/12/tinyfish_fc_proto2-300x200.jpg)

This thing is TINY! The outer dimensions are 20x20mm with a 16mm hole-to-hole spacing.
It runs betaflight and includes a FrSky compatible RX, a current- and
voltage-sensor, a blackbox logger, and it is open hardware -- go and build one yourself!

Key features:
- STM32F303 CPU
- MPU6000 gyro (SPI connection!)
- integrated FrSky compatible rx based on [uSKY](http://fishpepper.de/projects/uSKY)
- integrated current- and voltage sensor
- integrated blackbox logger
- betaflight ready

This work is published under the CERN open hardware license v1.2. 
Feel free to use the design - but make sure to give proper credit 
and release all modifications under the same license! 
See LICENSE.txt for details!

THIS COMES WITH NO WARRANTY! BUILD, FLY, AND USE AT YOUR OWN RISK!


# Build your own

Make sure to init the git submodule for the libraries in the
kicad_misc directory by calling git submodule init && git submodule update.
You will have to use a recent kicad version, i used the commit #efdfaeb
when i designed this circuit board. Older versions will probably not work.
