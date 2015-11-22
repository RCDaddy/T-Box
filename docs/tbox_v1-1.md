#T-Box v1.1

#Source Code
In the settings.h file you will need to change the following lines
```
#define rssiPinA A6
```
to
```
#define rssiPinA A2
```

and also

```
    #define rssiPinB A7
```
to
```
    #define rssiPinB A3
```

####BOM
- 3x 1k resistor
- 2x 100k resistor
- 3x 330 resistor
- 2x rx5808 receiver with [spi mod](rx5808-spi-mod.md)
- 3x 5mm LEDs
- 3x Miniature Tactile Button
- 1x DSN-MIN-360 Step Down regulator.
- 2x RP-SMA/SMA connector board mountable
- 1x 4066 digital switch chip
- 1x Atmega328p
- 1x 16.000Mhz Crystal
- 2x 22pf Cap
- 1x 0.1uf Cap
- 1x 10k resistor

- 1x OLED 128x64 display I2C (5v tollerant) Pin order must be VCC GND SCL SDA

Board available at [OSHPark](https://oshpark.com/shared_projects/U8csRbMR)

![alt text](img/v1.1/t-box%20v1.1%20r2%20front.png)
![alt text](img/v1.1/t-box%20v1.1%20r2%20back.png)

