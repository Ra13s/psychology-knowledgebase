# Psühholoogia avastusretk

Eestikeelsed mitmeteemalised ülevaated põnevatest psühholoogiakatsetest, ideedest ja meetoditest. Iga jooks ühendab mitu valitud leidu, sisulise sünteesi ja ajas täienevad teemakirjed.

Uued leiud põhinevad ainult 1. jaanuaril 2026 või hiljem avaldatud materjalil. Vanemad allikad sobivad taustaks ja võrdluseks. Teemad ulatuvad Jungist ja meditatsioonist õppimise, mälu, kujutluse, loovuse ning seni avastamata suundadeni; need on lähtepunktid, mitte otsingu piirid. Iga leid ei pea lõppema eneseabiharjutusega. Varasemad ülevaated säilivad ajaloo osana.

## Sisu

- [intakes/](intakes/) — iga jooksu mitmeteemaline süntees, valitud leiud ja avaldamise seis.
- [topics/](topics/) — ajas täienevad teemakirjed, seosed ja lugemisrajad.
- [stories/](stories/) — terviklikud üksikteema lood koos allikate ja tõenduse selgitusega.
- [sources/processed.jsonl](sources/processed.jsonl) ja [sources/processed/](sources/processed/) — kogu läbitöötatud allikate register korduste vältimiseks.
- [templates/story.md](templates/story.md) — loo soovituslik kuju.
- [AGENTS.md](AGENTS.md) — uurimise, kirjutamise ja avaldamise juhised.

## Lood

- 2026-09-13 — [Kas unenäole saab anda ülesande?](stories/2026-09-13-kas-unenaole-saab-anda-ulesande.md): suhtlus magajaga, mõistatuste helivihjed ja loovuse uurimine uinumisel; mida tulemused näitavad ja mida veel mitte.

## Töökorraldus

Ajastatud ülevaadete käivitaja on ChatGPT, mitte GitHub Actions. Repo säilitab lood, allikad ja teemade ajaloo; lugeja saab ülevaate ka ChatGPT-s.

Enne uut jooksu loetakse värsket `main`-haru, varasemaid intake'e ja teemakirjeid, kogu allikaregistrit ning pooleliolevaid PR-e. Kasutaja 04.10.2026 juhise järgi loob agent sisutäienduse haru ja PR-i, kontrollib lõplikku diffi ning GitHubi nõudeid, merge'ib valmis PR-i ise ja kontrollib sisu `main`ist tagasi. Inimese käsitsi merge'i ootama ei jääda.

Avaldamise käik: `fresh main → branch → PR → diff/checks → merge → verify main → delete merged branch`. Repo automaatne harukustutus on sisse lülitatud. Nõutud kontrolle, review'sid ja muid GitHubi kaitseid järgitakse; konkreetne takistus raporteeritakse. Ajastatud töö avaldamisjuhis kasutab sama käiku.

Repo ei ole isiklik vaimse tervise päevik. Ära lisa vestlusajalugu, isiklikke terviseandmeid ega ligipääsutunnuseid.

## Mitmeteemalised ülevaated

- [2026-09-13 — vari, WOOP, meditatsioon, taipamine ja vestlusküsimused](intakes/2026-09-13.md). Viis valitud leidu kuuest sisuliselt hinnatud suunast; praktilised rakendused ja kõrvale jäänud kandidaadid.
- [2026-09-16 — teadmislüngad, mälupalee, kõndiv loovus, distantseeritud sisekõne ja kehatunnetus](intakes/2026-09-16.md). Viis eri valdkonna leidu ning kaks teadlikult edasi lükatud „mindhack'i” kandidaati.
- [2026-09-23 — AI proovipartner, kognitiivne offloading, kehastatud kujutlus, füsioloogiline sünkroonsus ja lucid-dream vihjed](intakes/2026-09-23.md). Ainult 2026+ uus materjal; viis valitud leidu üheksast hinnatud suunast.
- [2026-09-30 — kompressiivne õppimine, automaatne väärtusõpe, kollektiivne intelligentsus, metakognitsioon ja VR-lucid treening](intakes/2026-09-30.md). Ainult 2026+ uus materjal; viis valitud leidu üheksast hinnatud suunast.

## Teemakirjed

- [Jungi vari ja tunnistamata võimed](topics/sugavuspsuhholoogia/jungi-vari-ja-tunnistamata-voimed.md).
- [WOOP: soov, takistus ja plaan](topics/eesmargid/woop-soov-takistus-plaan.md).
- [Märkamine ja aktsepteerimine meditatsioonis](topics/meditatsioon/markamine-ja-aktsepteerimine.md).
- [N2-uni ja taipamine](topics/uni/n2-uni-ja-taipamine.md).
- [Küsimused ja jätkuküsimused tutvumisvestluses](topics/suhtlemine/kusimused-ja-jatkukusimused.md).
- [Seletusliku sügavuse illusioon](topics/metakognitsioon/seletusliku-sugavuse-illusioon.md).
- [Mälupalee ehk method of loci](topics/malu/malupalee-meetod.md).
- [Kõndimine ja ideede genereerimine](topics/loovus/kondimine-ja-ideede-genereerimine.md).
- [Distantseeritud sisekõne](topics/emotsioonid/distantseeritud-sisekone.md).
- [Kummikäte illusioon ja kehatunnetus](topics/taju-ja-kehatunnetus/kummikae-illusioon.md).
- [AI-proov keeruliseks vestluseks](topics/suhtlemine/ai-proov-keeruliseks-vestluseks.md).
- [Kognitiivne offloading ja sisemine mälu](topics/malu/kognitiivne-offloading-ja-sisemine-malu.md).
- [Interotseptsioon ja vaimne kujutlus](topics/kujutlus/interotseptsioon-ja-vaimne-kujutlus.md).
- [Visuaalne kontakt ja füsioloogiline sünkroonsus](topics/sotsiaalne-kognitsioon/visuaalne-kontakt-ja-fusioloogiline-sunkroonsus.md).
- [Helivihjed ja lucid-dream induktsioon](topics/uni/helivihjed-ja-lucid-dream-induktsioon.md).
- [Kompressiivne õppimine: hubid enne detaile](topics/oppimine/kompressiivne-oppimine-ja-hubid.md).
- [Automaatne väärtuse omistamine ebaolulistele tunnustele](topics/otsustamine/automaatne-vaartuse-omistamine.md).
- [Payoff-info ja kollektiivne intelligentsus](topics/sotsiaalne-oppimine/payoff-info-ja-kollektiivne-intelligentsus.md).
- [Domeenispetsiifiline metakognitsioon](topics/metakognitsioon/domeenispetsiifiline-metakognitsioon.md).
- [VR ja lucid-dream metakognitsioon](topics/uni/vr-ja-lucid-dream-metakognitsioon.md).
