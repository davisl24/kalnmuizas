# Kalnmuiža — Heritage Editorial demo

**Aktīvais zars:** `main`  
**Statuss:** dizaina sistēma izstrādāta, **vizuālā desktop/mobile QA vēl nav apstiprināta**.

## Lokāla apskate
Esošā projekta mapē: `git pull origin main`. Atver `index.html` VS Code Live Server, vai palaid `py -m http.server 3000` un apskati `http://localhost:3000`.

Šī ir statiska HTML/CSS lapa ar nelielu JavaScript navigācijas izvēlnei. `npm install` nav vajadzīgs.

## Dizaina lēmumi
- Heritage Editorial, KARLE pilna platuma Hero kompozīcijas princips, oriģināla Kalnmuižas krāsu palete.
- Georgia virsraksti, sans-serif pamatteksts; desktop H1 72 / H2 48 / H3 30 / body 16 px; mobile H1 40 / H2 32 / H3 24 / body 16 px.
- 4/8 px spacing, 1280 px container, 40/20 px malas, 96/64 px sekciju padding.
- Viena primārā darbība: **Jautāt par pieejamību**.
- Vienas lapas sadaļas: Hero, Par vietu, Svinības/Nakšņošana/Atpūta, Atrašanās vieta, Kontakti. Nav tukšas galerijas, atkārtota FAQ vai izdomātu atsauksmju.

## Demo robežas
- `noindex,nofollow`, redzama neoficiālā demo norāde.
- Īsto vietas foto tiesības nav pārbaudītas; izmantoti tikai marķēti vietturi.
- Lietotājs apstiprināja, ka viesu nams darbojas, bet šodienas cenas, precīza ietilpība, atsevišķu pakalpojumu pieejamība un kontaktu aktualitāte vēl jāsaskaņo.
- Pārnešana uz `main` paredzēta lokālai demo apskatei, nevis oficiālai publicēšanai.
- Pirms LIVE nepieciešami faktiskie vizuālie, funkciju un avotu pārbaudes rezultāti.

Aktuālie lēmumi un neatrisinātie jautājumi: [PROJECT_STATE.md](PROJECT_STATE.md).
