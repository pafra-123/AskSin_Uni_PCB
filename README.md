[![Creative Commons Lizenzvertrag](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

Dieses Werk ist lizenziert unter einer [Creative Commons Namensnennung - Nicht-kommerziell - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz](http://creativecommons.org/licenses/by-nc-sa/4.0/).

# AskSin_Uni_PCB

Kompakte, universale Platine für Asksin-Projekte [Asksin-Projekte](https://asksinpp.de/)

![LS](AskSin_Uni_PCB_01a.jpg)

[Schaltplan](AskSin_Uni_PCB.pdf)

### Was kann die Platine?
- Abmessungen ca. 45x45mm
- Platz für Arduino und Funkmodul
- Config Button
- 2 Status LEDs
- 1x Pinleiste für I²C
- Alle freien I/O Pins sind auf Lötaugen geroutet
- Zusätzliche Durchkontaktierungen beim Funkmodul, damit man mit dem ISP auch später noch dran kommt
- Optionaler 5V Spannungsregler(z.B. für das optionale Reed-Relais)
- Optionales 5V Reed-Relais mit Freilaufdiode und mit optionaler Status-LED
- Optionaler SMD-Spannungsteiler für HB-UNI-Sen-CAP-MOIST (R1, R2)
- Optionaler SMD-Spannungsteiler für HB-UNI-Sen-DIST-US (R3, R4)
- Optionaler SMD-Spannungsteiler für HB-UNI-Sen-PRESS (R7, R8)

### Benötigte Bauteile
Minimalbestückung:
- 1x U1 - ATmega328P und 3,3V / 8Mhz
- 1x U2 - Funkmodul CC1101 868Mhz
- 1x J6 - 8pol. Stiftleiste, gerade, RM 2,00
- 1x LED1 - SMD-LED rot (1206)
- 1x R5 - SMD-Widerstand 1kOhm (0805)
- 1x C2 - SMD-Kondensator 10µF (0805)
- 1x SW1 - Kurzhubtaster 6x6mm
