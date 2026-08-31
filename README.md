# Sapio — build pubbliche

Questo repo contiene **solo gli artefatti** di [Sapio](https://andreaferraboli.github.io/sapio-web/):
nessun sorgente, nessuna storia di sviluppo. Il contenuto viene rigenerato
integralmente a ogni push su `main` del repo sorgente (privato).

- App web: <https://andreaferraboli.github.io/sapio-web/>
- App Android: [`sapio.apk`](https://andreaferraboli.github.io/sapio-web/sapio.apk) — v0.7.0
- Manifest di versione: [`version.json`](./version.json) — è il file che i client
  interrogano per accorgersi che esiste una build più recente di sé stessi.

Il sito si aggiorna a ogni push; l'APK solo quando cambia la versione.

Build web corrente: **v0.7.0** · build 14 · commit `f218903`
