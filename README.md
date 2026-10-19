# Kalnmuiža — Heritage Editorial demo

**Repo:** `davisl24/kalnmuizas`  
**Darba zars:** `demo/heritage-editorial-v1`  
**Statuss:** uzlabots un saglabāts GitHub; **browser QA un klienta faktu/foto apstiprināšana vēl nav pabeigta**.

## Kā apskatīt demo
Atver `index.html` no šī zara pārlūkā (lokāli vai HTML priekšskatītājā). HTML/CSS/niecīgs JS bez npm vai datubāzes. Lapa ir marķēta kā **neoficiāls demo** un satur `noindex,nofollow`.

## Dizaina virziens
Apstiprinātais **Heritage Editorial**, izmantojot KARLE projekta pilna platuma Hero un mainīgu teksta/fotolaukumu izkārtojuma principu. Krāsas, saturs un struktūra piemērota Kalnmuižai, nevis kopēta no KARLE.

## Pašreizējās sadaļas
1. Pilna platuma Hero ar primāro CTA
2. Par Kalnmuižu un vēsturiskā piedāvājuma skaitļi
3. Svinību zāle, nakšņošana, pirts un daba
4. Pieejamības precizēšanas process
5. Galerija (tikai atļautu foto vietturi)
6. FAQ (pārbaudīti avoti, neatrisinātie jautājumi atklāti marķēti)
7. Atrašanās vieta
8. Saziņa un footer

## Drošība un robežas
- **Nav izmantotas** svešas/stock/AI bildes, izdomātas atsauksmes vai aktuālu cenu solījumi.
- Reālie foto būs jāsaņem no saimniekiem ar publicēšanas atļauju.
- Lietotājs 2026-10-19 apstiprināja, ka viesu nams šobrīd darbojas. 2023. gadā notikušais ugunsgrēks ir vēsturisks fakts; pakalpojumu faktiskā pieejamība vēl jāsaskaņo.
- Katalogos atšķiras guļvietu skaits un e-pasta rakstība; tāpēc nezināmā nav pasniegta kā fakts.
- Bez kontaktu formas, analītikas vai mārketinga skriptiem. Tāpēc nav pievienots dekoratīvs sīkdatņu baneris.
- Nekas netiek apvienots ar `main` vai publicēts kā oficiālā Kalnmuižas vietne bez atļaujas.

Detalizētas atzīmes un bloķējošie punkti ir [PROJECT_STATE.md](PROJECT_STATE.md).

## Lokāli VS Code

1. Klonē: `git clone https://github.com/davisl24/kalnmuizas.git`
2. Atver mapi `kalnmuizas` VS Code.
3. Atver `index.html` ar Live Server paplašinājumu vai terminalī palaid `python -m http.server 3000` un atver `http://localhost:3000`.

Pirms oficiālas publiskas palaišanas pārbaudi foto atļaujas, faktiskos pakalpojumus un kontaktus. `main` izmantošana lokālai apskatei nav oficiāls production deploy.
