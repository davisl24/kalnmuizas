# PROJECT STATE — Kalnmuiža demo

**Atjaunināts:** 2026-10-19  
**Repo:** `davisl24/kalnmuizas`  
**Galvenais zars:** `main` (demo ir apvienots)  
**Iepriekšējais darba zars:** `demo/heritage-editorial-v1`  
**Statuss:** DEMO IR `main`, GATAVS LOKĀLAI PĀRBAUDEI / VIZUĀLAIS BROWSER QA VĒL NAV VEIKTS / PAKALPOJUMU DATI, FOTOGRĀFIJAS UN CENAS JĀAPSTIPRINA  
**Apstiprināts:** Heritage Editorial + KARLE tipa pilna platuma Hero, asimetriskas satura sadaļas.

## 2026-10-19 — Browser review, 7 anotāciju labojumu kārta
- **[LIETOTĀJA PIEPRASĪTS, IEVIETS DARBA ZARĀ]** Heading Georgia/italic aizstāts ar Manrope 500/600; vārda logo vienkāršots, noņemta dekoratīvā K monogramma un mazais apakšvirsraksts.
- **[LIETOTĀJA PIEPRASĪTS]** "Par Kalnmuižu" pilnvērtīga kompakta sadaļa; vēsturiska ap 200 gadus sena atjaunota ēka bioloģiskās saimniecības teritorijā (Dienvidkurzemes tūrisma avots).
- **[LIETOTĀJA PIEPRASĪTS]** Nakšņošanai un pirtij pievienoti konkrēti CTA uz kontaktiem; svinību CTA saglabāts uz `svinibas.html`.
- **[PAZIŅOTS AVOTS]** Viesunamiem.lv/Kalnmuiža Google Maps maršruta saite norāda uz 56.6821363853466, 21.352693304387003; iframe un directions saite piesaistīta šīm koordinātām, nevis neviennozīmīgam vārdam “Kalnmuiža”. **Vietas/iebrauktuves precizitāte vēl jāapstiprina ar saimniekiem.**
- **[PAZIŅOTS AVOTS]** Pievienots publiskajā Dienvidkurzemes tūrisma un viesunamiem.lv katalogos minētais e-pasts kalnamuizadunalka@inbox.lv. **Pirms LIVE pārbaudīt tā aktualitāti.**
- **[LIETOTĀJA PIEPRASĪTS]** Kontaktu sadaļa un footer atdalīti ar atšķirīgiem foniem, darbības prioritāte: tālrunis → e-pasts/Facebook; footer minimāls.
- **[IEPRIEKŠ LOCKED, SAGLABĀTS]** Konkrētās desktop/mobile H1/H2/H3 vērtības, 4/8 spacing, 1280px container, Heritage Editorial/KARLE kompozīcijas princips, 5 sākumlapas sadaļas.
- **[STATIC QA PASSED]** Saites uz sekcijām, unikāli ID, 1×H1 katrā lapā, CSS balanss, kopīgie stili, noindex un main neizmainīts.
- **[VISUAL QA OPEN]** Jaunais localhost desktop un mobile renderējums, Google iframe faktiskā darbība un vizuālais iespaids jāpārbauda pārlūkā pirms merge.

## 2026-10-19 — KARLE virziens visai Kalnmuižas vietnei
- **[LIETOTĀJA PRECIZĒJUMS]** KARLE projekta vizuālie principi attiecas uz **visu Kalnmuižas vietni**, nevis tikai `svinibas.html`.
- **[BUILT, DARBA ZARĀ]** `index.html` un `svinibas.html` izmanto kopīgu `styles.css`, vienotu header/navigācijas/CTA sistēmu, full-width editorial Hero, pārdomātu tipogrāfiju un ritmu, lielas attēlu zonas un atbilstoši mainīgus satura izkārtojumus. Esošās atrašanās vietas/Google Maps un kontaktu sadaļas saglabātas.
- **[KALNMUIŽAS IDENTITĀTE]** Vēsturiskās muižas, zemes toņu palete, Georgia tipogrāfija, cits satura uzsvars. KARLE repo ir kompozīcijas atsauce, nevis kopējams dizains vai foto avots.
- **[LOCKED SAGLABĀTS]** Visual Direction v1.1 tipogrāfijas izmēri, 4/8 px spacing, 1280 px container, 96/64 px section padding. Neizdomājam foto, cenas, atsauksmes.
- **[PROPOSED]** Jaunas iekšlapas (Nakšņošana, Kontakti) turpmāk būvējamas tajā pašā vizuālajā sistēmā, kad ir pietiekams saturs; šobrīd tās vēl nav izveidotas.
- **[NOT TESTED]** Aktuālā darba zara desktop/mobile renderējums un lietotāja vizuālais apstiprinājums. `main` nav mainīts.

## 2026-10-19 — KARLE dizaina principu pielāgošana “Svinības” lapai
- **[LIETOTĀJA VIRZIENS]** Patīk paša KARLE demo vizuālie principi. Precīzais avots: `davisl24/karle`, `index.html` (nevis publiskā karle.lv vietne).
- **[PROPOSED / BUILT darba zarā]** Pārņemts: full-width Hero ar lielu Georgia virsrakstu un vienu CTA, smalka trīs informācijas vienību josla un pārmaiņus izvietoti lieli attēlu/teksta bloki.
- **[ATŠĶIRĪGA IDENTITĀTE]** Kalnmuižai saglabāti siltie vēsturiskie zemes toņi, savs saturs un pakalpojumu proporcijas. Netiek izmantoti KARLE foto, tekstu materiāli, krāsu palete vai identiski HTML dizaina risinājumi.
- **[LOCKED SAGLABĀTS]** Project Visual Direction v1.1: desktop H1 72 / H2 48 / H3 30, mobile 40 / 32 / 24, 1280 px container, desktop/mobile 40/20 px malas un 96/64 px sekciju ritms.
- **[TESTED STATIC ONLY]** Viens H1, iekšējās saites un CSS pārklājums pārbaudīts; faktiskais desktop/mobile renderējums vēl **NOT TESTED**. Fotogrāfiju vietturi joprojām marķēti kā gaidoši īstas tiesības.
- **[NEXT]** Atvērt jauno `svinibas.html` darba zarā, izskatīt desktop/mobile ekrānuzņēmumus, labot redzamās problēmas, pēc lietotāja apstiprinājuma merge.

## 2026-10-19 — Atsevišķa “Svinības” lapa (jaunākais lēmums)
- **[APSTIPRINĀTS VIRZIENS]** No vienas lapas demo pakāpeniski pārejam uz vairāku lapu mājaslapu: Sākums, Svinības, Nakšņošana, Kontakti/atrašanās vieta. Jaunas lapas būvējam tikai ar atbilstošu saturu.
- **[BUILT — WORK BRANCH]** `feature/svinibas-page-v1`: izveidots `svinibas.html`, izdalīts kopīgais `styles.css`, sākumlapas svinību sadaļā pievienota saite un navigācija. Nav mainīta `main` versija.
- **[PĀRBAUDĪTS AVOTS, NAV KLIENTA APSTIPRINĀJUMA]** Dienvidkurzemes tūrisma katalogā minēta svinību zāle līdz 60 viesiem un nakšņošanas iespējas. Neizvietot cenas kā aktuālu piedāvājumu; guļvietu skaits avotos atšķiras.
- **[NOT TESTED]** Darba zara desktop/mobile pārlūka renderējums un CTA klikšķu faktiskā uzvedība vēl jāpārbauda un jāapstiprina lietotājam. Tikai pēc tam var apsvērt merge uz `main`.
- **[NEXT]** Atvērt `svinibas.html` lokāli, vizuāli izskatīt 1440/390 px, novērst konkrētas problēmas. Pēc apstiprinājuma izlemt Nakšņošanas lapas informācijas apjomu.

## 2026-10-19 — Dizaina sistēma no KESTREL Visual Direction v1.1
- **[APSTIPRINĀTS]** Virsrakstu fonts: Georgia (regular); body: Segoe UI / Arial sans-serif.
- **[APSTIPRINĀTS]** Desktop: H1 72 px / H2 48 px / H3 30 px / body 16 px / secondary 14 px / labels 12 px.
- **[APSTIPRINĀTS]** Mobile ≤760 px: H1 40 px / H2 32 px / H3 24 px / body 16 px.
- **[APSTIPRINĀTS]** Atstarpju ritms: 4/8 px; container 1280 px; lapas malas 40 px desktop, 20 px mobile; sekcijas 96 px desktop / 64 px mobile.
- **[APSTIPRINĀTS]** Saglabāt apstiprināto krāsu paleti, vienas lapas informācijas arhitektūru, full-width Hero un CTA “Jautāt par pieejamību”.
- **[BUILT / NOT VISUALLY TESTED]** CSS konsolidēts vienā sistēmā; noņemti pārrakstošie stili, dekoratīvie numuri un tukši apmales rotājumi. Saglabātas 5 sekcijas: Hero, Par vietu, Iespējas, Atrašanās vieta, Kontakti.
- **[NOT TESTED]** Faktiskais jaunās versijas desktop/mobile renderējums: pārbaude uz localhost vēl jāveic. QA ieteicamie platumi: 360, 390, 768, 1024, 1440 px. Darba rezultātu apstiprina lietotājs pēc vizuālās pārbaudes.

## GitHub stāvoklis un nākamais kontrolpunkts
- 2026-10-19 ar lietotāja apstiprinājumu apvienots Draft PR #1 ar `main` (squash merge `36e9d3d1da72a36e51073def1b5f674106eda484`).
- `main` satur `index.html`, `README.md` un `PROJECT_STATE.md`; demo paredzēts lokālai apskatei, nevis oficiālai produkcijas publicēšanai.
- GitHub koda/enkuru struktūras statiskās pārbaudes ir izpildītas, taču faktiskā `localhost` atvēršana, mobilais/desktop attēlojums un mijiedarbība **nav pārbaudīti**.
- **Tuvākais uzdevums:** `git pull origin main`, atvērt localhost un pārbaudīt virsrakstu hierarhiju, spacing un mobilās sekciju pārejas; labot tikai vizuāli konstatēto.

## Projektam piemērotais apjoms
Vienas lapas neoficiāls viesu nama demo. Galvenais mērķis — palīdzēt potenciālajam pasākuma apmeklētājam saprast vietu un **precizēt pašreizējo pieejamību**. Neveidot vairākas lapas vai neīstu rezervāciju sistēmu bez pamatojuma.

## Ieviests 2026-10-19 pēc Website Guidelines
- [x] Skaidrāks Hero virsraksts un piedāvājuma apraksts (Dunalka, svinību zāle, nakšņošana, pirts) ar katalogu datu atrunu.
- [x] Sticky header un klikšķināms tālrunis; mobilajā/tabletē zvanīšanas CTA redzams ārpus izvēlnes.
- [x] Semantiska `nav > ul > li` izvēlne un klaviatūras fokusa stili.
- [x] Mobilās izvēlnes aizvēršana ar Escape, klikšķi ārpus izvēlnes un izvēloties saiti.
- [x] Trīs reālistiski pieejamības precizēšanas soļi (nesolot atbildes laiku).
- [x] Saīsināti, skaidrāki pakalpojumu apraksti.
- [x] Atkārtotais FAQ izņemts pēc D2/D4 satura redukcijas, lai neatkārtotu pakalpojumu un atrašanās vietas faktus.
- [x] Vienota galvenā CTA formulēšana (Jautāt par pieejamību) un tiešās zvanīšanas iespējas.
- [x] Footer ar navigāciju, telefonu, atrašanās vietu, Facebook un skaidru DEMO statusu.
- [x] Statisks `noindex,nofollow` demo, bez analītikas, marketinga skriptiem un kontaktu formas.
- [x] Bez stock/AI attēliem un bez izdomātām atsauksmēm, skaitļiem, cenām vai pieejamības datumiem.

## 2026-10-19 publisko avotu pārbaude
- **Darbības statuss:** lietotājs 2026-10-19 apstiprināja, ka viesu nams šobrīd darbojas. Šis apstiprinājums pats par sevi nenozīmē, ka visas vēsturiskajos katalogos minētās telpas un pakalpojumi ir pieejami.
- **Zāle:** katalogi min līdz 60 viesiem, bet pašreizējā ietilpība nav apstiprināta.
- **Nakšņošana:** katalogi min 7 istabas; guļvietu skaits atšķiras: 35 un 39.
- **Tālrunis:** +371 29824636 atkārtojas vairākos avotos; jāapstiprina pie saimniekiem.
- **E-pasts:** avotos ir divi atšķirīgi varianti: `kalnmuizadunalka@inbox.lv` un `kalnamuizadunalka@inbox.lv`. Abi jāpārbauda; neviens netiek izvietots lapā.
- **Cenas:** publicētas katalogos, bet šodienas aktualitāte nav zināma; netiek pasniegtas kā spēkā esošas.
- **Fotogrāfijas:** reālu, aktuālu attēlu tiesības nav verificētas. Hero un pakalpojumu blokos saglabāti marķēti vietturi; atsevišķā galerija pagaidām izņemta.

## Gatavības vārti
### Pirms demo gala vizuālā apstiprinājuma
- [ ] Palaist `main` lokāli ar VS Code Live Server vai `py -m http.server 3000`.
- [ ] Pārbaudīt faktiskos mobilos/desktop renderējumus: 320, 390, 768, 1120, 1440 px.
- [ ] Pārbaudīt navigācijas klikšķus un tastatūras darbību ar Enter/Space/Esc, hover/focus un kontrastu.
- [ ] Pārbaudīt iegūto HTML resursu ātrumu (bez attēliem); ar attēliem vēlāk mērīt Core Web Vitals.
- [ ] Lietotāja vizuālais apstiprinājums.

### Pirms reālas publicēšanas
- [x] Lietotājs apstiprināja, ka viesu nams darbojas.
- [ ] Precizēt jaunu pasākumu rezervāciju pieejamību un faktisko telpu/pakalpojumu apjomu.
- [ ] Apstiprināt aktuālo zāles/istabu ietilpību, pakalpojumus, kontaktus un cenu nosacījumus.
- [ ] Iegūt īpašnieka atļauju izmantot konkrētās aktuālās fotogrāfijas.
- [ ] Ievietot optimizētus WebP/AVIF attēlus, korektus `alt` un lazy loading ārpus Hero.
- [ ] Iegūt īstas atsauksmes, ja tādas drīkst izmantot; pretējā gadījumā atsauksmju sadaļu nelikt.
- [ ] Pēc izvēlētā hostinga, reālās datu apstrādes un iesaistītā uzņēmuma datiem sagatavot atbilstošu privātuma informāciju. Sīkdatņu baneris vajadzīgs tikai atbilstoši reālajiem skriptiem/sīkdatnēm, nevis automātiski.
- [ ] Tikai ar atļauju izņemt DEMO marķējumu un `noindex`, pielikt precīzus SEO meta/strukturētos datus un publicēt.
- [x] Lietotājs 2026-10-19 apstiprināja visa demo satura pārnešanu uz `main` lokālai apskatei; apvienošana veiksmīgi notikusi. Tā nav atļauja publicēt oficiālu mājaslapu.

## Galvenie avoti
- https://www.dienvidkurzeme.travel/visainfo/item/aizputes-apkartne/naktsmitnes-aizpute/viesu-nams-kalnmuiza-3/
- https://liepaja.travel/naktsmitnes/viesu-maja-kalnmuiza/
- https://viesunamiem.lv/kalnmuiza
- https://www.liepajniekiem.lv/zinas/novados/dunalkas-pagasta-kalnmuiza-cies-ugunsnelaime/
- `Website-Guidelines(2).docx` (lietotāja iesniegtās darba vadlīnijas)
