# musikk_anbefalinger

## Kjente utfordringer

**Spotify mangler på song.link for noen låter**
song.link (Odesli) matcher automatisk låter på tvers av plattformer, men treffer ikke alltid. Alle tre testlåtene finnes på Spotify, men vises ikke på song.link-siden. Mulig løsning: legg til en Spotify-søkelenke som fallback, men krever at vi henter låttittel og artist fra Apple Music (ekstra API-kall).
