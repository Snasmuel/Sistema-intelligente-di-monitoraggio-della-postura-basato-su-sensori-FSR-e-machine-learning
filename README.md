# Sistema intelligente di monitoraggio della postura basato su sensori FSR e machine learning

[cite_start]Questo progetto rappresenta il lavoro svolto per la mia Tesi di Laurea Triennale in Ingegneria Informatica presso l'Università di Pisa (Anno Accademico 2024/2025)[cite: 6, 7, 14].

## 🎯 Obiettivo del Progetto
[cite_start]Il sistema consiste in una sedia smart dotata di sensori di pressione integrati nella seduta, in grado di monitorare la postura dell'utilizzatore e fornire feedback tramite vibrazioni in caso la postura risulti essere scorretta[cite: 17]. [cite_start]L'elaborazione dei dati e la classificazione della postura avvengono tramite un algoritmo SVM[cite: 35].

## 🛠️ Il mio contributo: Progettazione Hardware
[cite_start]All'interno del progetto sviluppato in team, il mio contributo personale è consistito nella progettazione di tutta la componentistica hardware necessaria al corretto funzionamento del sistema[cite: 43]. 

Mi sono occupato specificatamente di:
* [cite_start] Scelta e dimensionamento dei componenti hardware[cite: 44].
* [cite_start]Integrazione elettrica e progettazione dello schema circuitale[cite: 44, 164].
* [cite_start]Progettazione del sistema di alimentazione e analisi energetica per garantire l'autonomia del dispositivo[cite: 44, 266, 283].

## 🧰 Componenti Hardware Utilizzati
Il sistema embedded è stato implementato utilizzando le seguenti componenti principali:
* [cite_start]**Microcontrollore:** Raspberry Pi 3[cite: 130].
* [cite_start]**Sensori di pressione:** 13 sensori FSR 406[cite: 118, 119].
* [cite_start]**Feedback aptico:** 3 motori vibranti Adafruit Vibrating Mini Motor Disc[cite: 122].
* [cite_start]**Convertitore A/D:** ADS1015 (12-bit)[cite: 137].
* [cite_start]**Multiplexer:** CD74HCx4067 (16 canali)[cite: 140].
* [cite_start]**Alimentazione:** 14 celle agli ioni di litio Samsung INR21700-33J collegate in parallelo, interfacciate con un convertitore step-up MT3608[cite: 133, 134].

## 📄 Documentazione
L'analisi completa del problema, le motivazioni dietro le scelte progettuali, il dimensionamento dei componenti e l'analisi economica ed energetica sono dettagliati nel documento di tesi allegato a questa repository: [`Tesi_Samuel_Scarabelli.pdf`](./Tesi_Samuel_Scarabelli.pdf).

## ⚖️ Licenza
Questo progetto è rilasciato sotto licenza MIT. Consulta il file `LICENSE` per maggiori dettagli.
