# NodeElroSwitch
NodeMCU with 433 Mhz Transmitter/Receiver and 0.96" OLED

----------

Hier präsentiere ich mein kleines Projekt.
Es handelt sich um einen NodeMCU Lua V3 (ESP8266 ESP-12E) Board einem 433Mhz-Empfänger und -Sender. Zum ablesen des Status beim schalten und des Netzwerks ist ein 0.96" OLED (D9011, 128 x 64 Pixel) (ACHTUNG: 6 Pin-Version) angeschlossen.

Mit diesem kleinen Bausatz schalte ich Elro-Steckdosen (o.ä. mit Hauscodeoption) über eine IP mit Passwortschutz per HTTPGET.

Die Hauscodes können pro Steckdose unterschiedlich angegeben werden und per ESP8622Webserver-Bibliothek bequem per Browser geschaltet werden. In meinem fall per GetHttpFile in [FHEM](https://fhem.de/) in einem DOIF.

Das ganze basiert auf dem Git von [sui77](https://github.com/sui77) mit dem Namen [rc-switch](https://github.com/sui77/rc-switch).

ToDo Readme:
fritzing





