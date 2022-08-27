# LibreVFD
LibreVFD is a free and open hardware implementation of a programmable variable frequency drive to drive 380-400V
This implementation uses STM32F4 (411/401) for svPWM to achieve smooth three-phase motor control.

Goal of LibreVFD is to provide an open, affordable, replicable programmable VFD implementation that uses general-purpse off-the-shelf components.

## Roadmap
- Testing svPWM signal
- Design PCB
- Design casing and cooling
- Investigate PowerMOSFET vs IGBT performance

## Preliminary BOM
 item | amount | price per item | total price 
--- | --- | --- | --- 
STM32F4xx | 1 | 10 $ | 10 $
G30N60A IGBT | 6 | 4 $ | 24 $
400V electrolytic radial leaded capactior | 2 | 4 $ | 8 $
FAN73893 transistor driver | 1 | 3 $ | 3 $
DB15-06 three phase rectifier | 1 | 8 $ | 8 $
300 ohm resistor | 6 | 0.008 $ | 0.048 $
470 nanofarad capacitor | 3 | 0.015 $ | 0.045 $
