# Muziek-ontwikkel-app — Spelmuziek Studio

Webapp om korte gitaarloopjes geschikt te maken voor HTML-spellen.

**Openen:** https://endless1977.github.io/Muziek-ontwikkel-app/

## Wat kan het
- **Een tab per spel**: Tandem, Kronkels, Noodlanding, Aether Arena, Lumen Tunnelrace, 404: Will Found, Domination, Flippin Pippin, Buro Bolides en Nano Evolutie. Volgorde aanpassen door te slepen of via **↔ Volgorde** (◀ ▶, verbergen); de volgorde wordt in je browser onthouden.
- **Spelplan per spel**: alle muziekplekken die het spel nodig heeft, met richtlijnen (tempo, toonsoort, sfeer) en wat er al gevuld is. Voor Tandem zijn dat de 17 nummers uit het spel zelf: menu, de 7 werelden, drydock, mini-baas, eindbaas, Null Sovereign (beide vormen), transformatie, overwinning, game over en de aftiteling.
- **Koppelbestand**: per spel een JSON met per plek het MP3-adres en de looppunten, om het spel de muziek te laten laden.
- Opnames laden (WAV, MP3, OGG, FLAC, M4A/AAC, OPUS) en knippen op de golfvorm, ook precies op maten (BPM)
- Categoriseren (menu, gevecht, eindbaas, overwinning, jingle, …), koppelen aan een spel, sfeertags en notities
- Omzetten naar MP3 met instelbare bitrate, samplerate, mono/stereo, normaliseren, fades en loop-crossfade
- Grootte-check (standaard max. 6 MB) en naadloze loops
- Uploaden naar deze repo in `audio/<spel>/<plek>/`, met een overzicht in `audio/muziek.json`
- Bibliotheek met afspelen en kant-en-klare code voor in je spel
- Stemkastje (`stemkastje.html`), opent als pop-up

## Instellen
1. Maak een fine-grained token: GitHub → Settings → Developer settings → Fine-grained tokens.
   Alleen deze repo, met **Contents: Read and write**.
2. Open de app, tab **GitHub**, vul het token in en klik **Verbinding testen**.

Het token blijft in je browser. Zet het nooit in deze repo.
