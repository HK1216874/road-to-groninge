# The Road to Groningen

Website voor de recruitment game van de vestiging (1 november – 31 december 2026).

## Wat staat er op de site
- Live tussenstand (vertrekbord), opgehaald uit de gepubliceerde Google Sheet *Groningen Recruitment Game – Tussenstand v2*
- "Al ingestapt": iedereen met een aanname
- Puntencalculator, treinwagon met stoelen en tickets, prijzen, Golden Ticket en dienstregeling

## De stand bijwerken
Pas alleen de Google Sheet aan (kolommen **Naam, Leads, M&G, Aannames**). De site rekent de punten zelf uit
(lead 2, M&G 5, aanname 15). Wijzigingen zijn na ongeveer 5 minuten zichtbaar.

Laat de kolomvolgorde en de namen van de kolommen staan, en laat *Publiceren op het web* aan.

## Online zetten (Vercel)
De site is één bestand (`index.html`) zonder build-stap.

1. Ga naar vercel.com/new en importeer deze repository.
2. Framework Preset: **Other**. Build Command en Output Directory leeg laten.
3. Klik op **Deploy**.

Elke push naar `main` zet de nieuwe versie automatisch online.
