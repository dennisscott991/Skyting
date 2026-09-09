HK416 SKYTETABELLER PWA v2
=========================

Innhold:
- index.html: hovedapp
- data.js: skytetabelldata fra offentlig dokument
- manifest.webmanifest + ikoner: PWA/installasjon
- sw.js: offline-støtte
- KILDE_Skytetabeller_HK416.pdf: original kilde
- .nojekyll: gjør opplasting til GitHub Pages enklere

NYTT I V2
- Mer tydelig instruktørvisning med nøkkeldata øverst i hver øvelse
- Rapportfane
- "Lag rapport fra tabellen/øvelsen"
- Rapportutkast lagres lokalt på enheten
- Mottakers e-postadresse kan skrives inn
- "Åpne i e-post" lager ferdig e-post med emne og rapporttekst
- "Del rapport" bruker enhetens delingsark når nettleseren støtter det
- Offline-cache oppdatert til v2

VIKTIG OM E-POST
En ren statisk PWA kan ikke trygt sende e-post direkte i bakgrunnen uten en ekstern e-posttjeneste/backend. Denne versjonen bruker mailto: og åpner standard e-postapp med alt ferdig utfylt. Brukeren kontrollerer selve Send-handlingen.

INSTALLASJON PÅ IPAD
1. Publiser filene på HTTPS, f.eks. GitHub Pages.
2. Åpne nettadressen i Safari på iPad.
3. Trykk Del > Legg til på Hjem-skjerm.
4. Slå på "Åpne som nettapp".
5. Trykk Legg til.
