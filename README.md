# flavory-live
Flavory Live quiz app

## Fotofinish

`fotofinish/` is een fotoquiz voor op de beamer, waarbij iedereen meespeelt op zijn gsm.

- Quizmaster: open `fotofinish/?host` op de laptop aan de beamer. Spatie = verder, F = volledig scherm.
- Spelers: scannen de QR-code op het scherm, of openen `fotofinish/` en typen de code.
- Vragen maken: "Quiz bewerken" in de lobby. Sleep foto's in de lijst, elke foto wordt een vraag.
  Soorten: meerkeuze (met optionele uitzoomer), schatting, "gok de worp" en een pijlronde.
  "+ Wijnronde" zet er een blok wijnweetjes bij.
- Foto's en vragen blijven op de laptop (IndexedDB). "Pakket bewaren" en "Pakket laden" zetten ze in een .json-bestand.
  Er staan dus geen foto's in deze repo.
- De gsm's praten met de laptop via een publieke MQTT-server (geen accounts nodig).
  Lukt de verbinding niet, klik dan in de lobby op "Server" om een andere te kiezen.
