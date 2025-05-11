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
| Arduino Nano (ATmega328p + CH340)   | Placă de control principală                | 24.99       | [link](https://www.optimusdigital.ro/en/compatible-with-arduino-nano/1686-development-board-arduino-nano-compatible-atmega328p-ch340.html) |
| DHT22 Sensor                         | Măsurare temperatură și umiditate          | 23.12       | [link](https://www.optimusdigital.ro/en/temperature-sensors/1449-dht22-temperature-and-humidity-sensor-module.html) |
| LCD 1602 + Interfață I2C            | Afișaj alfanumeric cu 2 linii              | 16.34       | [link](https://www.optimusdigital.ro/en/lcds/2894-1602-lcd-with-i2c-interface-and-blue-backlight.html) |
| HC-05 Bluetooth Module              | Comunicare cu telefonul                    | 28.09       | [link](https://www.optimusdigital.ro/en/wireless-bluetooth/153-hc-05-master-slave-bluetooth-module-with-adapter-33v-and-5v-compatible.html) |
| Active Buzzer                       | Avertizare sonoră                          | 4.98        | [link](https://www.optimusdigital.ro/en/buzzers/12513-pcb-mounted-active-buzzer-module.html) |
| Breadboard (750 puncte)             | Montaj fără lipire                         | 8.98        | [link](https://www.optimusdigital.ro/en/breadboards/13245-breadboard-750-points.html) |
| Jumper Wires (Male to Male)         | Conectarea componentelor                   | 22.99       | [link](https://www.optimusdigital.ro/en/wires-with-connectors/12475-male-to-male-jumper-wires-40-pin-40cm.html) |
| USB Mini Cable (AM la Mini 50 cm)   | Alimentare și programare Arduino           | 3.99        | [link](https://www.optimusdigital.ro/en/usb-cables/2022-cablu-negru-usb-am-la-mini-usb-50-cm.html) |
| Plusivo Electronics Starter Kit     | LED-uri + rezistoare + PCB bonus           | 30.99       | [link](https://www.optimusdigital.ro/en/kits/12026-plusivo-electronics-starter-kit-0721248990075.html) |


**Total estimat**: **178.46 RON**
##  Libraries
##  Log

- **Week 6 – 12 May**: Achiziția componentelor
- **Week 7 – 19 May**
- **Week 8 – 26 May**


