# Rapporto Intervento CTF – release

Release pubbliche di **AppReportCTF**, l'app per compilare il modulo *Rapporto Intervento* di CTF Automazioni e salvarlo in PDF.
Il sorgente è in una repo privata.

## Download

Dalla pagina **[Releases](../../releases/latest)**:

- **AppReportCTF.exe**: si avvia senza installazione e si aggiorna da solo a ogni avvio. Serve il runtime WebView2, già presente su Windows 10/11.
- **AppReportCTF_vX.html**: la stessa app da aprire in Chrome o Edge.

## Configurazione

Al primo avvio l'exe crea **`config.json`** accanto a sé (oppure in `%LOCALAPPDATA%\AppReportCTF\`). Contiene due percorsi:

```json
{
  "archivio": "percorso della cartella archivio commesse",
  "modello":  "percorso del modulo PDF Rapporto Intervento"
}
```

Per modificarlo usa il pulsante **⚙ Config** nell'app, poi premi **↻ Ricarica**.

## Dati

Questa repo e le release non contengono dati aziendali: niente commesse, anagrafiche o modulo PDF.
L'app legge tutto all'avvio dai percorsi di `config.json`, **solo in lettura**. I PDF dei rapporti vengono salvati sul PC di chi li compila.
