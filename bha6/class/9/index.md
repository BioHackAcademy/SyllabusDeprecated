---
layout: page
title: Class 9 - bio-digital games and media
permalink: /bha5/class/9/
---

## Synopsys

Traditionally the last BHA lecture covers some interesting topic with guest lectures. This time its a special class on the topic of bio-digital games and media, with experts from the field. 

## Schedule

* Biotic Games introduction - Euglena Spaceships [PDF](/bha5/class/9/pdf/9.1 Biotic Games at Waag.pdf) - [VIDEO](https://vimeo.com/261943580)
* Wim van Eck & Maarten Lamers (Leiden University) - Organism Involved Computer Games [VIDEO](https://vimeo.com/261943628)
* Jan-Maarten Luursema - Planet Andi [VIDEO](https://vimeo.com/261944053)
* Raphael Kim (Queen Mary University) - Bio-digital interactions and Slow Biotic Games [VIDEO](https://vimeo.com/262571768)
* Syringe pump and peristaltic pump design [PDF](/bha5/class/9/pdf/9.2 Pumps design.pdf) - [VIDEO](https://vimeo.com/261944564)

## Devices

This week you can build two types of pumps. As with the other projects, each of the devices has its own github repository.

### Some notes on the source files and designs
* Code: We have included the LiquidCrystal_I2C library. However, as there are multiple libraries named LiquidCrystal_I2C around on the web, if you have included one in your Arduino libraries directory it can result in a conflict (errors during compilation). Temporarily remove the library from your Arduino libraries directory.
* Peristaltic pump: the design of the pump depends on the diameter of the tube. In case you use a different type, you will need to adjust the diameters. In our design we used HelixMark™ tubes (internal diameter 6.35 mm; external diameter 9.55 mm)
* Syringe pump: the mounting interface between the pump and the syringe depends on the type of syringe you use. In our design we used a MediWare 60mL syringe (REF: I3 040800).

### Syringe pump

This pump is best for moving small volumes of liquids, on at a time.

* [BHA_SyringePump repository](https://github.com/BioHackAcademy/BHA_SyringePump)

### Peristaltic pump

This pump is best continuously moving volumes of liquids.

* [BHA_PeristalticPump repository](https://github.com/BioHackAcademy/BHA_PeristalticPump)
* [Building guide](/biofactory/class/8-pumps/peristaltic-pump-building-guide/) 

Finished peristaltic pump:
[![Peristaltic Pump in action](http://img.youtube.com/vi/rvNwhfQSCfg/0.jpg)](http://www.youtube.com/watch?v=rvNwhfQSCfg)

[Watch the pump in action on Youtube](http://www.youtube.com/watch?v=rvNwhfQSCfg)

## Bill of Materials

In order to take part in this class you will need the following materials:

* [Syringe Pump materials](https://github.com/BioHackAcademy/BHA_PeristalticPump/blob/master/BoM.md)
* [Peristaltic Pump materials](https://github.com/BioHackAcademy/BHA_SyringePump/blob/master/BoM.md)

## Additional reading and hacking

* DIY Syringe pumps
  * [OpenPump](https://www.wevolver.com/gerrit.niezen/openpump---an-open-source-hardware-syringe-pump/openpump)
* DIY Peristaltic pumps
  * [Instructable Peristaltic Pump](http://www.instructables.com/id/Inexpensive-easy-to-build-peristaltic-pump/)

## Feeling lazy?

Go ahead and buy some pumps:

* [Syringepump.com](http://www.syringepump.com/index.php)
* [LabX Peristaltic Pump](http://www.labx.com/pumps-peristaltic)

Back to [BHA5 Classes](/bha5/classes/)