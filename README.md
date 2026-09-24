# 💡 Simulatore "Perché il Sistema Binario?" | Laboratorio Didattico

![Scope](https://img.shields.io/badge/Uso-Didattico-amber)
![License](https://img.shields.io/badge/Licenza-MIT-green)
![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20TailwindCSS%20%7C%20JS-blue)

Questa applicazione è uno **strumento didattico e laboratoriale** progettato per far scoprire agli studenti il motivo fondamentale per cui i calcolatori elettronici utilizzano il **sistema binario** anziché il sistema decimale.

Attraverso la simulazione dell'intensità luminosa di una lampadina virtuale (che rappresenta la tensione elettrica in un circuito reale), gli studenti toccano con mano la difficoltà di distinguere tra **10 stati possibili (0-9)** rispetto alla semplicità e robustezza di **2 soli stati (0 o 1, SPENTO/ACCESO)** in presenza di rumore ed interferenze elettriche.

---

## 🎯 Obiettivi Didattici

- **Comprendere l'interferenza**: Sperimentare come gli sbalzi di tensione e il rumore elettrico alterino i segnali.
- **Confronto Decimale vs Binario**: Rendersi conto di come una variazione del 5-10% possa far fallire la decodifica in un sistema a 10 livelli, mentre un sistema a 2 livelli tollevi margini di disturbo enormi (fino al 40-50%).
- **Apprendimento esperienziale**: Far guidare l'intuizione degli studenti attraverso un minigioco di decodifica visiva.

---

## 🕹️ Sezioni dell'Applicazione

### 1. 🎛️ Il Simulatore
- **Trasmettitore**: Imposta un valore da inviare e regola il cursore del **Rumore/Disturbo Elettrico**.
- **Segnale Ottico/Elettrico**: Osserva come varia la luminosità della lampadina e scopri la percentuale di intensità misurata.
- **Ricevitore**: Verifica se il ricevitore riesce a decodificare correttamente il valore o se incorre in un errore di trasmissione.

### 2. 🎮 La Sfida "Decodifica la Lampadina"
Un minigioco a round pensato per lezioni interattive in classe:
- **Round 1 (Decimale con Rumore)**: La lampadina trasmette 4 cifre decimali. Gli studenti devono indovinare le cifre basandosi sulla luminosità. Noteranno quanto sia facile sbagliare!
- **Round 2 (Binario con Stesso Rumore)**: Viene inviata una sequenza binaria. Gli studenti verificheranno quanto sia immediato distinguere tra luce accesa e spenta.

---

## 💻 Come Utilizzare l'App

L'applicazione è **100% client-side** (file unico HTML/JS):
- **Esecuzione Locale**: Basta fare doppio clic sul file HTML per aprirlo nel browser.
- **Hosting Online**: Può essere ospitata gratuitamente su **GitHub Pages** o **Netlify Drop** per condividerla con la classe tramite link.

---

## 📜 Licenza

Sviluppato esclusivamente per **scopi didattici e dimostrativi** nell'ambito dell'insegnamento dell'Informatica. Libero da utilizzare e riutilizzare nelle scuole.
