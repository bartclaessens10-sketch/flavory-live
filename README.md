# flavory-live
Flavory Live quiz app

## Fotofinish

`fotofinish/` is een quiz voor op de beamer, waarbij iedereen meespeelt op zijn gsm:
wijnweetjes, foto's van de dag en opdrachten.

- Quizmaster: open `fotofinish/?host` op de laptop aan de beamer. Spatie = verder, F = volledig scherm.
- Spelers: scannen de QR-code op het scherm, of openen `fotofinish/` en typen de code.
- Vragen maken: "Quiz bewerken" in de lobby. Sleep foto's in de lijst, elke foto wordt een vraag.
  Soorten: meerkeuze (met optionele uitzoomer), schatting, opdracht (de quizmaster tikt aan wie punten krijgt)
  en rondetitel. "+ Wijnronde" zet er telkens 6 nieuwe wijnweetjes bij.
- Teams: kies in de lobby het aantal teams en draai de fles om iedereen in te delen. Elk team heeft een glas
  dat bijgeschonken wordt met de punten van zijn spelers (gemiddelde per speler). Het volste glas wint.
- Foto's en vragen blijven op de laptop (IndexedDB). "Pakket bewaren" en "Pakket laden" zetten ze in een .json-bestand.
  Er staan dus geen foto's in deze repo.
- De gsm's praten met de laptop via een publieke MQTT-server (geen accounts nodig).
  Lukt de verbinding niet, klik dan in de lobby op "Server" om een andere te kiezen.
