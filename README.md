# Mightyboard
Pin mappings for the Makerbot Mightyboard Rev G and Rev H. These boards were used with the Replicator 2 and 2X printers. Physical locations of the pins are the same between the two boards, only the `J` designation is different.

<details><summary>Mightyboard Revision G</summary>
<p>

## Mightyboard Revision G
[Table of Connectors](Mightyboard_Rev_G/Connectors.md)

[Pins in Use](Mightyboard_Rev_G/Pins_in_use.md)

## Physical Notes
|            Rev G             |
|------------------------------|
| Beeper on underside of board |
| Includes a pcb_fan header    |

## Pinout Guide

![Pinout](Documents/Rev-G/Mightyboard_Rev_G_Pinout_Guide.png)

Pictures of the board can be found in the [Documents](Documents) folder.

</p>
</details>

<details><summary>Mightyboard Revision H</summary>
<p>

## Mightyboard Revision H
[Table of Connectors](Mightyboard_Rev_H/Connectors.md)

[Pins in Use](Mightyboard_Rev_H/Pins_in_use.md)

## Physical Notes
|            Rev H            |
|-----------------------------|
| Beeper on top side of board |
| Missing a pcb_fan header    |

## Pinout Guide

![Pinout](Documents/Rev-H/Mightyboard_Rev_H_Pinout_Guide.png)

Pictures of the board can be found in the [Documents](Documents) folder.

</p>
</details>

# Major Components on Board

|     Component Function      |        Component Name       |          Datasheet          |
|-----------------------------|-----------------------------|-----------------------------|
|             MCU             |       ATMega 1280/2560      | [Datasheet](Documents/ATmega640-1280-1281-2560-2561-Datasheet.pdf) |
|      Thermocouple ADC       |           ADS1118           | [Datasheet](Documents/ads1118.pdf) |
|      Bed Heater Mosfet      |     PSMN7R0-30YL SOT669     | [Datasheet](Documents/PSMN7R0-30YL.pdf) |
|    Hotend Heater Mosfets    |     PSMN7R0-30YL SOT669     | [Datasheet](Documents/PSMN7R0-30YL.pdf) |
|     Extruder Fan Mosfets    |        2N7002K SOT23        | [Datasheet](Documents/2N7002K.PDF) |
|       Part Fan Mosfet       |        2N7002K SOT23        | [Datasheet](Documents/2N7002K.PDF) |
|          Interface          |          ATMega8U2          | [Datasheet](Documents/ATmega8U2-16U2-32U2-Datasheet.pdf) |

# Power Supply Connector Pinout

![Power Connector Pinout Image](Documents/Power_Connector.webp)

[Socket Datasheet](Documents/Kycon_KPJX-CM-4S.pdf)

[Plug Datasheet](Documents/Kycon_KPPX-4P.pdf)