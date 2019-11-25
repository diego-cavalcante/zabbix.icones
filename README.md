![Zabbix logo](screenshots.en/zabbix.jpg)

*Read this in other languages: [English](README.md), [Português](README.pt.md), [Русский](README.ru.md).*

## Zabbix icons

Author: Diego Cavalcante\
E-Mail: diego@suportecavalcante.com.br\
Telegram: [diego_cavalcante](https://t.me/diego_cavalcante)\
Description: pack of almost 3000 icons for Zabbix Maps

Some images were taken from Google and others created from scratch in different colors and sizes. If you, like me, have spent some time developing maps, screens, and slideshows, congratulations because I know how slow and often complicated to express our environment and infrastructure in a visual and uncomplicated way, I hope you enjoy it.

NOTE: some images are free to use, others are proprietary.

## Installation

All you need to do is import xml files in the Zabbix web interface:
* Go to the address *your_zabbix_server_url/map.import.php*;
* Check the box next to the Images;
* Select the desired file and click Import.

If you want to change something, you need to generate your own set of icons using the script png_to_xml.sh, which transcodes images into text using base64 and creates an xml file from a directory with png images.\
Script is fixed because adds unnecessary tags ```<sysmap></sysmap>```. Source file is in [archive]( https://sourceforge.net/projects/zabbix/files/ZABBIX%20Latest%20Stable/4.4.1/zabbix-4.4.1.tar.gz).

Usage example:
```
cd zabbix.icons.en
./png_to_xml.sh equipment        equipment.xml
./png_to_xml.sh geometry         geometry.xml
./png_to_xml.sh labels           labels.xml
./png_to_xml.sh ../zabbix.icones.pt/legendas ../zabbix.icones.pt/labels.xml
./png_to_xml.sh ../zabbix.icons.ru/labels ../zabbix.icons.ru/labels.xml
./png_to_xml.sh miscellaneous_v1 miscellaneous_v1.xml
./png_to_xml.sh miscellaneous_v2 miscellaneous_v2.xml
./png_to_xml.sh miscellaneous_v3 miscellaneous_v3.xml
./png_to_xml.sh pixel            pixel.xml
./png_to_xml.sh proprietary      proprietary.xml
./png_to_xml.sh rack             rack.xml
./png_to_xml.sh virtualization   virtualization.xml
```

## Screenshots

Four colors of the icon mean four states: default (OK, in operation, green), problem (failure, red), maintenance (yellow), disabled (gray). For different icons, there are different sets of colors and sizes.

Note: file and directory names are translated into English, names are corrected to reduce confusion after importing to Zabbix.

#### equipment
![](screenshots.en/equipment_1.png)
![](screenshots.en/equipment_2.png)
![](screenshots.en/equipment_3.png)
#### geometry
![](screenshots.en/geometry_1.png)
![](screenshots.en/geometry_2.png)
![](screenshots.en/geometry_3.png)
#### labels
![](screenshots.en/labels.png)
![](screenshots.en/labels_pt.png)
![](screenshots.en/labels_ru.png)
#### miscellaneous_v1
![](screenshots.en/miscellaneous_v1_1.png)
![](screenshots.en/miscellaneous_v1_2.png)
#### miscellaneous_v2
![](screenshots.en/miscellaneous_v2_1.png)
![](screenshots.en/miscellaneous_v2_2.png)
#### miscellaneous_v3
![](screenshots.en/miscellaneous_v3_1.png)
![](screenshots.en/miscellaneous_v3_2.png)
![](screenshots.en/miscellaneous_v3_3.png)
![](screenshots.en/miscellaneous_v3_4.png)
#### proprietary
![](screenshots.en/proprietary.png)
#### rack
![](screenshots.en/rack.png)
#### virtualization
![](screenshots.en/virtualization.png)
