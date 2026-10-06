# DBA-sieradenlogboek

Openbare downloadpagina voor DBA Advies Veenendaal, met Excel-logboek en PDF-printversie. Gewone HTML/CSS, zonder framework, database, accounts of formulieren.

## Bestanden

- `index.html`: downloadpagina.
- `styles.css`: responsive DBA-opmaak.
- `assets/`: logo en favicon.
- `downloads/`: uitsluitend lege logboeken.
- `vercel.json`: downloadheaders voor Excel en PDF.

## Publicatie

Koppel deze repository aan Vercel-project `dba-sieradenlogboek`. Framework: Other. Root directory: repository-root. Geen build- of installcommand; serveer de bestanden uit de root. Productiebranch: `main`.

De nieuwsbrief verwijst naar de vaste productiepagina. Gebruik geen beschermde preview-link. Controleer de productiepagina en beide downloads zonder ingelogd te zijn.

## Lokaal bekijken

Voer `python3 -m http.server 8000` uit vanuit deze map en open `http://localhost:8000`.

## Logboeken bijwerken

Vervang bestanden in `downloads/` en behoud de bestandsnamen. Werk zo nodig de bestandsgroottes in de pagina bij. Zet nooit ingevulde klantlogboeken of persoonsgegevens in deze repository.
