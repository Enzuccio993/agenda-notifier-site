# Agenda Notifier · sito pubblico

**Presentazione del progetto e pagine pubbliche per il branding OAuth.**

![Sito statico](https://img.shields.io/badge/Sito%20statico-243746?style=flat-square) ![HTML e CSS](https://img.shields.io/badge/HTML%20e%20CSS-B7791F?style=flat-square)

[Contenuto](#contenuto) · [Anteprima locale](#anteprima-locale) · [Pubblicazione](#pubblicazione) · [Stato](#stato)

Pagina di presentazione di Agenda Notifier, informativa sulla privacy e termini. Il sito accompagna il progetto di promemoria locali per Google Calendar.

## Contenuto

| Percorso | Funzione |
| --- | --- |
| [index.html](index.html) | Pagina di presentazione |
| [styles.css](styles.css) | Stili condivisi |
| [privacy](privacy/) | Informativa sulla privacy |
| [terms](terms/) | Termini di utilizzo |
| [.nojekyll](.nojekyll) | Pubblicazione statica su GitHub Pages |

Il contenuto è HTML e CSS e non richiede una build. App Windows ed estensione browser citate nelle pagine appartengono al progetto applicativo; qui è ospitato il sito pubblico.

## Anteprima locale

Dalla cartella della repository, con Python installato:

```sh
python -m http.server 8000
```

Apri [localhost:8000](http://localhost:8000/) per verificare pagina iniziale, privacy e termini.

## Pubblicazione

Su GitHub Pages usa il branch `main` e la cartella `/ (root)` come sorgente.

| Pagina | Indirizzo previsto |
| --- | --- |
| Presentazione | [Agenda Notifier](https://enzuccio993.github.io/agenda-notifier-site/) |
| Privacy | [Informativa](https://enzuccio993.github.io/agenda-notifier-site/privacy/) |
| Termini | [Termini di utilizzo](https://enzuccio993.github.io/agenda-notifier-site/terms/) |

Questi sono gli URL di destinazione. Prima di usarli nel branding OAuth, verifica che le pagine siano raggiungibili e coerenti con l'app.

## Stato

Il sito contiene pagine statiche di presentazione e supporto. La loro presenza non indica che tutte le funzioni dell'app descritte siano già completate o distribuite.

---

A cura di [Enzuccio993](https://github.com/Enzuccio993).
