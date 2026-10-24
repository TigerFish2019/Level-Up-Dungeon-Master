# Level Up: Dungeon Master – installeren op je iPhone (zonder computer)

Een retro-pixel questapp in fantasy-stijl. Elke dag legt de Dungeon Master zeven quests op tafel: beweging, yoga, mindfulness, community en interactie. Jij kiest er drie. Alle gegevens blijven op je telefoon.

## 1. Bestanden klaarzetten
Open de app **Bestanden**, tik op `dungeonmaster-app.zip`. iOS pakt hem uit tot een map `dm-app`.

## 2. Online zetten via GitHub (in Safari)
1. Ga naar **github.com** en log in (of maak een gratis account).
2. Tik op **+** → **New repository**. Noem hem `dungeonmaster`, kies **Public**, vink **Add a README** aan en tik op **Create repository**.
3. Tik op **Add file** → **Upload files** → **Choose your files**, kies in Bestanden alle bestanden uit de map `dm-app`: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png`. Tik op **Commit changes**.
4. Ga naar **Settings** → **Pages**. Kies bij Branch **main** en **/(root)** en tik op **Save**.
5. Na 1 à 2 minuten staat de app op `https://jouwgebruikersnaam.github.io/dungeonmaster/`.

Zie je Settings of Upload niet? Tik in Safari op **aA** en kies **Vraag desktopwebsite aan**.

## 3. Installeren
1. Open het adres in **Safari**.
2. Tik op **Deel** en kies **Zet op beginscherm**.
3. Open de app één keer terwijl je online bent. Daarna werkt hij ook offline.

## Goed om te weten
- Dit is een aparte app, los van Hunter Systeem. Voortgang wordt niet gedeeld.
- **Tik op een onderstreepte oefening** (ook yoga- en ademhalingsoefeningen) en je held doet hem in pixelstijl voor.
- **d20:** rond je drie dagquests af en de Dungeon Master gooit een d20 voor je dagbonus. Een 20 geeft 2,5× de bonus, een 1 de helft.
- **Vloekmodus** (de strafmodus) kun je uitzetten onder Logboek.
- **Knieën:** de yogaquests geven aan waar je een kussen gebruikt. Doet iets pijn, trek dan opnieuw of kies een andere quest.
- Verwijder je het icoon, dan is je voortgang weg. Maak af en toe een back-up via **Logboek → Kopieer back-up**.
- **Updates:** vervang de bestanden op GitHub en verhoog `VERSION` in `sw.js`.
