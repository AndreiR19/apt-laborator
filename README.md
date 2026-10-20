# APD - Laborator
Proiect de laborator pentru Achizitia si Prelucrarea datelor.
Nod de achizitie a temperaturii bazat pe Arduino Uno
dapdlsa

## Parametri

- `CONFIG_H` este macro-ul de protecție al fișierului, pentru a evita includerea repetată a conținutului din `config.h`.
- `SENSOR_PIN` selectează pinul analogic pentru senzor; valoarea configurată este `A0`.
- `SAMPLE_PERIOD_MS` stabilește perioada de eșantionare în milisecunde; valoarea configurată este `1000` ms.
- `SERIAL_BAUD` stabilește viteza comunicației seriale; valoarea configurată este `19200` baud.
