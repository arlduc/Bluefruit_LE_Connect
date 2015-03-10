Bluefruit LE Connect
=================

iOS app for use with Adafruit's Bluefruit LE breakout board connected to Arduino. In this fork by Arlene Ducao, analog sensor values are geo-located, timestamped, written to an array, and optionally e-mailed to the user. 

Pick up a breakout to use along with this app here: http://www.adafruit.com/products/1697

Project tutorial: http://learn.adafruit.com/getting-started-with-the-nrf8001-bluefruit-le-breakout

Geo-timestamp tutorial: http://arlduc.org/senseandscale/?p=234 This tutorial was developed for the class "Quantified Self About Town" at NYU's Interactive Telecommunication's program. More at http://senseandscale.info

In progress!

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!




Version 1.5.1 (new geo-timestamp features)

=================

• Analog sensor values are written to an array while PinIOViewController is active.
• These sensor values are geo-located and timestamped using CoreLocation.
• When the user exits from PinIOViewController, he can optionally email the geo-timestamped values as a CSV.



Version 1.5
=================

• Controller Module
• Control Pad UI


Version 1.4
=================

• Info module
• UART packet optimizations


Version 1.3
=================

• Initial release
