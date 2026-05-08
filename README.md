# Sistema intelligente di monitoraggio della postura basato su sensori FSR e machine learning

Questo progetto rappresenta il lavoro svolto per la mia Tesi di Laurea Triennale in Ingegneria Informatica presso l'Università di Pisa (Anno Accademico 2024/2025).

## 🎯 Obiettivo del Progetto
Il sistema consiste in una sedia smart dotata di sensori di pressione integrati nella seduta, in grado di monitorare la postura dell'utilizzatore e fornire feedback tramite vibrazioni in caso la postura risulti essere scorretta. L'elaborazione dei dati e la classificazione della postura avvengono tramite un algoritmo SVM.

## 🛠️ Il mio contributo: Progettazione Hardware
All'interno del progetto sviluppato in team, il mio contributo personale è consistito nella progettazione di tutta la componentistica hardware necessaria al corretto funzionamento del sistema. 

Mi sono occupato specificatamente di:
* Scelta e dimensionamento dei componenti hardware.
* Integrazione elettrica e progettazione dello schema circuitale.
* Progettazione del sistema di alimentazione e analisi energetica per garantire l'autonomia del dispositivo.

## 🧰 Componenti Hardware Utilizzati
Il sistema embedded è stato implementato utilizzando le seguenti componenti principali:
* **Microcontrollore:** Raspberry Pi 3.
* **Sensori di pressione:** 13 sensori FSR 406.
* **Feedback aptico:** 3 motori vibranti Adafruit Vibrating Mini Motor Disc.
* **Convertitore A/D:** ADS1015 (12-bit).
* **Multiplexer:** CD74HCx4067 (16 canali).
* **Alimentazione:** 14 celle agli ioni di litio Samsung INR21700-33J collegate in parallelo, interfacciate con un convertitore step-up MT3608.

## 📄 Documentazione
L'analisi completa del problema, le motivazioni dietro le scelte progettuali, il dimensionamento dei componenti e l'analisi economica ed energetica sono dettagliati nel documento di tesi allegato a questa repository: [`Tesi_Samuel_Scarabelli.pdf`](./Tesi_Samuel_Scarabelli.pdf).

## ⚖️ Licenza
Questo progetto è rilasciato sotto licenza MIT. Consulta il file `LICENSE` per maggiori dettagli.
