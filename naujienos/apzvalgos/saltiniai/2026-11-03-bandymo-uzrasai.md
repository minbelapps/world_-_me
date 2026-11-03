# Ribotas naujienų struktūros bandymas: automatizavimo vertė ir praktinis atsparumas

Autorius: Codex. Tyrimo data: 2026-11-03. Vienkartinis eksperimentas; monitoringas nepaleistas. Tai analitiko užrašai, ne nepriklausomai peržiūrėta ataskaita. Centriniai dokumentai nekeisti, commit nedaromas.

## 1. Ką realiai pasiekė paieška ir kaip atrinkti signalai?

### Esminė išvada

Pasiekti keli 2026 m. spalio 20–26 d. šaltiniai, todėl nėra pagrindo teigti, kad viso 14 dienų lango internetas neprieinamas. Tačiau šio bandymo karo eigos ir Lietuvos kibernetinių incidentų aprėptis menka. Stipriausia gauta medžiaga leidžia nagrinėti automatizavimo diegimo trintį ir pasirengimo virtimą konkrečiais darbais; ji neleidžia spręsti apie bendrą pasaulio saugumo pokytį.

Laiko langas: nuo 2026-10-20 iki 2026-11-03 patikros momento, t. y. slenkantis 14 dienų laikotarpis. Ribinės spalio 20 d. publikacijos be valandos įtrauktos su šia išlyga. Nauja publikacija, naujas įvykis ir senesnius duomenis pristatantis tyrimas atskirti.

Pirmiausia perskaitytas vartotojo nurodytas `deep-research/references/researcher.md`, po jo visi keturi centriniai naujienų dokumentai ir projekto `CODEX.md`. Tyrėjo ciklas taikytas tiesiogiai: šiame bandyme nebuvo tyrimo subagentų ar nepriklausomo peržiūrėtojo. Vartotojo nurodytas vietinis Markdown kelias laikomas galutinio rezultato vieta. Signalai ir žemėlapiai telpa šiame viename faile; centrinėje sistemoje jų atskiri failai nesukurti.

### Patikros žodynas

| Žyma | Ką ji reiškia šiame bandyme |
|---|---|
| Netikrinta | Klausimui neskirta atskira patikra arba nepasiektas reikalingas dokumentas. |
| Ieškota, bet nerasta | Nurodytoje užklausoje negauta tinkamo atsakymo. Tai paieškos rezultatas, ne pasaulio būsenos įrodymas. |
| Šaltinis patvirtina nebuvimą | Konkretus šaltinis savo apimtyje aiškiai praneša apie nebuvimą. Tai nėra universali garantija. |
| Dalinai patikrinta | Pasiekta tik dalis teiginio įrodymų, santrauka arba priklausomas perpasakojimas. |
| Patvirtinta siaura dalis | Tiesiogiai perskaitytas dokumentas patvirtina tiksliai apibrėžtą teiginį; jo priežastys ir platesnis paplitimas gali likti nežinomi. |

Pavyzdys paskutinei nebuvimo kategorijai: robotikos autoriai savo bandyme nepraneša apie bendrą produktyvumo pagerėjimą, išskyrus pasikartojančio kodo užduotį. Tai patvirtina tokį jų tyrimo rezultatą, o ne AI naudos nebuvimą visoje robotikoje. [Tyrimas](https://arxiv.org/html/2610.32636v1)

### Paieškų eiga ir biudžeto apskaita

Skaičiuotas kiekvienas užklausos tekstas ir kiekvienas URL atvėrimas, net jei keli sudėti į vieną įrankio iškvietimą. Iš viso **10 užklausų + 8 atvėrimai = 18 tikslinių veiksmų** per 6 interneto įrankio iškvietimus. Vietinių instrukcijų skaitymas, laikrodis ir failo išsaugojimas į šį skaičių neįtraukti. Paieškos grąžinti papildomi rezultatai nėra atskiri mano vykdyti atvėrimai.

| Nr. | Iteracija / veiksmas | Rezultatas ir ribojimas |
|---|---|---|
| 1 | I: `AI automation business October 2026 after:2026-10-20 before:2026-11-04` | AI valdymo ir sąnaudų publikacijos, du tyrimai, įmonių pranešimai. Paieškos filtrai nelaikyti patvirtintomis datomis. |
| 2 | I: `Europe cyber preparedness Ukraine October 2026 after:2026-10-20 before:2026-11-04` | Regioninio pasirengimo apžvalga, NATO ir ES senesnis kontekstas. Atskiro patikimo naujo karo eigos signalo neišplėtota. |
| 3 | I: `Lithuania resilience defence procurement October 2026 after:2026-10-20 before:2026-11-04` | Dronų pirkimas, pirkimų reformos perpasakojimas, ankstesni investicijų ir pratybų pranešimai. |
| 4 | II: `https://arxiv.org/abs/2610.32636` | Atverta autoriaus santrauka, patikrinta pateikimo data. |
| 5 | II: `https://arxiv.org/abs/2610.34613` | Atverta autoriaus santrauka, patikrinta pateikimo data. |
| 6 | II: [GlobalGov pirkimas](https://globalgov.io/s/lt-lithuania-non-piloted-aircraft-specializuoti-bepilo-iai-orlaiviai-interreg-727343-2026) | **Nepavyko:** įrankis grąžino „not accessible / Internal Error“. Paieškos ištrauka išliko tik kandidatui aptikti. |
| 7 | II: `site.enisa.europa.eu October 2026 threat landscape cyber preparedness` | Rastas rugsėjo 22 d. metinis dokumentas apie 2025 metus. 14 d. incidentų klausimui atsakymo neduoda. |
| 8 | II: `site:kam.lt "2026" "spalio 20" pirkimų` | Bendrame rezultatų pakete tinkamo KAM pirminio reformos patvirtinimo **nerasta**. |
| 9 | II: `"727343-2026"` | Keli pirkimų agregatoriai. Visi remiasi tuo pačiu TED skelbimu; nepriklausomų įvykių nepadaugėjo. Buvo ir pašalinių rezultatų. |
| 10 | II: `https://arxiv.org/html/2610.32636v1` | Pasiektas straipsnio HTML; matomi pramoninis kontekstas, išvados, riboto atvejo metodika. |
| 11 | II: `https://arxiv.org/html/2610.34613v1` | Pasiektas HTML; užfiksuotas bendro ir to paties projekto palyginimų skirtumas bei teksto skaičių neatitikimas. |
| 12 | II: `https://ted.europa.eu/en/notice/-/detail/727343-2026` | **Dalinė nesėkmė:** matomas numeris ir „Competition“, bet ištraukiklis nepateikė pirkimo sąlygų. |
| 13 | II: `site:nksc.lt "2026" "spalio" incidentai` | Bendrame pakete tinkamo NKSC rezultato **nerasta**. Nepatikrina incidentų nebuvimo. |
| 14 | II: `site:gov.pl "2026" "102" "ochrony ludności"` | Senesnė nacionalinė programa ir naujesnis spalio 26 d. vietinis įgyvendinimas. |
| 15 | II: `site:enisa.europa.eu "October" "2026" "exercise"` | Bendrame pakete tinkamo pratybų rezultato **nerasta**; konkretus įvykis nepatvirtintas. |
| 16 | II: `cyber incident October 2026 after:2026-10-20 before:2026-11-04 site:cert.europa.eu` | PHP ir GitLab perspėjimai; taip pat daug senesnių rezultatų. Pasirinktas PHP, GitLab atskirai negilintas. |
| 17 | II: [Lenkijos vietinis įgyvendinimas](https://www.gov.pl/web/olioc/przygtowania-do-realizacji-programu-olioc-2027-2031-na-dolnym-slasku) | Puslapis pasiektas, bet atvėrimo ištraukoje dominavo navigacija; konkretūs skaičiai gauti iš paieškos teksto. |
| 18 | II: `https://cert.europa.eu/publications/security-advisories/2026-018/` | Perskaityta perspėjimo istorija, santrauka ir rekomendacijos. |

Laikrodis tikrintas 10:52:46, 10:53:03, 10:53:22, 10:53:31 ir 10:53:42 UTC (Vilniuje +2 val.). Interneto biudžetas pasiektas maždaug per minutę; tai nėra tariamos šešios minutės naršymo. Likusi darbo dalis skirta III iteracijos sintezei, užrašams ir patikrai. Galutinis laikas pridėtas apačioje.

### Atrankos logika ir atmesti kandidatai

Pasirinkti penki taškai pagal galimą sprendimo reikšmę, konkretaus veiksmo ar rezultato buvimą, datą ir šaltinio pasiekiamumą. Keturi turi tiesiogiai pasiektus pirminius ar institucinius dokumentus, tačiau Lenkijos detalės liko paieškos ištraukos lygmens. Penktas — Lietuvos pirkimas — sąmoningai paliktas silpnesnės patikros būsenos. Tai ne penki nepriklausomai patvirtinti reiškiniai.

AI sąnaudų antraštė apie „89 %“ ir agentų teisių komentarai neįtraukti kaip nustatyti techniniai ar ekonominiai faktai: nepasiektas apklausos originalas ir metodika. Jie tik padėjo suformuluoti patikros klausimus. [Aptikta sąnaudų publikacija](https://www.itpro.com/technology/artificial-intelligence/ais-price-tag-is-starting-to-shape-its-path-through-the-enterprise-89-percent-of-enterprises-have-scaled-back-ai-deployments-over-token-costs-and-theyre-still-struggling-to-track-spending)

Lietuvos pirkimų reformos perpasakojimas nepakeltas į priimtą teisės normą: pirminio dokumento nerasta. [Kandidatas](https://www.adriadefense.com/lithuania-moves-to-accelerate-defense-procurement-and-tighten-supply-chain-rules/)

### Spragos

Paieška daugiausia anglų kalba, su viena lietuviška ir viena lenkiško turinio užklausa. Ekonominės galimybės nagrinėjamos per procesus ir pirkimų paklausą, ne per akcijų kainas ar visos ekonomikos rodiklius. Neatliktas sistemingas Baltijos, Ukrainos, energetikos ar civilinės saugos incidentų auditas. 14 dienų lango pabaiga, ypač spalio 27–lapkričio 3 d., atrinktuose stipresniuose signaluose menkai atstovaujama. Tai duomenų ir atrankos spraga, ne išvada, kad ten nieko nevyko.

## 2. Ką rodo penki atrinkti taškai, jų datos ir prieštaravimai?

### Esminė išvada

Du nauji tyrimai keičia ne būtinai technologijos būseną per šias dvi savaites, o mūsų turimą pagrindą vertinti jos naudą. Pasirengimo srityje vertingesnis konkretus vietinis darbas negu kartojamas nacionalinio biudžeto skaičius. Kibernetinio saugumo perspėjimas suteikia operacinį signalą, tačiau pats savaime nepatvirtina jau įvykusios atakų bangos.

### S1. Robotikos AI: pritaikymas ir mokymasis, o ne automatinė grąža

**Tema / vieta:** pramoninių robotų programavimas, Vokietijos MVĮ AKE Technologies. **Publikacija:** arXiv pateikta 2026-10-23. **Eksperimento dienų datos:** šiame bandyme nenustatytos; publikacijos data jų nepakeičia.

**Pastebėjimas:** autoriai aprašo dviejų darbo dienų atvejį. Bendro produktyvumo pagerėjimo nenustatė, išskyrus labai pasikartojantį kodą; antrą dieną rezultatai gerėjo. Naudojimąsi AI ir agento konfigūraciją keitė kartu, todėl vien mokymosi poveikio izoliuoti negalima. Tai akademinis bendradarbiavimas su tiriama įmone, ne visos pramonės nepriklausomas auditas. **Būsena:** patvirtinta siaura dalis — taip praneša autoriai; duomenys neperanalizuoti, recenzavimo statusas nepatikrintas. [Pirminis tekstas](https://arxiv.org/html/2610.32636v1)

**Interpretacija / kas keičiasi:** praktinės vertės hipotezę verta siaurinti iki aiškiai apibrėžtų pasikartojančių užduočių. Prieš parduodant bendrą „agentą inžinieriui“, tikrinti paruošimo, taisymo ir patikros laiką. **Toliau:** ilgesnis bandymas, tas pats įrankis ir užduoties tipas, atskirai skaičiuojamos mokymo sąnaudos.

### S2. Infrastruktūros kodas: bendras vidurkis slepia kitokią projekto vidaus padėtį

**Publikacija:** 2026-10-25. **Duomenys:** 2025 m. sausio–2026 m. gegužės PR; tai naujai paskelbta analizė apie senesnį laikotarpį.

**Pastebėjimas:** santraukoje „tyliai“ agentų padedami PR priimami dažniau bendrai (87,4 % prieš 78,9 %), bet tų pačių projektų viduje — 4 procentiniais punktais rečiau. Atitinkamuose Terraform palyginimuose autoriai neranda statistiškai aptinkamo tvarumo požymių skirtumo. Tai nėra saugumo ar realios energijos sąnaudų lygybės įrodymas. **Prieštaravimas pačiame tekste:** automatinių botų dalis santraukoje 32,9 %, įvado įnašų sąraše 35,8 %; ši dalis nelaikoma patikimai nustatytu skaičiumi. **Būsena:** dalinai patikrinta stebėjimo analizė, ne priežastinis eksperimentas. [Pirminis tekstas](https://arxiv.org/html/2610.34613v1)

**Interpretacija:** projektų ir užduočių sudėtis gali sukurti patrauklų bendrą rezultatą. Galimybė — matavimas ir kokybės tikrinimas konkrečiame procese. **Toliau:** atskirti agento efektą nuo užduočių pasirinkimo, tikrinti atmetimo priežastis ir priežiūros laiką.

### S3. PHP: perspėjimo sunkumas nėra atakos dažnio matas

**Datos:** CERT-EU istorijoje pradinė publikacija 2026-10-20, atnaujinimai 21 ir 23 d.; puslapio antraštės „Release Date“ — 23 d. Tekstas nurodo pataisas spalio 21 d. 13:30 UTC. Vadinasi, vien viršutinė data nuslėptų įvykio eigą.

**Pastebėjimas:** institucinis perspėjimas aprašo du kritinius nuotolinio kodo vykdymo pažeidžiamumus ir trečią, retai konfigūracijai aktualų vektorių. Rekomenduojama atnaujinti paveiktas sistemas; vien laikinos priemonės nėra visų kelių ištaisymas. Puslapis remiasi PHP ir kitais šaltiniais, tai ne nepriklausomas jų eksperimentų pakartojimas. **Būsena:** patvirtintas perspėjimas; platus realus išnaudojimas šiame bandyme nepatvirtintas. Pats tekstas kalba apie išaugusią tikimybę, ne pateikia nustatytą incidentų skaičių. [CERT-EU](https://cert.europa.eu/publications/security-advisories/2026-018/)

**Interpretacija:** verslo galimybė galėtų būti priklausomybių inventorizacija ir pataisų patikra. Savininko naudojamos PHP sistemos **netikrintos**; nėra pagrindo teigti, kad jo projektas pažeidžiamas. **Toliau:** tikslus naudojamų komponentų sąrašas ir konkrečių tiekėjų ištaisymo patvirtinimai, jei toks darbas būtų atskirai užsakytas.

### S4. Lietuvos policijos dronų pirkimas: paklausos kandidatas su neužbaigta pirmine patikra

**Skelbiama publikacija:** 2026-10-21, paraiškų terminas 2026-11-25; šios datos gautos iš agregatorių. TED pasiektas skelbimo numeris 727343-2026, tačiau sąlygos neišskleistos.

**Pastebėjimas:** agregatoriai aprašo INTERREG projektą LTPL00382 „Budrus ir pasirengęs“ Lietuvos–Lenkijos pasienyje ir dvi dronų komplektų dalis (4–8 ir 1–2). Tai viena skelbimo kilmės šeima, ne keli nepriklausomi patvirtinimai. **Būsena:** dalinai patikrinta; oficialių kiekių, kvalifikacijos ir pakeitimų patikra neužbaigta. [TED](https://ted.europa.eu/en/notice/-/detail/727343-2026), [HelloTender perpasakojimas](https://www.hellotender.eu/lt/viesieji-pirkimai/specializuoti-bepilociai-orlaiviai-interreg-727343-2026)

**Interpretacija:** konkretus pirkimas būtų reikšmingesnis paklausos požymis už bendrą pasirengimo retoriką. Bet tai dar ne pasirašyta sutartis, pristatymas ar veikimo rezultatas. Galimos aptarnavimo ir mokymo nišos yra analitiko hipotezė: jų šis skelbimas šiame bandyme nepatvirtina. **Toliau:** oficialūs dokumentai, dalyvių reikalavimai, sutarties sudarymo ir priėmimo pranešimai.

### S5. Lenkijos vietiniai pasirengimo darbai: įgyvendinimo detalė svarbesnė už pakartotą biudžetą

**Publikacija:** 2026-10-26. **Vizito data:** tekste „pastarosiomis dienomis“, tiksli nenustatyta. **Sutarčių pasirašymo datos:** nenustatytos, kalbama apie 2026 m. darbus.

**Pastebėjimas:** oficiali OLiOC publikacija apie Lubań nurodo tris sutartis, bendrą daugiau nei 1,7 mln. PLN užduočių vertę, dvi avarines gręžtines vandens tiekimo vietas už daugiau nei 821 tūkst. PLN ir perspėjimo sistemos plėtrą už 100 tūkst. PLN. **Būsena:** dalinai patikrinta — institucijos paieškos tekste pateiktas teiginys, ne sutarčių ar užbaigimo aktų auditas. Puslapio atvėrimas įvyko, tačiau naudingo turinio ištrauka buvo ribota. [OLiOC](https://www.gov.pl/web/olioc/przygtowania-do-realizacji-programu-olioc-2027-2031-na-dolnym-slasku)

**Interpretacija:** matome konkrečias funkcijas — vanduo, perspėjimas, sandėliai — į kurias galima orientuoti tolesnę paklausos paiešką. Tai vienos vietovės atvejis, ne įrodytas viso regiono pagreitėjimas. **Toliau:** ar sutartys įvykdytos, ar įranga išbandyta, ar numatytas priežiūros finansavimas.

### Atskirai: senesnio konteksto rinkinys K1–K3

Šie faktai nėra paskutinių 14 dienų naujienos ir nepridedami prie penkių naujų taškų skaičiaus.

- **K1 — Lenkijos programos pagrindas:** spalio 6 d. oficiali publikacija aprašo daugiau nei 102 mlrd. PLN 2027–2031 m. programą, tęsiamą po beveik 34 mlrd. PLN 2025–2026 m. laikotarpio. Nauja spalio 26 d. publikacija šios nacionalinės sumos nesukūrė. Skirtingos trukmės bendrų sumų lyginimas be metinio perskaičiavimo klaidintų. [Oficiali spalio 6 d. publikacija](https://www.katowice.uw.gov.pl/aktualnosci/ponad-102-mld-zl-na-ochrone-ludnosci-rzad-przyjal-program-ochrony-ludnosci-i-obrony-cywilnej-na-lata-2027-2031)
- **K2 — kibernetinių priklausomybių pagrindas:** ENISA puslapis nurodo 2026-09-22 ataskaitą, kurios stebėjimo laikotarpis yra 2025-01-01–12-31. Tai tinka priklausomybių ir paslaugų sutrikimų mechanizmams svarstyti, bet ne nustatyti spalio pabaigos atakų pokytį. Dokumento visas tekstas šiame bandyme neskaitytas. [ENISA teminis puslapis](https://www.enisa.europa.eu/topics/cyber-threats/threat-landscape)
- **K3 — regioninio pasirengimo kryptis:** NATO spalio 19 d. pranešimas aprašo spalio 15–16 d. kasmetinį hibridinių grėsmių simpoziumą. Tai ankstesnės koordinacijos kontekstas; kasmetinio renginio negalima laikyti nauju neįprastos parengties įrodymu. Nepriklausomai incidentai pagal šį pranešimą netikrinti. [NATO](https://www.nato.int/en/news-and-events/articles/news/2026/10/19/nato-allies-and-partners-meet-in-bucharest-to-strengthen-response-to-russias-hybrid-activities)

### Nepriklausomumas ir likę klausimai

S1 ir S2 skirtingos autorių grupės, skirtingi metodai ir tiriamos aplinkos. Tai suteikia dvi skirtingas perspektyvas, bet ne to paties produktyvumo efekto replikaciją. S3 yra perspėjimų grandinė, besiremianti tiekėjo informacija. S4 agregatoriai kartoja TED. S5 ir K1 priklauso tai pačiai Lenkijos valstybinei programai; vietinės detalės papildo mechanizmą, tačiau nėra nepriklausomas nacionalinio biudžeto patvirtinimas.

Neaptikta duomenų nėra teiginys apie nebuvimą: karo logistika **netikrinta giliau**; tinkami NKSC ir ENISA pratybų rezultatai **ieškoti, bet nerasti**; plataus PHP išnaudojimo nebuvimo šaltinis **nepatvirtina**. Nepriklausomos lauko patikros, pirkimų užbaigimo ir klientų mokėjimo už siūlomas nišas įrodymų neturime.

## 3. Kokie ryšiai verti bandymo, kas skirtų scenarijus ir ką taisyti metodikoje?

### Esminė išvada

Vertingiausios dvi darbinės hipotezės: automatizavimo vertė gali slinkti į siaurą pritaikymą ir patikrinamą rezultatą; pasirengimo programos gali kurti paklausą per vietinį funkcijų įgyvendinimą bei priežiūrą. Tai dvi atskiros ryšių grupės, o ne viena pasaulinės krizės istorija. Toliau pateikti mechanizmai ir galimybės yra analitiko išvados iš S1–S5 ir aiškiai atskirto konteksto, ne šaltinių tiesiogiai nustatyti rinkos dėsniai.

### Ryšių rinkinys A: daugiau automatinio veikimo → svarbesnė tikrinimo ekonomika

**Klausimas:** kur mažas vykdytojas galėtų sukurti matuojamą vertę, kai agentas geba atlikti daugiau veiksmų, bet jo naudojimas dar negarantuoja geresnio galutinio rezultato?

| Signalai | Galimas mechanizmas | Kas palaiko / ko trūksta | Prasminga alternatyva |
|---|---|---|---|
| S1 + S2 | Generavimo galimybės susiduria su užduoties kontekstu ir priėmimo procesu. Vertė gali likti dokumentacijos paruošime, siaurose užduotyse ir rezultatų patikroje. | Skirtingi tyrimai rodo konteksto svarbą; jie nematuoja bendros tokios paslaugos rinkos. | Tai laikinai netinkamų įrankių ir ankstyvo naudojimo pasekmė; geresni modeliai ar įprasti šablonai gali panaikinti tarpininko nišą. |
| S2 + S3 | Kodo pakeitimas gali paveikti veikiančią infrastruktūrą; priklausomybių patikra turi apimti tikrą įdiegtą būseną. | IaC analizė ir PHP perspėjimas yra skirtingi taškai. Nėra įrodymo, kad aptariamą PHP problemą sukėlė agentai. | Saugumo priežiūra buvo reikalinga ir iki AI; jos paklausa gali nekilti dėl agentų. |
| S1 + S3, kontekstas K2 | Procesas, kuriame aišku, ką galima automatizuoti ir kaip grįžti po klaidos, gali būti vertingesnis už daugiau automatinių veiksmų. | Tai bendro veikimo modelio hipotezė. Priklausomybių kontekstas senesnis. | Tiekėjų valdomos paslaugos gali šią funkciją įtraukti į esamą kainą. |

**Scenarijus A1 — siauro pritaikymo vertė išlieka.** Per kelias savaites pakartotinai atliekama tokio pat tipo užduotis reikalauja mažiau viso žmogaus laiko, įskaitant peržiūrą ir taisymus. Palaikytų klientų pasirengimas mokėti už konkretų rezultatą ir pakartotinis naudojimas. Silpnintų tik gražesnės demonstracijos, didesnis sukurtų eilučių skaičius ar daugiau nepriimamų pakeitimų.

**Scenarijus A2 — integracija tampa standartine preke.** Standartinis agentas ar paprastas deterministinis įrankis tą patį darbą atlieka panašiai gerai be papildomos priežiūros paslaugos. Skirtų bazinis palyginimas su turimais šablonais ir įrankiais, o ne tik „AI prieš rankinį darbą“.

**Mažas siūlomas bandymas, nepradėtas:** pasirinkti vieną pasikartojantį dokumentų ar duomenų sutvarkymo procesą. Fiksuoti visą laiką, taisymų skaičių, įrankių kainą ir priimto rezultato dalį. Kartoti po mokymosi, rezultatą lyginti ir su paprastu skriptu ar šablonu. Tai tyrimo pasiūlymas, ne jau įrodytas verslas.

**Pokytis nuo ankstesnio vaizdo:** ankstesnio formalizuoto žemėlapio neskaičiau, todėl istorinio sustiprėjimo neteigiu. Šio bandymo viduje po S2 gilinimo pradinis „dažniau priimami PR“ įspūdis pakeistas kontekstiniu vertinimu. Tai realus analitiko išvados pokytis.

**Grįžimo kriterijus:** naujas nepriklausomas ilgalaikis produktyvumo tyrimas arba konkretus savas palyginamas bandymas. Vykdytojas nepaskirtas; joks automatinis priminimas nesukurtas.

### Ryšių rinkinys B: pasirengimo politika → vietiniai pirkimai → veikimo ir priežiūros poreikis

**Klausimas:** ar pasirengimas pereina iš programų į konkrečias perkamas funkcijas, ir kokie požymiai rodytų realų rezultatą?

| Signalai | Galimas mechanizmas | Kas palaiko / ko trūksta | Prasminga alternatyva |
|---|---|---|---|
| K1 → S5 | Daugiametė programa leidžia vietos valdžiai planuoti vandenį, perspėjimą, sandėlius ir slėptuves. | Matomi vietinės programos sutarčių teiginiai, tačiau nėra užbaigimo audito. Tai mišrus naujienos ir senesnio konteksto ryšys. | Nauja komunikacija apie seniau suplanuotus darbus, o ne naujas pasirengimo pagreitėjimas. |
| S4 + S5 | Skirtingose vietose perkamos konkrečios pasirengimo funkcijos; gali rastis mažesnių tiekimo, diegimo ar priežiūros nišų. | Dvi šalys ir skirtingos kilmės programos. Lietuvos šaka patikrinta silpniau; bendras paklausos mastas nežinomas. | Tai keli izoliuoti projektai su dideliais kvalifikacijos barjerais, o ne lengvai pasiekiama rinka mažam tiekėjui. |
| S5 + K2; S3 kaip atskiras techninis pavyzdys | Fizinė parengtis priklauso ir nuo skaitmeninių sistemų veikimo; diegimas be priežiūros gali nekurti tikro tęstinumo. | Bendras techninis mechanizmas tikėtinas, bet S5 sistemų architektūra netikrinta. PHP ryšys su šiomis sistemomis nenustatytas. | Vietiniai sprendimai gali būti autonomiški ir šių konkrečių skaitmeninių priklausomybių neturėti. |

**Scenarijus B1 — nuoseklus pajėgumų kūrimas.** Vėliau matytume sudarytas sutartis, pristatymus, priėmimo bandymus, išmokytus naudotojus ir priežiūros išlaidas. Stiprintų veikimo rezultatai per elektros ar ryšio sutrikimų bandymus. Vien biudžetų ir vizitų publikacijų daugėjimas jo nepatvirtina.

**Scenarijus B2 — komunikacija ir lėtas įgyvendinimas.** Kartojami nacionaliniai skaičiai, bet konkursai nesulaukia pasiūlymų, nutraukiami, atidedami arba neturi eksploatacijos finansavimo. Skirtų tų pačių projektų baigties patikra, ne naujų antraščių skaičius.

**Scenarijus B3 — papildomas grėsmės nulemtas pagreitis.** Jo tikėtumėmės, jei atsirastų nuo ankstesnio plano nukrypstančių terminų, papildomų asignavimų ar naujų skubių administracinių veiksmų, susietų su konkrečiu įvykiu. Dabartinis rinkinys to nenustato. Silpnintų įprastas daugiamečių programų vykdymas pagal anksčiau paskelbtą grafiką.

**Praktinė galimybė, dar ne rekomendacija pirkti įrangą:** susiaurinti iki vienos funkcijos, pavyzdžiui, atsargų apskaitos, įrangos bandymų žurnalų ar vietinio perspėjimo priežiūros, ir tikrinti oficialius pirkimus bei realius naudotojų poreikius. Nei tinkamumas tiekėju, nei pakankama paklausa šiame bandyme neįrodyti. Asmeniniam atsparumui šie taškai siūlo klausimą apie vandens, ryšio ir energijos tęstinumo patikrą; savininko būklė neaudituota.

**Pokytis bandymo viduje:** platus „šalys ruošiasi“ kandidatas po gilinimo suskaidytas į senesnį nacionalinį sprendimą ir naujesnę vietinę įgyvendinimo informaciją. Tai leidžia tirti galimybes neapsimetant, kad visas biudžetas atsirado šią savaitę.

**Grįžimo kriterijus:** S4 pirkimo sutarties arba atšaukimo paskelbimas; S5 darbų užbaigimo ir veikimo duomenys. Lapkričio 25 d. terminas tėra agregatoriaus nurodyta būsima data, kurią pirmiausia reikėtų patikrinti oficialiai. Atsakingas asmuo nepaskirtas.

### Metodikos spragos ir konkretūs patobulinimai

1. **Per platus pirmas paieškos paketas.** Gauta daug pusiau tinkamų rezultatų, o karo eiga liko nuošalyje. Kitą tokio pat dydžio bandymą skirti 3 plačioms užklausoms, 8 pirminių dokumentų atvėrimams, 4 alternatyvų ar prieštaravimų paieškoms ir 3 nesėkmių taisymams. Atskirai rezervuoti bent vieną kryptingą karo logistikos ar administracinių veiksmų patikrą. Tai pasiūlymas, ne pakeista centrinė taisyklė.
2. **Bendri rezultatų paketai blogai rodo nulinius atsakymus.** NKSC ir ENISA pratybų užklausos bendrame pakete nepateikė tinkamų rezultatų. Kitą kartą svarbias „nerasta“ užklausas vykdyti po vieną ir vieną kartą pakeisti formuluotę. Nedaryti išvados apie viso tinklalapio ar laikotarpio tylą.
3. **Įrankio atvėrimas nėra turinio perskaitymas.** TED pateikė tik karkasą, OLiOC — ribotą ištrauką. Įraše turėti atskirus laukus: URL pasiektas; turinys išgautas; faktas rastas tekste; originalus dokumentas patikrintas. TED atveju kitą kartą pirmiau rinktis oficialų atsisiunčiamą skelbimą ar duomenų formatą, jei prieinamas. Nepavykimo neslėpti agregatoriais.
4. **Šaltinio šeima svarbiau už domenų skaičių.** Prie signalo įrašyti kilmės ID, pvz., `TED:727343-2026`, ir grandinę „originalas → perpasakojimai“. Dvi ar trys jo kopijos turi likti vienu pirminiu šaltiniu. Akademiniams darbams atskirai žymėti autorių grupę ir tiriamus duomenis.
5. **Datos turi keturis sluoksnius.** Žymėti įvykį, publikaciją, atnaujinimą ir duomenų laikotarpį. S2 nėra spalio infrastruktūros aktyvumo matas, S3 viršutinė data nėra pradinis perspėjimas, S5 nėra naujas nacionalinės programos patvirtinimas.
6. **Skaičiai gali konfliktuoti ir pirminiame tekste.** S2 32,9 % / 35,8 % neatitikimas rodo, kad pirminis šaltinis nėra automatiškai nuoseklus. Kitą kartą atskirai užrašyti versiją, lentelę ir vardiklį; nepasirinkti patogesnio skaičiaus. Duomenų peranalizavimą daryti tik jei jis pakeistų svarbų sprendimą.
7. **Reikia patikrinti mokumą, ne vien technologinę galimybę.** A ir B rinkinių nišos kol kas hipotezės. Kitas mažas tyrimas galėtų turėti vieną aiškų klausimą: kas jau perka tokią funkciją, kokiu mastu, su kokiais reikalavimais ir iš ko? Be to negalima laikyti jų patvirtintu pajamų planu.
8. **Trūksta bazinės būsenos ir ankstesnių žemėlapių palyginimo.** Šis failas yra pirmas šio bandymo momentinis vaizdas. Kitam palyginimui turėti konkrečius objektus ir rezultatus: sutartis, pristatymas, bandymas, išlaidos, priimtas darbas. „Sustiprėjo“ vartoti tik nurodžius, kuris naujas duomuo pakeitė vertinimą.
9. **Spragų žodyną padaryti privalomu trumpu lauku.** Atskirti „netikrinta“, „ieškota, bet nerasta“, „šaltinis patvirtina nebuvimą“; pastarajam visada nurodyti šaltinio apimtį ir datą. Pridėti „įrankis neišgavo turinio“, kad techninė kliūtis neatrodytų informacijos nebuvimu.
10. **Nereikia užpildyti visų temų fiktyviais signalais.** Toliau palikti matomą karo ir cyber vietinės aprėpties spragą. Senesnį kontekstą naudoti mechanizmams, bet nei jo kiekio, nei naujos publikacijos nelaikyti naujų įvykių skaičiumi.
11. **Nepriklausoma peržiūra neatlikta.** Šiame tekste yra to paties analitiko alternatyvų patikra. Prieš reikšmingą finansinį ar pasirengimo sprendimą kitam peržiūrėtojui pateikti dvi pagrindines hipotezes, jų silpniausią šaltinį ir scenarijų skyrimo kriterijus. Jo vaidmens čia neimituoti.
12. **Du ryšių rinkiniai yra siekiama apimtis, ne rezultatų kvota.** Vartotojas tai patikslino baigiant bandymą. Abu rinkinius palieku dėl apibrėžto pagrindo: A stipriausia dalis yra S1 ir S2 konteksto bei vertinimo trintis, B — tiesioginis K1 ir S5 programos bei vietinio vykdymo ryšys. Vis dėlto A sąsaja su PHP ir B sąsaja su skaitmeniniu tęstinumu yra silpnesnės mechanizmų hipotezės, o ne papildomi patvirtinimai. Jas galima palikti tolesnių klausimų sąraše, nesuteikiant joms tokio pat svorio kaip pagrindinėms jungtims. Lietuvos pirkimo patikros spraga mažina B tarpvalstybinės išvados stiprumą. Kitą kartą po atrankos pirmiausia tikrinti, ar apskritai turime prasmingą jungtį; jei ne — pateikti vieną rinkinį ar atskirus signalus, aiškiai pasakyti, kodėl ryšys nesusidarė. Šis bandymas nepatvirtino nei naujos mokios rinkos, nei bendro pasirengimo pagreičio.

### Galutinės aprėpties būsenos

| Klausimas | Būsena |
|---|---|
| Ar pasiekiami bent keli 14 d. lango šaltiniai? | Taip, tiesiogiai atverti datuoti tyrimai ir CERT-EU perspėjimas. |
| Ar patikrinta visa 14 d. pasaulio naujienų aprėptis? | Ne; netikrinta sistemingai. |
| Ar šiuo laikotarpiu Lietuvoje nebuvo cyber incidentų? | Tokios išvados nėra: ieškota, bet tinkamo NKSC rezultato negauta. |
| Ar vyksta neįprasta nauja karo eskalacija? | Šiame bandyme neįvertinta; pasirinkto rinkinio tam nepakanka. |
| Ar PHP perspėjimas įrodo platų realų išnaudojimą? | Ne; patvirtintas perspėjimas, mastas netikrintas. Tai nėra masto nebuvimo įrodymas. |
| Ar AI visur gerina arba blogina produktyvumą? | Nenustatyta. S1 aprašo ribotą atvejį, S2 — konteksto veikiamą stebėjimą. |
| Ar naujai rastas dokumentas gali patvirtinti ankstesnės hipotezės nebuvimą? | Tik siaurai: S1 autoriai praneša neradę bendro pagerėjimo savo bandyme. |
| Ar atrastos galimybės jau turi mokančių klientų? | Netikrinta. |
| Ar sukurtas nuolatinis monitoringas arba pakeista centrinė struktūra? | Ne; sukurtas tik šis užsakytas eksperimento failas. |

### Užbaigimo laikas

Tekstas ir failo buvimas patikrinti 2026-11-03 10:57:59 UTC (12:57:59 Vilniuje), nuo pirmojo laikrodžio patikrinimo — 5 min. 13 sek. Po šios patikros įtraukta paskutinė vartotojo pastaba apie ryšių kvotą; papildomų interneto veiksmų nedaryta. Pabaigos laikrodis fiksuojamas galutinėje patikroje. Apytikris 6–8 min. biudžetas yra viršutinės darbo apimties orientyras, ne priežastis dirbtinai tęsti paiešką.

Galutinė turinio struktūros patikra: 10:58:26 UTC (12:58:26 Vilniuje), praėjo 5 min. 40 sek. Patvirtinta, kad failas sukurtas nurodytoje vietoje, turi tris pagrindines dalis, paieškos žurnalą, nuorodas, nebuvimo būsenų skirtį ir kvotos savikritiką. Naršymo apimtis liko 18 veiksmų; darbas baigtas šiek tiek greičiau už apytikrį laiko orientyrą.
