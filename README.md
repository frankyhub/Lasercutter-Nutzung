# Oberlab Lasercutter
![lb](https://github.com/frankyhub/png/blob/master/lightburn.png)

Unterlagen für die [Einweisung](https://github.com/frankyhub/Lasercutter-Nutzung/blob/master/Nutzungsberechtigung%20Lasercutter%20V1_8.pdf) und [Workshop](https://github.com/frankyhub/Lasercutter-Nutzung/blob/master/Lasercutter%20%20Workshop%20%20Teil%20I%20V1_8.pdf)

Teil 1: Funktionsprinzip

Teil 2: Sicherer Umgang mit dem Lasercutter

Teil 3: Arbeiten mit LightBurn

Teil 4: Lasercutter Checkliste

Teil 5: Materialparameter


this serial port are different depending on which Arduino you are using.

| Microcontroller Board | Hardware serial? | MCU RX pin | MCU TX pin |
|-----------------------|------------------|------------|------------|
| A-Star 32U4           |        Yes       |      0     |      1     |
| Arduino Leonardo      |        Yes       |      0     |      1     |
| Arduino Micro         |        Yes       |      0     |      1     |
| Arduino Mega 2560     |        Yes       |     19     |     18     |
| Arduino Due           |        Yes       |     19**   |     18     |
| Arduino Uno           |        No        |     10     |     11     |
| Arduino Yun           |        No        |     10     |     11     |

If you would like to read information from the Maestro, like in the Input

## Material-Parameter

|   Material  | Stärke mm |   Modus   |Passes |Speed mm/s |Pmax %|
|-------------------------|-----------|-------|-----------|------|
| Sperrholz   |     4     | Gravur    |   1   |   100     |   5  |
| Sperrholz   |     4     | Schneiden |   1   |    30     | 100  |
| Leder       |     4     | Gravur    |   1   |	  100     |   3  |
| Filz        |     3     | Gravur    |   1   |   100     |   0,1|
| Holz        |     4     | Gravur    |   1   |   100     |  10  |
| MDF         |     2     | Schneiden |   1   |    15     | 100  |
|             |           |           |   1   |           |      |

