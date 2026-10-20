# APD - Laborator
Proiect de laborator pentru Achizitia si Prelucrarea datelor.
Nod de achizitie a temperaturii bazat pe Arduino Uno

## Parametri

### `SENSOR_PIN`
Pinul analogic la care este conectat senzorul. In acest proiect este setat pe `A0`, adica intrarea analogica 0 a placii Arduino Uno. Aceasta valoare este folosita in `analogRead(SENSOR_PIN)` pentru a citi nivelul brut al semnalului de la senzor.

### `SAMPLE_PERIOD_MS`
Perioada de esantionare in milisecunde. Valoarea `1000` inseamna ca nodul va realiza o masuratoare la fiecare 1 secunda. Aceasta este folosita in `delay(SAMPLE_PERIOD_MS)` pentru a controla intervalul dintre citiri consecutive.

### `SERIAL_BAUD`
Rata de transmisie a portului serial, exprimata in baud. Valoarea `9600` configureaza comunicarea seriala la 9600 de biți pe secundă. Este utilizata in `Serial.begin(SERIAL_BAUD)` pentru a initializa monitorul serial al Arduino.
