# radio-norge

Kontaktliste for å gjøre **"Norge til VM"** av **Stoch** viralt
(AI-generert album, fri bruk).

## Hva er dette?

Kuratert kontaktdirektorat over hele økosystemet som kan spille,
dele eller dekke albumet inn mot VM 2026:

- 🇳🇴 **Radiostasjoner** — nasjonale, regionale, lokale (150+)
- ⚽ **Fotballklubber** — Eliteserien, OBOS-ligaen, NFF, supporterklubber
- 🍺 **Bars & fan zones** — ~90 steder som viser VM på storskjerm
- 🎧 **Spotify-kuratorer** — inkl. Digster Norge sin "🇳🇴 NORGE TIL VM 2026 ⚽️"
- 📰 **Sportsmedier, podkaster, kulturpresse, tech-presse**

Brukes til manuell mail merge — send albumet gratis ut med åpenhet om AI.

## Filer

| Fil | Innhold |
|---|---|
| ⭐ `mailmerge.csv` | **Ren mail-merge-fil** — email, first_name, station_name, region, type — 230+ kontakter |
| `radio-stations.csv` | Radio: 150+ stasjoner med full kontaktinfo |
| `football-contacts.csv` | NFF, Eliteserien, OBOS-ligaen, supporterklubber |
| `bars-and-fanzones.csv` | ~90 bars/fan zones for VM 2026 |
| `national-networks.md` | Detaljert: NRK, P4-gruppen, Bauer Media |
| `media-and-playlists.md` | Spotify-kuratorer, podkaster, sportsmedier, kultur, tech |
| `outreach-template.md` | Ferdige e-post/DM-maler på norsk |
| `sources.md` | Kilder |

## CSV-felter

```
name, type, owner_group, region, website, primary_email, secondary_email,
phone, address, social, editor, notes
```

Type kan være: `national-public`, `national-commercial`,
`national-public-regional`, `regional`, `local`, `group-hq`,
`industry-org`, `music-archive`.

## Brukstips

1. **Filtrer etter `type`** — start med `national-*` for største rekkevidde,
   eller `local` for mer personlig respons (lokalradioer spiller ofte gjerne
   AI/uavhengig musikk uten gatekeeping).
2. **Mail merge** — bruk `primary_email` som hovedkolonne, `name` og
   `editor` som personalisering.
3. **Konsern-effekter** — Jærradiogruppen eier 9 stasjoner. Radioene-gruppen
   eier 7. P4-gruppen eier 9+ kanaler. Bauer Media eier 8+ kanaler.
   Du treffer mange ved å skrive til konsern-redaktørene, men ofte gir det
   bedre effekt å skrive til hver stasjon individuelt.
4. **NRK-musikkinntak** — send via `bidra.nrk.no/musikkinntak` (de tar inn
   WAV/FLAC + cover 3000x3000 i digitalt musikkarkiv). I tillegg send
   personlige e-poster til P1/P2/P3-musikkprodusentene.
5. **P4-gruppen** — én enkelt adresse `musikk@p4.no` dekker hele konsernet.

## Antall kontakter i listen

| Kategori | Antall |
|---|---|
| NRK (nasjonal + regional + tematiske) | ~25 |
| P4-gruppen | ~9 |
| Bauer Media (Radio Norge m.fl.) | ~11 |
| Lokalradioer (Norsk Lokalradioforbund) | ~95 |
| Kristne/livssyn-stasjoner | ~10 |
| Student/flerkulturelle | ~6 |
| NFF (kommunikasjon, presse, sosiale medier) | ~11 |
| Eliteserien klubber | 16 |
| OBOS-ligaen klubber | 16 |
| Supporterklubber (Oljeberget, Klanen, Bataljonen ...) | ~6 |
| Bars / fan zones (Oslo/Bergen/Trondheim/Stavanger ++) | ~90 |
| Sportsmedier (NRK Sport, TV 2, VG, Dagbladet, AP, Nettavisen ...) | ~12 |
| Fotballpodkaster (Rabona, Fotballrådet, TV 2, NRK ...) | ~7 |
| Spotify-spillelister/kuratorer (Digster, Filtr, Topsify ...) | ~8 |
| Kultur- & tech-presse | ~10 |
| **Totalt** | **~320+** |

## Vær åpen om AI

Anbefalt åpningssetning på alle e-poster:

> "Hei! Vi sender dere albumet *Norge til VM* av Stoch — generert med AI,
> og fritt til å spille for redaksjonen, både i programmer og på sosiale
> medier. Vi er helt åpne om at musikken er AI-laget."

Dette respekterer redaksjonell etikk (Vær Varsom-plakaten), og de fleste
musikksjefer setter pris på ærligheten.

## Disclaimer

Kontaktinformasjonen er hentet fra offentlige nettsider mai 2026.
Noen e-poster (de uten eksplisitt verifisering) er konstruert etter
mønster `post@domene.no` — det er den vanligste praksisen for norske
lokalradioer, men sjekk leveringsstatus etter første utsendelse.
