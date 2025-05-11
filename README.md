# Termometru Digital cu Bluetooth

**Author:** Cezara Chirilă
##  Description

Acest proiect constă în realizarea unui termometru digital inteligent, cu alarmă și transmisie Bluetooth. Dispozitivul măsoară temperatura și umiditatea ambientală folosind senzorul DHT22, afișează valorile pe un ecran LCD 1602 cu interfață I2C și trimite datele către o aplicație de tip terminal serial pe telefon prin modulul Bluetooth HC-05. Când temperatura depășește un prag stabilit, se activează un buzzer de avertizare.
##  Motivation

Proiectul este util pentru monitorizarea confortului termic în locuințe, birouri sau sere. Datorită transmisiei Bluetooth, utilizatorul poate primi date în timp real pe telefon, fără a fi nevoie de conexiuni complicate sau rețele WiFi.
##  Architecture

### Block Diagram
### Schematic (Textual)
##  Components

| Device                               | Usage                                      | Price (RON) | Link |
|-------------------------------------|--------------------------------------------|-------------|------|
| Arduino Nano (ATmega328p + CH340)   | Placă de control principală                | 24.99       | [link](https://www.optimusdigital.ro/ro/placi-programabile/10441-placa-arduino-nano-ch340.html) |
| DHT22 Sensor                         | Măsurare temperatură și umiditate          | 23.12       | [link](https://www.optimusdigital.ro/ro/senzori-temperatura/8527-senzor-temperatura-dht22.html) |
| LCD 1602 + Interfață I2C            | Afișaj alfanumeric cu 2 linii              | 16.34       | [link](https://www.optimusdigital.ro/ro/lcd-uri/3584-lcd-1602-i2c.html) |
| HC-05 Bluetooth Module              | Comunicare cu telefonul                    | 28.09       | [link](https://www.optimusdigital.ro/ro/bluetooth/9491-modul-bluetooth-hc05.html) |
| Active Buzzer                       | Avertizare sonoră                          | 4.98        | [link](https://www.optimusdigital.ro/ro/buzzer/3975-buzzer-activ.html) |
| Breadboard (750 puncte)             | Montaj fără lipire                         | 8.98        | [link](https://www.optimusdigital.ro/ro/breadboard-uri/8468-breadboard-750.html) |
| Jumper Wires (Male to Male)         | Conectarea componentelor                   | 22.99       | [link](https://www.optimusdigital.ro/ro/cabluri/3661-male-to-male-jumper-wires.html) |
| USB Mini Cable (AM la Mini 50 cm)   | Alimentare și programare Arduino           | 3.99        | [link](https://www.optimusdigital.ro/ro/usb/9612-cablu-usb-mini.html) |
| Plusivo Electronics Starter Kit     | LED-uri + rezistoare + PCB bonus           | 30.99       | [link](https://www.optimusdigital.ro/ro/kits/4065-starter-kit-plusivo.html) |

**Total estimat**: **178.46 RON**
##  Libraries
##  Log

- **Week 6 – 12 May**: Achiziția componentelor
- **Week 7 – 19 May**
- **Week 8 – 26 May**


