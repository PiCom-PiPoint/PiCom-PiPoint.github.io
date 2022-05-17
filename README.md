# PiCom-PiPoint 🚌
![Java Version](https://img.shields.io/badge/Java-17.0-green.svg) ![Html Version](https://img.shields.io/badge/HTML-5-orange.svg) ![CSS Version](https://img.shields.io/badge/CSS-3-blue.svg) ![SASS Version](https://img.shields.io/badge/SASS-1.51.0-ff69b4.svg) ![GitHub](https://img.shields.io/github/license/PiCom-PiPoint/PiCom-PiPoint.github.io)

We consider an advertising system distributed over all the stops of a network of public transport. This system will be named "PiCom" for Pi Communication because it is based on
the use of Raspberry Pi. On each stop of the transport network are installed:

- a 32 inch screen
- a Raspberry Pi 4 model B on which Raspberry Pi OS is installed
- a 4G key that connects to a 4G network. We will assume that this key gives
a static IP address to each Raspberry Pi
- a secure and hermetic box in which the above equipment is
placed
Between 6 a.m. and 8 p.m., the Raspberry Pi at each transport network stop displays
advertisements.
This time interval is divided into time slots: 6h-7h, 7h-8h, etc.
The display duration of an advertisement is 15 seconds.
The transport network is divided into zones. A stop is in one and one
single area. A zone has a minimum of 5 stops and a maximum of 20 stops.
For each zone, a price for broadcasting advertisements is defined. This
broadcast rate changes according to the time slot.
For example: the display of an advertisement in the hyper-centre area
for the time slot 12 p.m. to 1 p.m. costs 25 euros.
The customer is guaranteed that during the same time slot and in an area
considered, the ad will be shown 40 times.

<br/>
The objective of this business case is to implement two applications :

- the PiCom application for customers and administrators
- the PiPoint application for Raspberry Pi

<br/><br/>
# Required work

To carry out this project, you must use a project management tool and
a versioning tool.
Your project should include the following phases:
- Modeling
- UML and/or Merise modeling
- Database design
- Design and development of web applications without the use of
framework
- Design and development of web applications with the use of
framework(s)
- Writing tests (unit and integration) for both applications
- Design and development of an Android and/or Electron application
- Design and development of a REST API

<br/><br/>
# Repository Statistics

![GitHub repo file count](https://img.shields.io/github/directory-file-count/PiCom-PiPoint/PiCom-PiPoint.github.io) ![Lines of code](https://img.shields.io/tokei/lines/github/PiCom-PiPoint/PiCom-PiPoint.github.io) ![GitHub language count](https://img.shields.io/github/languages/count/PiCom-PiPoint/PiCom-PiPoint.github.io)

<br/><br/>
# Installation
## To build CSS
```
npm i -g sass
sass assets/styles/scss/main.scss assets/styles/css/styles.css
```
You can add `--watch` at the end to create CSS file dynamicly while coding.
