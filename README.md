# Recruiter CRM — sito GitHub Pages

Questo repository contiene la pagina vetrina di Recruiter CRM.

## Struttura

- `index.html` — pagina principale
- `style.css` — grafica
- `assets/` — video e immagini

## Pubblicazione

GitHub → repository → Settings → Pages → Build and deployment:
- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

## IMPORTANTE: aggiornamento del link di download

Attualmente i pulsanti puntano alla release:

`v3.2.3/Recruiter-CRM-Setup-3.2.3.exe`

Quando pubblichi una nuova versione con un nome file diverso, apri `index.html` e modifica SOLO la costante `DOWNLOAD_URL` in fondo al file, sostituendo il vecchio percorso con quello della nuova release.

Il repository delle release dell'app (`recruiter-crm-updates`) resta separato e non va modificato per pubblicare il sito.
