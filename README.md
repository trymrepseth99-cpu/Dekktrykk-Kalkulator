# Dekktrykk-kalkulator

Norsk dekktrykk-kalkulator for landevei, grus og terrengsykkel, laget for å brukes på mobil (iPhone).

Finn anbefalt lufttrykk foran og bak ut fra sykkeltype, vekt, målt dekkbredde, hjuldiameter, dekktype, underlag og gjennomsnittsfart.

## Bruk

Åpne siden i nettleseren. På iPhone: trykk Del i Safari og velg «Legg til på Hjem-skjerm» for å bruke den som en app. Innstillingene lagres kun lokalt på enheten (localStorage).

## Om beregningen

Modellen estimerer raskest mulig trykk. Tillegg utenfor selve modellen: komfortjustering (Balansert −5 %, Komfort −10 %) og vått føre (−8 %).

Resultatet er veiledende. Sjekk alltid min/maks-trykk som står på dekk og felg.

## Filer

- `index.html` – hele appen (HTML, CSS og JavaScript, ingen byggesteg)
- `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png` – app-ikon og installasjon på hjemskjerm
- `fonts/` – selvhostede fonter (Archivo, Rajdhani, IBM Plex Mono, alle under SIL Open Font License)

## Publisering (GitHub Pages)

Settings → Pages → Source: «Deploy from a branch», branch `main`, mappe `/ (root)`.
