# AppReportCTF – release

Release pubbliche di **AppReportCTF**, un'app per compilare un modulo PDF *Rapporto Intervento*.
Il sorgente è in una repo privata.

## Download

Dalla pagina **[Releases](../../releases/latest)**:

- **AppReportCTF.exe**: si avvia senza installazione e si aggiorna da solo a ogni avvio. Serve il runtime WebView2, già presente su Windows 10/11.
- **AppReportCTF_vX.html**: la stessa app da aprire in Chrome o Edge.

## Setup

Al primo avvio si apre la finestra **⚙ Setup**. Lì puoi:
- aprire il file `setup.json` che ti è stato fornito (**Apri esistente…**);
- oppure crearne uno nuovo, indicando la cartella principale e, se serve, il modulo PDF.

## Dati

Questa repo e le release non contengono dati: niente nomi, percorsi, archivi, commesse o moduli.
Tutto ciò che serve all'app sta nel `setup.json` sul PC di chi la usa. Le cartelle indicate lì vengono **solo lette**.
