# eq3-thermostat-enocean

Goal of this project:
Control a group of 3 eq3 bluetooth thermostats automaticly when a window is opened.

Message flow: -> EnOcean door/window sensor
                  -> EnOcean Pi on Raspberry Pi 3B+
                      -> Node Red on Raspberry Pi 3B+
                          -> Heckie75/eQ-3-radiator-thermostat script to control thermostats
                              -> 3 eq3 thermostats


Thanks to Heckie75 for his script!
Thanks to Holger Will for his support with the EnOcean sensor!
