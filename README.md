# Firma SOS Lambrate

Contiene la firma HTML e le immagini pubbliche da ospitare su GitHub Pages.

## Contenuto
- `index.html`
- `README.md`
- cartella `assets/` con:
  - `logo_sos_lambrate.png`
  - `icon_phone.png`
  - `icon_email.png`
  - `icon_web.png`
  - `icon_address.png`
  - `icon_instagram.png`
  - `icon_facebook.png`
  - `icon_tiktok.png`

## Pubblicazione
1. Usa il repository pubblico `SOSLambrate/sos-lambrate-signature`.
2. Carica **il contenuto di questa cartella** nella radice del repository.
3. Vai in **Settings > Pages**.
4. In **Build and deployment** seleziona **Deploy from a branch**.
5. Scegli **main** e **/(root)**, poi salva.
6. Dopo la pubblicazione controlla:
   - `https://soslambrate.github.io/sos-lambrate-signature/`
   - `https://soslambrate.github.io/sos-lambrate-signature/assets/logo_sos_lambrate.png`

## Note
- Le immagini vengono caricate via HTTPS e non come allegati tradizionali.
- Alcuni client email possono bloccare inizialmente le immagini remote.
- Per aggiornare la firma, sostituisci i file nel repository e attendi il nuovo deploy di GitHub Pages.

## Aggiornamento icona posizione
L'icona indirizzo deve apparire bianca sul fondo rosso `#ED0303`, come le altre icone. Il riferimento in `index.html` usa `?v=3` per evitare che i client mostrino la vecchia immagine memorizzata nella cache.

Aggiornamento v4: icona TikTok corretta (simbolo bianco con forma ufficiale); URL con versione per aggiornamento cache.

## Aggiornamento v5
Icone posizione e TikTok sostituite con PNG bianchi su trasparente, esportati da tracciati vettoriali ad alta risoluzione. Carica `index.html`, `assets/icon_address.png`, `assets/icon_tiktok.png`.
