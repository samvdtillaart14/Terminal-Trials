# Terminal Trials – webapp voor je telefoon

Leer de Linux-terminal in korte lessen, van "Hallo, shell" tot Linux Mastery. Dit is de installeerbare webapp-versie (PWA): hij werkt offline en staat na installatie als app op je beginscherm.

## Online zetten met GitHub Pages

1. Maak op github.com een nieuwe repository, `Terminal-Trials` (Public).
2. Klik op **Add file › Upload files** en sleep alle bestanden uit deze map erin:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png`.
3. Klik op **Commit changes**.
4. Ga naar **Settings › Pages**. Kies bij *Source* "Deploy from a branch", branch `main`, map `/ (root)` en klik **Save**.
5. Na een minuut staat de app op `https://<jouw-gebruikersnaam>.github.io/Terminal-Trials/` (let op de hoofdletters: het pad is hoofdlettergevoelig).

## Op je telefoon installeren

- **Android (Chrome):** open de link, tik op ⋮ › **App installeren** (of "Toevoegen aan startscherm").
- **iPhone (Safari):** open de link, tik op het deel-icoon › **Zet op beginscherm**.

De app opent daarna schermvullend, zonder adresbalk, en werkt ook zonder internet.

## Bijwerken

Upload een nieuwe `index.html` naar dezelfde repository. Bij grotere updates verhoog je in `sw.js` het versienummer (`tt-v1` → `tt-v2`), zodat telefoons de nieuwe bestanden ophalen.

Je voortgang wordt op je telefoon zelf bewaard (in de browser van de app), los van de versie op claude.ai.
