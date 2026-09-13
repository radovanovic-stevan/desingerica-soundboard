# Desingerica Soundboard

Jedna stranica, 30 dugmića, svako pušta jedan stih Desingerice.

## Pokretanje

Otvori `index.html` u browseru — nema build-a, nema servera.
(Ako browser blokira `file://` audio, pokreni `python3 -m http.server` u ovom folderu i otvori `http://localhost:8000`.)

## Kontrole

- **Klik** na dugme ili tastatura: `1–9`, `Q–P`, `A–L`, `Z–M` (redom #01–#30)
- **Shift + taster** — sloj preko trenutnog zvuka
- **Space** — random dugme · **Esc** — stop sve
- **Panika mode** — pušta random stih svakih 0.7s dok ga ne ugasiš

## Snimci

`sounds/` — 30 mp3 isečaka (1.5–4.3s) iz pesama: Skakavacc, Merccedecc, Medovacca,
Đuskavacc, Tuckavacc, Ccuti, Ccucula, Rendalicca, Folkicc.
Lista i labele su u `sounds.js` — dodaj/izmeni tamo, stranica ih sama iscrta.
