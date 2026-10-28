# Save the date – Italia in Piazza Marche

## File
- `index.html` → la pagina
- `evento.ics` → il file calendario

## Logo
Il logo è già incluso come `logo.jpg`. Per cambiarlo carica un nuovo file con lo stesso nome.

## Pubblicare su GitHub Pages (gratis, 5 minuti)
1. Crea un account su https://github.com (se non ce l'hai).
2. In alto a destra: **+ → New repository**. Nome, ad esempio: `marche-7-novembre`. Spunta **Public**. Clic su **Create repository**.
3. Nella pagina del repository: **Add file → Upload files**, trascina `index.html`, `evento.ics` e `logo.jpg`, poi **Commit changes**.
4. Vai su **Settings → Pages**. In "Branch" scegli `main` e cartella `/ (root)`, poi **Save**.
5. Dopo 1–2 minuti la pagina è online.

## I link finali
Sostituisci `NOMEUTENTE` con il tuo nome utente GitHub:
- Pagina: `https://NOMEUTENTE.github.io/marche-7-novembre/`
- File .ics diretto: `https://NOMEUTENTE.github.io/marche-7-novembre/evento.ics`

Usa il link della **pagina** per WhatsApp, Storie Instagram e QR code (funziona su tutti i telefoni).
QR code gratuito: incolla il link su https://www.qrcode-monkey.com e scarica in PNG/SVG ad alta risoluzione per la stampa.

## Come funziona il pulsante
- **iPhone / Mac**: apre il file .ics → "Aggiungi al calendario".
- **Android**: apre Google Calendar con l'evento già compilato → "Salva".
- **Desktop**: scarica il file .ics; sotto ci sono anche i pulsanti Google e Outlook.

## Aggiornare l'evento in futuro
Su GitHub apri il file, clicca la matita ✏️, modifica e **Commit changes**. Il link resta lo stesso.

**In `evento.ics`:**
- Data/ora: `DTSTART;TZID=Europe/Rome:20261107T150000` (formato AAAAMMGG T HHMMSS)
- Per aggiungere un orario di fine: nuova riga sotto DTSTART, es. `DTEND;TZID=Europe/Rome:20261107T190000`
- Titolo: `SUMMARY:` · Luogo: `LOCATION:` (le virgole vanno scritte `\,`) · Descrizione: `DESCRIPTION:`
- Aggiorna anche `DTSTAMP:` alla data della modifica e lascia invariato `UID:` (così chi ha già salvato l'evento lo vede come lo stesso evento).

**In `index.html`:**
- Testi visibili: cerca "Sabato 7 novembre", "15:00", "Piazza Cavour".
- Link Google/Outlook: in fondo al file, nelle righe `dates=` e `startdt=`.

Nota: chi ha già importato il file .ics non riceve aggiornamenti automatici; in caso di cambi importanti conviene ricondividere il link.
