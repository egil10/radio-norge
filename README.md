# radio-norge

Kontaktliste over norske radiostasjoner — for utsendelse av albumet
**"Norge til VM"** av **Stoch** (AI-generert musikk, fri bruk).

## Hva er dette?

En kuratert oversikt over så mange norske radiokanaler som mulig — nasjonale,
regionale og lokale — med e-post, telefon, adresse, sosiale medier og
kontaktperson der det er funnet.

Listen brukes til manuell mail merge: send album-en gratis til redaksjoner,
med klar opplysning om at musikken er AI-generert og fri til bruk.

## Filer

| Fil | Innhold |
|---|---|
| `radio-stations.csv` | Hovedlisten: 150+ stasjoner med kontaktinfo |
| `national-networks.md` | Detaljert info om NRK, P4-gruppen, Bauer Media |
| `outreach-template.md` | Ferdige e-post/DM-maler på norsk |
| `sources.md` | Kilder brukt for å bygge listen |

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

## Antall stasjoner i listen

| Kategori | Antall |
|---|---|
| NRK (nasjonal + regional + tematiske) | ~25 |
| P4-gruppen | ~9 |
| Bauer Media (Radio Norge m.fl.) | ~11 |
| Lokalradioer (Norsk Lokalradioforbund) | ~95 |
| Kristne/livssyn-stasjoner | ~10 |
| Student/flerkulturelle | ~6 |
| **Totalt** | **150+** |

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
