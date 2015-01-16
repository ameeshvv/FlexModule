Edison+SD Flex Module
========

Initial Design Notes
36 pins + SD + Buttons + LEDs + various logic level converters (TXS0206 and either TXS0108E or TXB0108)
Use raised DP40 connector to fit SD and components under neath on board - DF40HC(3.0)-70DS-0.4V(51)?
SD low height - JAE ST11S008V4HR2000 (1.25mm) or 5040771891 - cheap (newark, 1.28mm)
Should fit in same layout as the STM32 large.

This is the hardware design repository for an Edison+SD Flex Module from Fyber Labs.  It will need 3v3 support
for buses and GPIO as well as USB OTG routing.  With a raised connector, components should easily fit under
the Edison.  Might as well as a SDmicro as well and fully use up the space.  Need to research console or
similar solution.