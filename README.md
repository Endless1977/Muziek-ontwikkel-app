# Muziek-ontwikkel-app — Spelmuziek Studio

Webapp om korte gitaarloopjes geschikt te maken voor HTML-spellen.

**Openen:** https://endless1977.github.io/Muziek-ontwikkel-app/

## Wat kan het
- Opnames laden (WAV, MP3, OGG, FLAC, M4A/AAC, OPUS) en knippen op de golfvorm, ook precies op maten (BPM)
- Categoriseren (menu, gevecht, eindbaas, overwinning, jingle, …), koppelen aan een spel, sfeertags en notities
- Omzetten naar MP3 met instelbare bitrate, samplerate, mono/stereo, normaliseren, fades en loop-crossfade
- Grootte-check (standaard max. 6 MB) en naadloze loops
- Uploaden naar deze repo in `audio/<categorie>/`, met een overzicht in `audio/muziek.json`
- Bibliotheek met afspelen en kant-en-klare code voor in je spel
- Stemkastje (`stemkastje.html`), opent als pop-up

## Instellen
1. Maak een fine-grained token: GitHub → Settings → Developer settings → Fine-grained tokens.
   Alleen deze repo, met **Contents: Read and write**.
2. Open de app, tab **GitHub**, vul het token in en klik **Verbinding testen**.

Het token blijft in je browser. Zet het nooit in deze repo.
