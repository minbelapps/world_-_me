# Naujienų stebėjimo ir analizės struktūra

Atnaujinta 2026-11-03. Šiame faile – naujienų temos, aplinkos stebėjimas ir požymių bei ryšių vertinimas. Visa centrinė sistema aprašyta [SISTEMOS-STRUKTURA.md](../SISTEMOS-STRUKTURA.md).

## 1. Paskirtis ir darbo vietos

Kaupti pavienius signalus, sieti juos tarp temų ir laike, kurti kelias galimas interpretacijas ir sekti, kaip jos keičiasi. Nauda gali būti tiek pastebėta galimybė, tiek rizika, tiek pagrįstas sprendimas kol kas nieko nekeisti.

Signalai saugomi [signalai/](signalai/README.md), datuoti ryšių žemėlapiai – [zemelapiai/](zemelapiai/README.md), apžvalgos ir tyrimai – [apzvalgos/](apzvalgos/README.md). Šie įrašai susiejami nuorodomis, o ne kopijuojami į kiekvieną žemėlapį iš naujo.

## 2. Analitiko ir peržiūrėtojo paskirtis

Aplinkos ir galimų krypčių analitikas renka bei interpretuoja signalus pagal sutartas temas ir išteklių ribas. Rezultatų peržiūrėtojas tikrina svarbias išvadas, alternatyvas, neatitikimus ir duomenų spragas; koordinatorius sieja jas su mūsų tikslais. Savininkas sprendžia dėl įsipareigojimų ir išteklių.

Tai vaidmenys, o ne jau veikianti nuolatinė tarnyba. Konkrečiai užduočiai nurodome apimtį, atsakingą vykdytoją, laiko ribą ir peržiūros momentą. Esant mažiems ištekliams, dalis signalų tik išsaugoma vėlesniam svarstymui.

## 3. Požymiai, galimi ryšiai ir pradinės temos

### Ne tik faktų suvestinė: požymių ir galimų ryšių žemėlapis

Savininko patikslinimas: pavienes akivaizdžias naujienas jis dažnai randa pats. Analitiko papildoma vertė – pastebėti ne taip ryškius požymius, pasikartojimus, laiko seką ir ryšius tarp skirtingų temų. Galimas loginis ryšys yra tinkamas tyrimo rezultatas net tada, kai jis dar neįrodytas. Jį vadiname hipoteze, o ne faktu. „Ryšys neįrodytas“ nėra pakankama išvada, jei nepaaiškinta, ką vis dėlto leidžia svarstyti turimi požymiai.

Analizė turi laikyti atskirai tris dalykus: **kas pastebėta, kaip pastebėjimai galėtų būti susiję ir kokią galimą raidą tai leistų svarstyti.** Nereikalaujame iš pradžių įrodyti kiekvieno smulkaus pastebėjimo, kad jį apskritai išsaugotume. Kartu nepadarome jo teisingu vien todėl, kad jis tinka įdomiam paaiškinimui. Tikrinimo sąnaudos auga pagal galimo sprendimo svarbą, ne vien įrašo neįprastumą.

#### Ką išsaugome apie signalą

- Temą, vietą, pastebėjimo / įvykio datą ir kada apie jį sužinojome.
- Trumpą stebėjimą ir kilmę: tiesiogiai matyta, savininko pasakyta, oficialus dokumentas, publikacija ar perspausdinimas.
- Kas atrodo pasikeitę, su kuo lyginame ir ar turime ankstesnių duomenų. Jei jų nėra, žymime „atrodo neįprasta“, ne „įrodytai padaugėjo“.
- Patikros būseną ir neaiškumus. Nepatikrintas signalas nėra nei automatiškai atmetamas, nei pripažįstamas faktu.
- Su kokiais kitais signalais jį siejame, kodėl ir kada reikėtų peržiūrėti.

Išsaugoma ne tik naujiena, bet ir **vertinimų istorija**. Ankstesnio žemėlapio nepakeičiame taip, tarsi dabartinę išvadą žinojome nuo pradžių. Pakartotinė sena naujiena nėra naujas nepriklausomas signalas, nors jos išplitimas gali būti atskiras informacijos sklaidos reiškinys.

#### Kaip kuriame ryšius

Ryšio įrašas turi paprastą paaiškinimą: kas su kuo galėtų būti susiję, koks galimas mechanizmas ir kokios prielaidos dar trūksta. Atskirti bendrą laiką, bendrą šaltinį, panašų veiksmą ir numanomą priežastinį ryšį. Tai nėra tas pats. Daug priklausomų pranešimų gali atspindėti vieną šaltinį; nepriklausomų skirtingų požymių sutapimas gali būti vertas gilesnės patikros.

Kiekvienam svarbesniam paaiškinimui užrašome bent vieną prasmingą alternatyvą ir kokių kitų požymių tikėtumėmės, jei jis teisingas. Taip pat – kas jį silpnintų. Jei kiekvieną galimą rezultatą galima paskelbti tos pačios hipotezės patvirtinimu, reikia patikslinti pačią hipotezę.

Ne visi ryšiai turi vienodą vertę. Žymime, ar ryšys tiesiog galimas, ar jau turi papildomų nepriklausomų požymių. Neskiriame išgalvoto procento vien tam, kad vaizdas atrodytų tikslus. Mažai informacijos nėra savaime nei ramybės, nei artėjančios nelaimės įrodymas; gali reikšti poreikį tiksliau stebėti konkretų dalyką.

#### Kaip žemėlapis keičiasi

Kitoje peržiūroje žymime: naujas signalas, pasikartojimas, sustiprėjęs ryšys, susilpnėjęs ryšys, prieštaraujantis duomuo, paaiškintas reiškinys arba nebeaktualus vertinimas. Ataskaita turi parodyti ne tik dabartinį vaizdą, bet ir kas jame pasikeitė bei kodėl.

Rezultatas gali būti keli konkuruojantys scenarijai ir konkretus stebėjimo klausimas, o ne viena galutinė priežastis. Pirmiausia siūlome, ką verta stebėti ar kokį mažą bandymą atlikti; didesnį veiksmą atskirai sprendžiame pagal jo kainą ir riziką.

#### Savininko pavyzdžių paskirtis

Pokalbyje pateiktos atsargų rekomendacijos, pratybos, institucijų pasirengimas ryšio ar elektros sutrikimams, parduotuvių atsargų pokyčiai, politiniai pareiškimai, rinkimai, skaitmeninės tapatybės ir valiutų planai, streikai bei kibernetiniai sutrikimai iliustruoja, kokius skirtingus taškus būtų galima sieti. Šiame dokumentavimo žingsnyje konkrečių pranešimų netikriname ir jų bendro ryšio nenustatome. Atsitiktinumas, bendros ilgalaikės priežastys, sklaidos efektas ar sąmoningas koordinavimas yra skirtingi galimi paaiškinimai; vien neįprastumas nepasirenka vieno iš jų.

Savininko paminėtas Rusijos pasirengimo prieš puolimą pavyzdys paaiškina metodą: mažos administracinės ar organizacinės detalės kartais gali pasakyti daugiau nei viešas vertinimas, kad veiksmas „neapsimoka“. Šio pasakojimo teisinės ar istorinės detalės čia papildomai nepatikrintos; pamoka nėra laikyti kiekvieną mažą detalę slapto plano įrodymu, o jos neprarasti vien dėl to, kad ji nėra pagrindinė antraštė.

#### Pradinės naujienų temos ir darbo ribos

Savininkas pritarė šiam pradiniam temų rinkiniui ir papildė jį karu, kibernetinėmis atakomis, pavojaus signalais bei pasirengimo pavojams požymiais. Tai sutarta stebėjimo kryptis, ne teiginys, kad visos temos jau nuolat stebimos.

| Tema | Ko ieškome |
|---|---|
| Dirbtinis intelektas ir automatizavimas | Naujų galimybių, praktinio naudojimo, kainų, ribojimų ir darbo pokyčių; įmonių vadovų, tyrėjų ir komandų kaitos, pavaldumo bei strateginių prioritetų pokyčių. |
| Robotika, gamyba ir įranga | Komponentų, patikimumo, sąnaudų ir mažos gamybos galimybių pokyčių. |
| Ekonomika, verslas ir rinkos | Paklausos, finansavimo, tiekimo, įmonių veiksmų ir rinkų, įskaitant akcijas, pokyčių. |
| Politika ir infrastruktūra | Valstybių sprendimų, tarpusavio santykių ir svarbių infrastruktūros priklausomybių. |
| Teisė ir valstybės priemonės | Įstatymų projektų ir įsigaliojimo, mokesčių, standartų, paramos bei viešųjų pirkimų. |
| Energetika, maistas ir savarankiškumas | Tiekimo, gamybos, laikymo ir vietinių alternatyvų galimybių bei pažeidžiamumo. |
| Medicina, sveikata ir ilgaamžiškumas | Tyrimų rezultatų ir nesėkmių, praktinio prieinamumo, skirtumo tarp pažado ir taikymo. |
| Žmonių elgesys ir nepatenkinti poreikiai | Pasikartojančių problemų, naudojimo įpročių ir to, už ką žmonės pasirengę mokėti. |
| Mokslas ir tolimos technologijos | Ankstyvų atradimų, kurie gali pakeisti būsimų krypčių galimybes. |
| **Karas ir kariniai veiksmai** | Konfliktų eigos, pajėgų ir logistikos pokyčių, mobilizacijos, pratybų, karinės gamybos, eskalacijos bei deeskalacijos požymių. |
| **Kibernetinės atakos ir skaitmeninis saugumas** | Įsilaužimų, duomenų vagysčių, ryšio / paslaugų ir fizinių įrenginių sutrikimų, atsigavimo bei bendrų pažeidžiamumų. |
| **Pavojaus signalai ir perspėjimai** | Konkrečių institucijų ar kitų šaltinių perspėjimų, evakuacijos nurodymų, pasikeitusio parengties lygio, transporto ar paslaugų ribojimų ir neįprastų sutrikimų. |
| **Pasirengimo pavojams požymiai** | Atsargų, tiekimo, civilinės saugos, slėptuvių, elektros / ryšio tęstinumo, institucinių pirkimų ir administracinių pasirengimo veiksmų pokyčių. |

Temos persidengia. Vienas įvykis gali turėti kelias žymas, bet jo nelaikome keliais nepriklausomais patvirtinimais. Skiriame **jau įvykusį incidentą**, **viešą perspėjimą apie galimą pavojų** ir **pasirengimo veiksmą, iš kurio mėginame suprasti lūkesčius**. Pavyzdžiui, pratybos yra pasirengimo veiksmas, o ne savaime artėjančio puolimo patvirtinimas; paprastas gedimas savaime nėra nustatyta kibernetinė ataka.

Kiekvienoje temoje renkame ne tik dideles antraštes, bet ir šias naujienų rūšis:

- Pareiškimus ir ketinimus.
- Veiksmus bei įsipareigojimus: biudžetus, sutartis, pirkimus, darbuotojų samdymą, infrastruktūros kūrimą.
- Tikrus rezultatus: kas pradėta naudoti, parduodama, neveikia ar uždaroma.
- Mažus neįprastus požymius ir lėtus kaupiamuosius pokyčius.
- Prieštaravimus, atšaukimus ir laukiamų požymių nebuvimą.

Svarbių asmenų pareiškimus siejame su tema ir vėlesniais veiksmais, nepakeliame jų reikšmės vien dėl žinomumo. Pareiškimas, teisės akto projektas, priimta norma ir realus įgyvendinimas žymimi skirtingai. Vertiname tiek rizikas, tiek galimybes ir požymius, kurie prieštarauja patraukliai istorijai.

Pradžioje daugiau dėmesio skiriame dirbtiniam intelektui / automatizavimui, ekonominėms galimybėms ir mūsų atsparumui sutrikimams; karo, kibernetiniai ir pasirengimo signalai įtraukti į šį atsparumo vertinimą, ne palikti vien atsitiktinei paieškai. Konkrečių temų dažnio ir biudžeto dar nenustatėme. Kitoms sritims paliekame mažesnę netikėtos paieškos dalį.

Visų temų vienu metu išsamiai neaprėpsime. Pirmiausia kaupiame trumpus stebėjimus, parenkame kelis svarbesnius klausimus ir giliname tai, kas galėtų pakeisti mūsų sprendimus. Apžvalgos apimtis ir stebėjimo spragos turi būti aiškios. Automatinė naujienų stebėjimo sistema, duomenų bazė ar nuolatiniai agentų darbai šiuo aprašu nepaleidžiami.

#### Ankstesnio tyrimo pamoka

Pirmas naujienų tyrimas per daug orientavosi į atskirų faktų patikrą ir savininko frazės „per 40 metų“ vertinimą. Ta frazė buvo užduoties kontekstas, ne svarbiausia tyrimo tezė. Ateityje analitikas turi savarankiškai tirti reiškinį: ne patvirtinti ar paneigti savininko nuotaiką, o atrasti reikšmingus ryšius, aiškiai išlaikant jų neapibrėžtumą. Pavienių faktų patikra yra šio darbo dalis, bet neatstoja bendro vaizdo ir galimų paaiškinimų.


## 4. Krizių ir grėsmių signalų vertinimas

Savininkas kaip poreikio pavyzdį paminėjo kelių valstybių pavojaus pratybas ir neįprastą, jo vertinimu, branduolinę eskalaciją. Konkrečios valstybės, įvykiai ir šaltiniai šiame pokalbyje nepateikti; čia jie **nepatikrinti**. Tai nėra šio dokumento išvada apie dabartinę krizę.

Būsimo analitiko darbo eiga tokiam signalui:

1. **Patikrinti patį įvykį.** Kas vyko, kur, kada, kas pranešė? Atskirti įvykio datą nuo publikacijos datos. Pirminį pranešimą, kai įmanoma, tikrinti su nepriklausomu šaltiniu.
2. **Patikrinti tariamą išskirtinumą.** Ar tikrai tokio įvykio nebuvo daug metų? Ar tai planinės pratybos, anksčiau paskelbtas veiksmas, pasikartojanti retorika, ar pasikeitęs elgesys? Keli straipsniai, cituojantys tą patį pranešimą, nėra keli nepriklausomi patvirtinimai.
3. **Apsvarstyti alternatyvius paaiškinimus.** Sutapimas, bendras grafikas, viešoji komunikacija, pasirengimo politika, tikras rizikos pokytis ar kitas paaiškinimas. Vien laiko artumas neįrodo bendros priežasties.
4. **Aprašyti scenarijus ir nežinomybę.** Vertinti raidą ir pasekmes atskirai. Labai sunki pasekmė savaime nereiškia didelės jos tikimybės. Jei tikimybės pagrįstai įvertinti negalime, taip ir rašome; neįrašome išgalvoto procento.
5. **Susieti su mūsų sprendimais.** Kas keistųsi asmeniniam pasirengimui, energijos ir maisto priklausomybėms, projektams, tiekimui ar turimiems ištekliams? Ar verta nedidelė grįžtama priemonė, papildomas tyrimas, ar pakanka stebėti?
6. **Pateikti nepriklausomai peržiūrai.** Prieš svarbų išteklių perskirstymą tikriname, ar nepradėjome kurti išvados pagal baimę arba iš anksto norimą pasakojimą. Galutinį veiksmą patvirtina savininkas.
7. **Išsaugoti ir vėliau įvertinti prognozę.** Užrašyti vertinimo datą, laikotarpį, prielaidas ir kriterijus, pagal kuriuos spręsime, kas pasitvirtino. Naujas vertinimas turi naują datą; ankstesnės prognozės neperrašome taip, tarsi teisingą atsakymą žinojome iš pradžių.

Stebėjimas nėra garantuotas krizės numatymas. Jei vėliau bus įjungti pranešimai, sutarsime jų sąlygas: reikšmingas naujas patvirtinimas ar sprendimui svarbus pokytis, o ne kiekviena panaši antraštė. Vertinimo peržiūros data ir konkretūs pokyčiai apsaugo tiek nuo nuolatinio aliarmo, tiek nuo pasenusios išvados ignoravimo.


## 5. Darbo tęstinumas

Kiekvienas įrašas turi žinomą autorių, datą ir būseną. Stebėjimo atnaujinimas nekeičia ankstesnės išvados istorijos: žymime papildymus, paneigimus ir naujas žemėlapio versijas. Vienos temos keli pasakojimai gali remtis tuo pačiu šaltiniu, todėl šaltinių ryšiai svarbūs tiek pat, kiek jų skaičius.

Kol kas tai dokumentų struktūra. Nerengiame tariamų automatinių ataskaitų, jei paieška nevyko, ir neskelbiame žemėlapio parengtu, kol nėra jo turinio. Platesnės sistemos mokymosi ir diskusijų taisyklės lieka centriniame projekte.


## 6. Ribotos paieškos užduotis ir sąžininga ataskaita

Prieš paiešką trumpai nurodome klausimą ir jo reikšmę mūsų sprendimui, temas / geografiją / kalbas, laikotarpį su ribos data (kai svarbu – valanda ir laiko zona), vykdytoją ir laiko arba veiksmų biudžetą. Pabaigoje pasakome, kas realiai aprėpta ir kas liko už ribų; biudžetas yra riba, ne pareiga jį išnaudoti.

Paliekame trumpą tikrai vykdytų užklausų ir atvertų adresų pėdsaką, įskaitant svarbias nesėkmes ir atrankos priežastis. Atskirti „adresas pasiektas“ nuo „teiginys perskaitytas turinyje“. Perspausdinimus priskiriame jų pirminiam šaltiniui, o papildomą patikrą datuojame ir nurodome, kas ją atliko; originalių užrašų tyliai neperrašome.

Atskiriame įvykio, publikacijos, atnaujinimo, duomenų laikotarpio ir mūsų patikros laiką, kai jie skiriasi. Nauja publikacija apie senus duomenis nėra naujas įvykis. Prieš siūlant priežastinį ryšį patikriname chronologiją ir objektų tapatumą: ar tariama priežastis galėjo veikti tuo metu, ar tai ta pati programa, jos etapas ir finansavimo laikotarpis? Būsimos programos biudžetas savaime nepaaiškina ankstesnių sutarčių; politikos tęstinumą atskiriame nuo įrodytos finansavimo grandinės.

Signalų, ryšių ir scenarijų skaičius nėra rezultatų kvota. Pateikiame tik prasmingas jungtis su mechanizmu, alternatyva ir skiriančiu požymiu; jei ryšys nesusidarė, pakanka atskirų signalų bei paaiškinimo. Galima paslauga ar poreikis dar nėra patvirtinta moki rinka.

Spragoms vartojame konkrečią būseną: **netikrinta**; **ieškota, bet nerasta** (nurodytos paieškos ribose); **įrankis neišgavo turinio**; **šaltinis patvirtina nebuvimą** (tik jo apimtyje ir laikotarpyje). Šių būsenų nesuplakame. Kai nėra bazinio palyginimo, neteigiame augimo, pagreičio ar neįprastumo kaip nustatyto fakto.

## 7. Skaitytojui skirtas naujienų paketas

Metodikos aprašas nėra naujienų žemėlapio pakaitalas. Parengtas paketas turi tris susietas dalis: konkrečių naujienų santraukas su šaltiniais ir datomis; tikrų įvykių taškus bei paaiškintas jungtis; analitiko vertinimus ir užrašytas prognozes. Skaitytojo įėjimas yra `NAUJAUSIA.md`, o datuoti paketai saugomi istorijoje.

Kiekvienas žemėlapio taškas leidžia pasiekti naujienos santrauką. Jungtis turi pasakyti, ar tai dokumentuotas veiksmo ir atsako ryšys, ar bendra priklausomybė, ar hipotezė. Prognozė nurodo numatomą reiškinį, datą ir horizontą, ją palaikančius taškus, alternatyvą, patvirtinimo bei nepasitvirtinimo kriterijus ir galutinės peržiūros ribą. Jau įvykusio veiksmo atkūrimas negali būti pateiktas kaip būsima prognozė.

Viršuje nurodyti, iki kada informacija tikrinta. Nauja publikacija apie ankstesnį laikotarpį taip ir pažymima. Metodinė savikritika saugoma atskirai arba trumpai gale, kad neužgožtų naujienų. Jei grafinė schema neatsidaro, turi likti skaitoma konkrečių taškų ir jungčių lentelė. Naujausia suvestinė nėra automatinė stebėsena.
