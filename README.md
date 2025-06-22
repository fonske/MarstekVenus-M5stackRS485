# MarstekVenus-M5stackRS485
Readout and control of Marstek Venus plugin battery with M5stack RS485 base (Atom S3 lite)


![image]([https://github.com/user-attachments/assets/343db925-dc42-4a91-88b5-51ac631e3bb0](https://github.com/fonske/MarstekVenus-M5stackRS485/blob/main/photos/m5stack_RS485_base_Atom_S3_lite.jpg))

Om de M5stack RS485 base te kunnen gebruiken op de Marstek Venus E, gevoed via de modbus connector, dient de er op de PCB een aanpassing gemaakt te worden dmv een gesoldeerde draadbrug.
Deze draadbrug bypassed the DC buck converter, die er origineel een te lage spanning van maakt (4,5 Vdc). Hierdoor zal de Marstek batterij telkens rebooten.
Door deze brug te plaatsten zal de 5V uit de marstek modbus connector direct op de Atom en PCB gevoed worden, daarmee is dit probleem getackeld.

Standaard is dus de RS485 base van m5stack dus niet te gebruiken zonder deze aanpassing!

Waarin is deze anders:
* blablabla
* blablabla.
* blablabla.
* blablabla.

Ontwikkkeling:
* 22-06-2025 - Eerste versie van de documentatie.
* 12-02-2025 - Uitlezen P1 dongle (WiFi) werkt inmiddels.  Dongle iP1_Dongle_Pro van smart-stuff.nl
* 13-02-2025 - Simulatie dongle gemaakt.  Dient om later een besturingsmodel te kunnen testen.


Magneethouder:
Deze is hier te downloaden.
Gebruikte extra materialen zijn:

![image](https://github.com/user-attachments/assets/1456eb45-89a0-4ce3-8583-d6aa8df0ffdf)


