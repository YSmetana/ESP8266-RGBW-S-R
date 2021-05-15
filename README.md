View this project on [CADLAB.io](https://cadlab.io/project/24310). 

# ESP8266-RGBW-S-R

**ESP8266**-based **RGBW** controller with **S**ensor and **R**elay support.

This harware design (PCB) is based on the [ESP-GO project and Hackitt & Bodgitt](https://www.smarthometimes.com/1015/home-control-2019-and-esp-go/) board created by Pete Scargill and Aidan Ruff.

## Power supply
AC 110-220V or DC 5V, DC 5-24V.

### AC 110-220V, 5V needed
Use **PSU-A** HLK-PM01, output DC 5V. DC 3.3V via onboard LM1117-3.3.

### AC 110-220V, NO 5V needed
Use **PSU-D** HLK-2M03, output DC 3.3V. Short J4 to supply 3.3V directly from DC-DC convertor.

### DC 5V
Use **PSU-B** B0503S, output DC 3.3V. No onboard 3.3 regulator needed. Short J4 to supply 3.3V directly from DC-DC convertor.

### DC 5-24V
Use **PSU-C** LM2596-based buck convertor. Set output to 5V and use onboard LM1117-3.3. Or set output to 3.3V and short **J4** to supply 3.3V directly from DC-DC convertor.





## License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
