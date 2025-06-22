# MarstekVenus-M5stackRS485
Readout and control of Marstek Venus plugin battery with M5stack RS485 base (Atom S3 lite)



![image](https://github.com/fonske/MarstekVenus-M5stackRS485/blob/main/photos/m5stack_RS485_base_Atom_S3_lite.jpg)

Om de M5stack RS485 base te kunnen gebruiken op de Marstek Venus E, gevoed via de modbus connector, dient de er op de PCB een aanpassing gemaakt te worden dmv een gesoldeerde draadbrug.
Deze draadbrug bypassed the DC buck converter, die er origineel een te lage spanning van maakt (4,5 Vdc). Hierdoor zal de Marstek batterij telkens rebooten.
Door deze brug te plaatsten zal de 5V uit de marstek modbus connector direct op de Atom en PCB gevoed worden, daarmee is dit probleem getackeld.
![image](https://github.com/fonske/MarstekVenus-M5stackRS485/blob/main/photos/modify_pcb_for_5v.jpg)

> [!WARNING]
> Standaard is dus de RS485 base van m5stack dus niet te gebruiken zonder deze aanpassing!

Ik wil hier nog wat zeggen:
* blablabla
* blablabla.
* blablabla.
* blablabla.

Ontwikkkeling:
* 22-06-2025 - Eerste versie van de documentatie.


Magneethouder:
Deze is hier te downloaden.
Gebruikte extra materialen zijn:




