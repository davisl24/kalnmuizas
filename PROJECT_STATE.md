# PROJECT STATE — Kalnmuiža demo

**Atjaunināts:** 2026-10-19
**Repo:** `davisl24/kalnmuizas`
**Darba zars:** `demo/heritage-editorial-v1`
**Statuss:** BUILT / BROWSER QA NOT TESTED / APPROVAL PENDING
**Dizaina virziens:** A — Heritage Editorial (apstiprināts). 2026-10-19 apstiprināta KARLE pilna platuma Hero kompozīcijas principa pārnese.

## Apstiprinātais dizains
- Viena lapa ar sešām galvenajām sadaļām: Hero; Par vietu; Iespējas (svinību zāle, nakšņošana, pirts un daba); Galerija; Atrašanās vieta; Kontakti.
- Pilna platuma Hero (KARLE kompozīcijas princips), mainīgs attēlu/teksta ritms, lielas editorial fotolaukumu proporcijas; nevis KARLE dizaina vai satura kopija.
- Silta, atturīga editorial tipogrāfija un krāsu sistēma.
- Tikai īsti Kalnmuižas attēli ar atļauju; pašlaik ir tikai tekstuāli vietturi.
- Bez neīstas rezervācijas sistēmas. Esošais CTA ir zvanīšanas saite ar skaidri nosauktu mērķi.
- DEMO marķējums un `noindex,nofollow`; nekas nav publicēts kā oficiālā vietne.

## GitHub izolācija
Jaunais repozitorijs ir atsevišķs no Kestrel un citiem projektiem. `main` satur tikai README; demo atrodas darba zarā.

## Faktu riski un neatrisinātie jautājumi
2023. gada ziņu publikācijā minēts ugunsgrēks Kalnmuižā Dunalkā. Vecākos tūrisma katalogos norādītā nakšņošana, zāles ietilpība un atpūtas iespējas nav automātiski spēkā šodien.

Pirms atļaujas publicēt kā oficiālu vietni jānoskaidro:
1. Vai viesu nams šobrīd darbojas un pieņem pasākumus?
2. Vai zāle joprojām ir līdz 60 viesiem? Vai joprojām ir 7 istabas?
3. Kuri kontakti un cenas ir aktuāli?
4. Kurus aktuālos foto drīkst izmantot, un ar kādu atļauju?

## Pārbaudes
- [x] Statiskā HTML struktūra, navigācijas enkuri, UTF-8, LV, responsīvās CSS media queries (koda pārbaude no avota).
- [x] 2026-10-19: atkārtota statiskā pārbaude: nav dublētu ID vai bojātu iekšējo enkuru, CSS iekavas sabalansētas, noindex saglabāts, nav ārējo attēlu vai skriptu.
- [x] Nav ārējo skriptu, izsekošanas vai fiktīvu rezervācijas formu.
- [x] GitHub darba zars, nošķirts no Kestrel.
- [ ] Reāls desktop/mobile browser QA (320, 390, 768 un 1440 px).
- [ ] Faktisko pakalpojumu apstiprinājums.
- [ ] Foto atļaujas un attēlu izvietošana.
- [ ] Lietotāja apstiprinājums pirms apvienošanas/publicēšanas.

## Atsauces
- https://www.dienvidkurzeme.travel/visainfo/item/svinibu-vietas/svinibu-vietas-1/viesu-nams-kalnmuiza-6/
- https://www.facebook.com/Kalnmuiza
- https://www.liepajniekiem.lv/zinas/novados/dunalkas-pagasta-kalnmuiza-cies-ugunsnelaime/
