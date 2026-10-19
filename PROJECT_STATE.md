# PROJECT STATE — Kalnmuiža demo

**Atjaunināts:** 2026-10-19  
**Repo:** `davisl24/kalnmuizas`  
**Darba zars:** `demo/heritage-editorial-v1`  
**Statuss:** IMPLEMENTĒTS (saturs/UX) / BROWSER QA NAV VEIKTS / KLIENTA FAKTI JĀAPSTIPRINA  
**Apstiprināts:** Heritage Editorial + KARLE tipa pilna platuma Hero, asimetriskas satura sadaļas.

## Projektam piemērotais apjoms
Vienas lapas neoficiāls viesu nama demo. Galvenais mērķis — palīdzēt potenciālajam pasākuma apmeklētājam saprast vietu un **precizēt pašreizējo pieejamību**. Neveidot vairākas lapas vai neīstu rezervāciju sistēmu bez pamatojuma.

## Ieviests 2026-10-19 pēc Website Guidelines
- [x] Skaidrāks Hero virsraksts un piedāvājuma apraksts (Dunalka, svinību zāle, nakšņošana, pirts) ar katalogu datu atrunu.
- [x] Sticky header un klikšķināms tālrunis; mobilajā/tabletē zvanīšanas CTA redzams ārpus izvēlnes.
- [x] Semantiska `nav > ul > li` izvēlne un klaviatūras fokusa stili.
- [x] Mobilās izvēlnes aizvēršana ar Escape, klikšķi ārpus izvēlnes un izvēloties saiti.
- [x] Trīs reālistiski pieejamības precizēšanas soļi (nesolot atbildes laiku).
- [x] Saīsināti, skaidrāki pakalpojumu apraksti.
- [x] FAQ par darbības statusu, 60 viesu zāli, nakšņošanu, cenu nenoteiktību un atrašanās vietu.
- [x] Vienota galvenā CTA formulēšana (Jautāt par pieejamību) un tiešās zvanīšanas iespējas.
- [x] Footer ar navigāciju, telefonu, atrašanās vietu, Facebook un skaidru DEMO statusu.
- [x] Statisks `noindex,nofollow` demo, bez analītikas, marketinga skriptiem un kontaktu formas.
- [x] Bez stock/AI attēliem un bez izdomātām atsauksmēm, skaitļiem, cenām vai pieejamības datumiem.

## 2026-10-19 publisko avotu pārbaude
- **Darbības statuss pēc 2023. gada ugunsgrēka:** nav neatkarīgi apstiprināts. Uzskatāms par būtisku bloķējošu faktu pirms oficiālas publicēšanas.
- **Zāle:** katalogi min līdz 60 viesiem, bet pašreizējā ietilpība nav apstiprināta.
- **Nakšņošana:** katalogi min 7 istabas; guļvietu skaits atšķiras: 35 un 39.
- **Tālrunis:** +371 29824636 atkārtojas vairākos avotos; jāapstiprina pie saimniekiem.
- **E-pasts:** avotos ir divi atšķirīgi varianti: `kalnmuizadunalka@inbox.lv` un `kalnamuizadunalka@inbox.lv`. Abi jāpārbauda; neviens netiek izvietots lapā.
- **Cenas:** publicētas katalogos, bet šodienas aktualitāte nav zināma; netiek pasniegtas kā spēkā esošas.
- **Fotogrāfijas:** reālu, aktuālu attēlu tiesības nav verificētas. Hero un galerijā saglabāti atklāti marķēti vietturi.

## Gatavības vārti
### Pirms demo dizaina apstiprināšanas
- [ ] Pārbaudīt faktiskos mobilos/desktop renderējumus: 320, 390, 768, 1120, 1440 px.
- [ ] Pārbaudīt navigācijas klikšķus un tastatūras darbību ar Enter/Space/Esc, hover/focus un kontrastu.
- [ ] Pārbaudīt iegūto HTML resursu ātrumu (bez attēliem); ar attēliem vēlāk mērīt Core Web Vitals.
- [ ] Lietotāja vizuālais apstiprinājums.

### Pirms reālas publicēšanas
- [ ] Pārliecināties, ka viesu nams darbojas un ir gatavs jaunām rezervācijām.
- [ ] Apstiprināt aktuālo zāles/istabu ietilpību, pakalpojumus, kontaktus un cenu nosacījumus.
- [ ] Iegūt īpašnieka atļauju izmantot konkrētās aktuālās fotogrāfijas.
- [ ] Ievietot optimizētus WebP/AVIF attēlus, korektus `alt` un lazy loading ārpus Hero.
- [ ] Iegūt īstas atsauksmes, ja tādas drīkst izmantot; pretējā gadījumā atsauksmju sadaļu nelikt.
- [ ] Pēc izvēlētā hostinga, reālās datu apstrādes un iesaistītā uzņēmuma datiem sagatavot atbilstošu privātuma informāciju. Sīkdatņu baneris vajadzīgs tikai atbilstoši reālajiem skriptiem/sīkdatnēm, nevis automātiski.
- [ ] Tikai ar atļauju izņemt DEMO marķējumu un `noindex`, pielikt precīzus SEO meta/strukturētos datus un publicēt.
- [ ] `main` nav jāmaina bez lietotāja apstiprinājuma.

## Galvenie avoti
- https://www.dienvidkurzeme.travel/visainfo/item/aizputes-apkartne/naktsmitnes-aizpute/viesu-nams-kalnmuiza-3/
- https://liepaja.travel/naktsmitnes/viesu-maja-kalnmuiza/
- https://viesunamiem.lv/kalnmuiza
- https://www.liepajniekiem.lv/zinas/novados/dunalkas-pagasta-kalnmuiza-cies-ugunsnelaime/
- `Website-Guidelines(2).docx` (lietotāja iesniegtās darba vadlīnijas)
