# MarstekVenus-M5stackRS485
Modbus uitlezing en controle van een Marstek Venus plugin battery met M5stack RS485 base (+ Atom S3 lite)


![image](https://github.com/fonske/MarstekVenus-M5stackRS485/blob/main/photos/m5stack_RS485_base_Atom_S3_lite.jpg)

#### Uitleg aanpassing:
Om de M5stack RS485 base te kunnen gebruiken op de Marstek Venus E, gevoed via de modbus connector, dient de er op de PCB een aanpassing gemaakt te worden dmv een gesoldeerde draadbrug.

Deze draadbrug bypassed the DC buck converter, die er origineel een te lage spanning van maakt (4,5 Vdc). Hierdoor zal de Marstek batterij telkens rebooten.

Door deze brug te plaatsten zal de 5V uit de marstek modbus connector direct op de Atom en PCB gevoed worden, daarmee is dit probleem getackeld.

![image](https://github.com/fonske/MarstekVenus-M5stackRS485/blob/main/photos/modify_pcb_for_5v.jpg)

> [!WARNING]
> Standaard is de RS485 base van m5stack dus niet te gebruiken zonder deze aanpassing!


#### Ontwikkkeling:
* 22-06-2025 - Eerste versie van de documentatie.
* 27-07-2025 - [atom_s3_lite_rs485.yaml](https://github.com/fonske/MarstekVenus-M5stackRS485/blob/main/esphome/atom_s3_lite_rs485.yaml) naar v1.1. Esp-idf V5.3.1 fixed ivm compile error on v5.3.2. OTA webserver en esphome v2025.7.0

#### Magneethouder:
[Magneethouder](https://github.com/fonske/MarstekVenus-M5stackRS485/blob/main/photos/magnet_holder.jpg) voor m5stack rs485 base:
Het 3Dprint stl bestand is [hier](https://github.com/fonske/MarstekVenus-M5stackRS485/blob/main/3d_print/base_485_magnet_m5_marstek.stl) te downloaden.

#### Gebruikte materialen:
De gebruikte extra materialen zijn:
- 4x adereindhulzen wit 0.5 mm2
- [1x JST XH kabeltje](https://www.aliexpress.com/item/1005005811950799.html)  female, 10 cm, 6P
- [2x m3 schroefjes](https://www.tinytronics.nl/nl/gereedschap-en-montage/installatie-en-montagemateriaal/bouten/bout-m3-5mm-draad-100-stuks)
- [2x neodymium magneetjes](https://www.tinytronics.nl/nl/gereedschap-en-montage/installatie-en-montagemateriaal/magneten/xmp-neodymium-magneet-10x2mm-n35)

#### Contact
Purchase: alphonsuijtdehaag at gmail dot com, if you are interested in a complete set with M5Stack Atom s3 lite

.
> [!NOTE]
> Deze code is gebaseerd op het fantistische werk van Superduper1969. :+1:
> [Lilygo repository](https://github.com/fonske/MarstekVenus-LilygoRS485/tree/main?tab=readme-ov-file)
