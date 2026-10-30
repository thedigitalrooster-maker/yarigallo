# yarigallo — sito personale v0.1
Sito one-page statico in italiano per Christian Yari Gallo, Innovation & Digital Solutions Specialist.

## Tecnologia
HTML5, CSS3, JavaScript vanilla. Nessun pacchetto npm, database, autenticazione o costo di piattaforma richiesto per la demo. Animazioni CSS, IntersectionObserver, FAQ native `<details>`, modal HTML `<dialog>`.

## Anteprima locale
Aprire `index.html` in un browser (oppure avviare `python -m http.server 8000` dalla cartella e visitare `http://localhost:8000`).

## Pubblicazione su GitHub Pages
1. Creare un repository **pubblico** chiamato `yarigallo` nel proprio account GitHub (GitHub Pages gratuito per repository pubblici con piano Free).
2. Caricare i file **mantenendo** le directory `.github/workflows` e `assets` (tramite Git o caricamento web con cartelle).
3. In `Settings > Pages`, impostare `Source: GitHub Actions`.
4. Ogni push sul ramo `main` attiva il workflow `deploy.yml`. Il sito sarà accessibile su `https://USERNAME.github.io/yarigallo/`.
5. Per collegare `yarigallo.it`, verificare la disponibilità, acquistare il dominio, configurare DNS e Custom domain nelle impostazioni Pages.

## Prima della pubblicazione ufficiale
- In `script.js` valorizzare `CONTACT.email`, `CONTACT.phoneInternational`, `CONTACT.whatsappInternational`; usare numeri internazionali, senza spazi (per WhatsApp solo cifre).
- In `index.html` correggere il link email nel footer e aggiungere informativa privacy reale, consenso, dati identificativi applicabili. Fino ad allora **non utilizzare il modulo per raccogliere dati personali**.
- La richiesta appuntamento non invia dati a un server: apre il client email con un messaggio precompilato e richiede invio manuale. Non conferma nessuna prenotazione.
- Sostituire il monogramma in sezione Chi sono con una fotografia autentica autorizzata quando disponibile.
- Verificare descrizioni dei progetti e autorizzazioni, aggiungere casi e risultati verificabili.
- Migliorare accessibilità, test multi-browser e performance con foto/video reali prima del lancio.

## Struttura
- `index.html` struttura e testi
- `style.css` identità visiva dark premium, responsive e animazioni
- `script.js` menu, reveal, contatti e richiesta email
- `assets/favicon.svg` icona
- `.github/workflows/deploy.yml` pubblicazione automatica

## Roadmap
v0.2: fotografie reali, dettagli progetti, URL social, contatti configurati, privacy.
v0.3: backend di richieste solo se necessario (es. serverless), con anti-spam e gestione consenso.
