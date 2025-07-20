# TonUINO
Persönliches TonUINO Projekt.

# Anleitung zum Compilieren

## Arduino IDE
Allgemeine Anleitungen zum Einrichten der IDE findet man hier [www.tonuino.de/TNG](https://www.tonuino.de/TNG) und hier [www.leiterkartenpiraten.de](https://www.leiterkartenpiraten.de)

- Es ist unbedingt darauf zu achten, dass das Verzeichnis in das das Repository gecloned oder heruntergeladen wird (also das Verzeichnis, in dem schließlich auch die TonUINO-TNG.ino zu finden ist, genau so heißt, wie die ino Datei, also in diesem Fall "TonUINO-TNG"!

- Bei der classic (Nano, Every, Every4808 und Esp32) sowie AiO HW Variante muss die Datei 'platform.local.txt' in den avr HW Ordner kopiert werden. Dieser Ordner ist gewöhnlich folgender:  

```
    Windows:  
      Classic:  C:\Users\<Benutzer>\AppData\Local\Arduino15\packages\arduino\hardware\avr\1.8.6
      Every:    C:\Users\<Benutzer>\AppData\Local\Arduino15\packages\arduino\hardware\megaavr\1.8.8
      AiO:      C:\Users\<Benutzer>\AppData\Local\Arduino15\packages\LGT8fx Boards\hardware\avr\1.0.7
      Esp32:    C:\Users\<Benutzer>\AppData\Local\Arduino15\packages\arduino\hardware\esp32\2.0.18-arduino.5

    Linux:  
      Classic:  ~/.arduino15/packages/arduino/hardware/avr/1.8.6
      Every:    ~/.arduino15/packages/arduino/hardware/megaavr/1.8.8
      Aio:      ~/.arduino15/packages/LGT8fx Boards/hardware/avr/1.0.7
      Esp32:    ~/.arduino15/packages/arduino/hardware/esp32/2.0.18-arduino.5/

    MacOS 13.x:  
      Classic:  ~/Library/Arduino15/packages/arduino/hardware/avr/1.8.6
      Every:    ~/Library/Arduino15/packages/arduino/hardware/megaavr/1.8.8
      AiO:      ~/Library/Arduino15/packages/LGT8fx Boards/hardware/avr/1.0.7
      Esp32:    ~/Library/Arduino15/packages/arduino/hardware/esp32/2.0.18-arduino.5/
```

- Man findet den Ordner auch, wenn man die Datei platform.txt sucht.  

- Für die AiOplus HW Variante sind keine Änderungen notwendig  

- Die HW Variante (TonUINO_*, ALLinONE oder ALLinONE_Plus) sowie die Button Konfiguration (THREEBUTTONS, FIVEBUTTONS oder BUTTONS3X3) muss in der Datei constants.hpp durch Entfernen des entsprechenden Kommentars angegeben werden. (nur wenn die Arduino IDE verwendet wird) 

**Libraries**
- Es müssen folgende Versionen der Libraries verwendet werden:  
    - jchristensen/JC_Button: 2.1.2  
    - boerge1/MFRC522_fix: 1.4.12  
    - makuna/DFPlayer Mini Mp3 by Makuna: 1.2.3
    - adafruit/Adafruit NeoPixel: 1.11.0 (optional, nur bei Feature NEO_RING notwendig)

## Teileliste
- AZDelivery TonUINO Set
- Widerstandset
- Jumperkabelset
- Kondensator: 1x1000µF
- 1x Leuchtdiode
- Widerstände: 1x1k, 2x220R
- Gebildet Taster 3x2-polig, 1x3-polig (für Powerbank)
- Powerbank mit gleichzeitigem Auf/Entladen (zB https://www.amazon.de/dp/B0CB1DC7GS)
- 1xMini-USB Kabel
- 1xUSB-C Kabel
- 1xUSB-C Buchse
- 1x Kopfhörer-Buchse
- 1x Visaton FRS 8 (4Ohm)
- 1x Gitter für Lautsprecher
- 1x micro SD Karte + Reader

## Tools
- App: TonUINO NFC Tools
- zum Batch-Beschreiben von RFID Karten: https://github.com/mxmehl/tonuino-cards-manager		
- HERMA Etiketten







