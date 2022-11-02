# Warmwasser-Sparpumpe
## für Heizkessel mit Zirkulationskreislauf

Auf Basis des [Heise Artikels zur Zirkulationspumpensteuerung](https://www.heise.de/select/make/2022/4/2216608454200440892) wurde diese Variante entworfen.
Sie enthält folgende Änderungen

* Software
  * Tasmota!
  * Pumpenlogik ist als Tasmota-Skript implementiert.

* Hardware
  * Verwendung einer NodeMCU anstelle eines reinen ESP8266-Modul.
  * Schraubklemmen für sämtliche Anschlüsse
  * 5V Stromversorgung anstelle eines eigenen Netzteils

<img src="https://github.com/Trickx/Zirkulationspumpensteuerung/blob/main/Tasmota-Screenshots/Tasmota_Edit_Script.png" width="500">

|<img src="https://github.com/Trickx/Zirkulationspumpensteuerung/blob/main/Tasmota-Screenshots/Tasmota_Main_Menu.png" width="250">|
<img src="https://github.com/Trickx/Zirkulationspumpensteuerung/blob/main/layout_pic.png" width="250">|

<img src="https://github.com/Trickx/Zirkulationspumpensteuerung/blob/main/schaltung.png" width="500">

## Scripting ist nicht vorkompilierten Tasmota-Binaries enthalten.
Das Default-Tasmota Projekt muss unter Zuhilfenahme einiger zusätzlicher Defines gebaut werden.
* ![Anleitung](https://tasmota.github.io/docs/Scripting-Language/)
<img src="https://github.com/Trickx/Zirkulationspumpensteuerung/blob/main/Tasmota-Screenshots/user_config_override.h.png" width="500">


* Beachten Sie die einschlägigen VDE-Vorschriften.
* Keine Gewährleistung für irgendwas.
