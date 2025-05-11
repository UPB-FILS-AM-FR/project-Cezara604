#Your Project Name:Termometru Digital cu Bluetooth
#Author: Cezara Chirilă
#Description:Acest proiect constă în realizarea unui termometru digital inteligent, cu alarmă și transmisie Bluetooth. Dispozitivul măsoară temperatura și umiditatea ambientală folosind senzorul DHT22, afișează valorile pe un ecran LCD 1602 cu interfață I2C, și trimite datele către o aplicație de tip terminal serial pe telefon prin modulul Bluetooth HC-05. Când temperatura depășește un prag stabilit, se activează un buzzer de avertizare.
#Motivation:Proiectul este util pentru monitorizarea confortului termic în locuințe, birouri sau sere. Datorită transmisiei Bluetooth, utilizatorul poate primi date în timp real pe telefon, fără a fi nevoie de conexiuni complicate sau rețele WiFi.
#Architecture:
Block diagram:

Schematic:
Components:
| Device                               | Usage                                      | Price (RON) |
|-------------------------------------|--------------------------------------------|-------------|
| Arduino Nano (ATmega328p + CH340)   | Placă de control principală                | 24.99       |
| DHT22 Sensor                         | Măsurare temperatură și umiditate          | 23.12       |
| LCD 1602 + Interfață I2C            | Afișaj alfanumeric cu 2 linii              | 16.34       |
| HC-05 Bluetooth Module              | Comunicare cu telefonul                    | 28.09       |
| Active Buzzer                       | Avertizare sonoră                           | 4.98        |
| Breadboard (750 puncte)            | Montaj fără lipire                         | 8.98        |
| Jumper Wires (Male to Male)         | Conectarea componentelor                   | 22.99       |
| USB Mini Cable (AM la Mini 50 cm)   | Alimentare și programare Arduino           | 3.99        |
| Plosivo Electronics Starter Kit     | LED-uri + rezistoare + PCB bonus           | 30.99       |
#Libraries
Log
Week 6 - 12 May:Achizitia componentelor
Week 7 - 19 May
Week 20 - 26 May
