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
./png_to_xml.sh equipment        equipment.xml
./png_to_xml.sh geometry         geometry.xml
./png_to_xml.sh labels           labels.xml
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

![alt tag](screenshots.en/15.png)
![alt tag](screenshots.en/16.png)
![alt tag](screenshots.en/17.png)
![alt tag](screenshots.en/18.png)
![alt tag](screenshots.en/19.png)
![alt tag](screenshots.en/20.png)
![alt tag](screenshots.en/21.png)
![alt tag](screenshots.en/22.png)
![alt tag](screenshots.en/06.png)
![alt tag](screenshots.en/07.png)
![alt tag](screenshots.en/08.png)
![alt tag](screenshots.en/09.png)
![alt tag](screenshots.en/10.png)
![alt tag](screenshots.en/11.png)
![alt tag](screenshots.en/12.png)
![alt tag](screenshots.en/13.png)
![alt tag](screenshots.en/14.png)
![alt tag](screenshots.en/01.png)
![alt tag](screenshots.en/02.png)
![alt tag](screenshots.en/03.png)
![alt tag](screenshots.en/04.png)
![alt tag](screenshots.en/05.png)
