# ESP01-REL-SoftAP
Pilotage d'un relais en WiFi en utilisant un ESP01-REL.

## A propos
Le code d'exemple fourni dans la documentation permet de piloter le relais en WiFi cependant le module est configuré pour fonctionner sur un réseau Wifi existant.

Le code de ce repository contient les modifications permettant de faire fonctionner le module comme un point d'accès. (Cf. "Soft Access Point" ci-dessous)

## Getting Started
Le code a été écrit à l'aide de Visual Studio Code + Platform IO

Pour ceux qui utilisent Arduino IDE, il faut supprimer la ligne 1 après le copier/coller :

        #include <Arduino.h>

## Montage
[A compléter]

### Sources / Documentation
- ESP-01S RELAY MODULE - GoTronic
https://www.gotronic.fr/art-module-relais-wifi-esp01-rel-34887.htm
- Documentation ESP-01S
https://www.gotronic.fr/pj-2714.pdf
- Soft Access Point
  https://arduino-esp8266.readthedocs.io/en/latest/esp8266wifi/soft-access-point-examples.html
