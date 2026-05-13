# Maler for utsendelse — "Norge til VM" av Stoch

> Husk: vær åpen om at musikken er AI-generert.
> Det er både etisk riktig og treffer redaksjons-tonen i Norge bedre.

---

## Mal 1 — E-post til norsk lokalradio (anbefalt)

**Emne:** Gratis VM-album fra Stoch — fri bruk for {{station_name}}

```
Hei {{editor_first_name}}!

Vi vil gjerne sende dere et nytt album: "Norge til VM" av Stoch.

Bakgrunn: vi har laget et stemningsalbum med Norge-fotballfeber inn mot
VM. Hele albumet er AI-generert — vi er helt åpne om det — og vi gir
{{station_name}} fri og rettighetsfri bruk: spill det i programmer,
bruk det som jingles/bumpers, klipp utdrag til sosiale medier, eller
del videre. Ingen krav, ingen TONO-fakturaer fra oss.

Albumet ligger på Spotify som "Stoch — Norge til VM":
[lenke]

Vi sender også WAV-filer/cover om dere vil ha det:
[WeTransfer-lenke]

Stikkord: Norge, VM, lagånd, hits-vennlig, ca. 3 min per spor.

Hvis dere spiller noe og vil ha en kommentar fra oss, er det bare å si
fra. Lykke til med radioen, og heia Norge til VM!

Mvh
Egil Furre
egilfure@gmail.com
[telefon]
```

---

## Mal 2 — Til store nasjonale (NRK, P4, Bauer)

**Emne:** Musikksubmission — Stoch "Norge til VM" (AI, transparent, lisensfri)

```
Hei musikkredaksjonen,

Sender inn albumet "Norge til VM" av Stoch til vurdering.

For full åpenhet: musikken er AI-generert. Vi opplyser om dette i
metadata, på Spotify, og overalt vi nevner utgivelsen — etter samme
praksis som flere norske artister har tatt i bruk det siste året.

Vi er klar over at AI-musikk håndteres ulikt fra kanal til kanal.
Vi ber dere ikke om noe spesielt — bare at dere lytter og vurderer
på vanlig vis. Vi gir også fri bruk uten royalty-krav fra vår side
om dere vil bruke spor som vignett/bumper/sosiale-medier-innhold.

Albumet er tematisk: håndhevelse, Norge-fotball, VM-stemning.

Spotify: [lenke]
WAV + cover (3000x3000): [WeTransfer-lenke]
Komponist / produsent / metadata: vedlagt tekstfil.

Tilgjengelig for spørsmål når som helst.

Mvh
Egil Furre
egilfure@gmail.com
```

---

## Mal 3 — Kort Instagram/Facebook DM

```
Hei {{station}}! 👋⚽

Har laget et VM-album, "Norge til VM" av Stoch — AI-generert
(transparent) og helt fri til bruk for dere.

Vil dere ha WAV-er + cover, eller bare Spotify-lenken?

Heia Norge! 🇳🇴
```

---

## Mal 4 — Brukertips-skjema (når stasjonen ikke har e-post men har "tips oss"-form)

```
Hei!

Jeg vil tipse om et nytt album som passer inn mot VM:
"Norge til VM" av Stoch (AI-generert, fri bruk).

Spotify: [lenke]

Hvis musikkredaksjonen vil ha WAV-filer kan dere svare på denne
meldingen eller skrive til egilfure@gmail.com.

Vh Egil Furre
```

---

## Sosiale handles per stasjon

Se `radio-stations.csv` kolonne `social`.

Format i CSV: `fb:handle / ig:handle / tt:handle / tw:handle / li:slug`

For DM-utsendelse: filtrér på rader hvor `social` ikke er tom,
hent fb/ig-handles, send Mal 3.

---

## Sjekkliste før første batch

- [ ] Spotify-lenke fungerer fra inkognito
- [ ] Cover er 3000x3000 (krav fra NRK Bidra)
- [ ] WeTransfer-link med WAV varer 7+ dager
- [ ] Du har test-sendt til egen e-post først (HTML, linker, bilder OK)
- [ ] "AI-generert"-merkingen er synlig i metadata og e-post
- [ ] Avsender-domene er ikke nyregistrert (havner i spam)
- [ ] Du sender i puljer (50-100 per gang) for å unngå spam-filter
- [ ] Du har en SPF/DKIM-godkjent e-postadresse hvis du ikke sender via Gmail
- [ ] Du har en "unsubscribe / ikke send mer"-linje (god skikk)

---

## Sortert rekkefølge (anbefalt utsendingsorden)

1. **Først:** NRK Bidra-portal + de fem NRK-musikksjefene
   (P1/P2/P3/P13/Folkemusikk) — kvalitetsstempel
2. **Deretter:** musikk@p4.no + hei@radionorge.no — dekker store deler av
   FM/DAB-Norge
3. **Så batch 1 av lokalradioer:** alle med eksplisitt verifisert
   e-post i CSV (~50 stasjoner)
4. **Batch 2:** lokalradioer med fallback-e-poster (post@domene)
   — forvent ~10-15% bounce
5. **Batch 3:** DM på Instagram/Facebook til de uten e-post
