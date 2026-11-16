# AppReportCTF – release

Release pubbliche di **AppReportCTF**, un'app per compilare un modulo PDF *Rapporto Intervento*.
Il sorgente è in una repo privata.

## Download

Dalla pagina **[Releases](../../releases/latest)**: **AppReportCTF.exe**. Si avvia senza installazione e si aggiorna da solo (all'avvio e ogni 2 ore, modificabile nel Setup) senza perdere il rapporto in corso.

Serve il componente Microsoft **WebView2**, già presente su Windows 10/11. Se manca, all'avvio l'app propone di scaricarlo dal sito Microsoft e installarlo: il file viene accettato solo se firmato da Microsoft.

## Setup

Al primo avvio si apre la finestra **⚙ Setup**. Lì puoi:
- aprire il file `setup.json` che ti è stato fornito (**Apri esistente…**);
- oppure crearne uno nuovo, indicando la cartella principale e, se serve, il modulo PDF.

## Dati

Questa repo e le release non contengono dati: niente nomi, percorsi, archivi, commesse o moduli.
Tutto ciò che serve all'app sta nel `setup.json` sul PC di chi la usa. Le cartelle indicate lì vengono **solo lette**.
