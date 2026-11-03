# Pavaišinti kūrėją – TV dizaino ir veikimo pasiūlymas

Autorius: Codex. Data: 2026-11-01. Būsena: diskusijos pasiūlymas, ne patvirtintas įgyvendinimas.

## Rekomendacija

Televizoriuje rodyti vieną didelį QR kodą į savininko pasirinktą mokėjimo puslapį. Kavos / alaus pasirinkimą ir sumą palikti telefone. TV programėlei nereikia Stripe SDK, mokėjimų serverio ar kortelės duomenų. Radijas ir toliau groja.

Siūlau pradėti nuo vienos nuolatinės, pakartotinai naudojamos mokėjimo nuorodos, o ne kelių QR kodų ar vienkartinio mokėjimo prašymo. Konkreti platforma pasirenkama tik patikrinus savininko paskyrą, gavimo sąlygas ir realų atsiskaitymą telefone. Šiuo pasiūlymu platforma dar nepasirenkama.

## Mygtukas pagrindiniame ekrane

Prie Dainos / Vaizdas / Info pridėti puodelio kontūro piktogramą su trumpu užrašu „Pavaišinti“. Vizualiai toks pats dydis ir spalvos kaip kitų antrinių veiksmų: tamsus pusiau permatomas pagrindas, šviesi piktograma, šiltas auksinis kontūras gavus fokusą. Nuolatinio švytėjimo, judėjimo ar raginimo paremti nereikia.

Pasiūlymas pulteliui: puodelis paskutinis apatinėje eilėje, po Info. Esamą septynių valdiklių maketą reikėtų perskaičiuoti į aštuonis, ne tiesiog suspausti ir pridėti ikoną. Išlaikome TV saugius kraštus ir pakankamus atstumus. Pradinis fokusas lieka ant Play/Pause.

## Atvertas langas

Centruota plati kortelė ant pritemdyto patefono vaizdo. Kortelėje matomas šviesus betonas, tokios pačios medžiagos kaip pagrindas, tačiau mažiau ryškios tekstūros, kad netrukdytų tekstui. Tamsiai pilkas tekstas, šiltai auksinės smulkios detalės. Už lango plokštelė gali suktis toliau; etikečių persiliejimus šiame vaizde galima laikinai sustabdyti, kad QR skenavimo niekas neblaškytų.

1920 × 1080 ekrano pradinis maketavimo orientyras: kortelė apie 1200 × 660 ekrano pikselių; kairėje tekstas, dešinėje QR. Tai kompozicijos proporcijos, ne Android dp reikšmės. Galutinį dydį nustatome pagal TV peržiūrą.

Siūlomas tekstas:

> **Patinka šis patefonas?**
>
> Gali pavaišinti kūrėją kava ar alumi.
>
> Nuskenuok kodą telefonu ir pasirink sumą.
>
> Ačiū, kad padedi kurti toliau.

Po tekstu mažas „minbelapps“ parašas. Atskirai aiški eilutė: „Palaikymas skirtas programėlės kūrėjui, ne LRT.“ Tai svarbu dėl etiketėje ir ekrane esančio LRT pavadinimo. Nevadinčiau to mokėjimu už LRT transliaciją ar oficialia LRT parama.

Kava / alus čia yra draugiškas gestas, ne parduodamos prekės. Nedėčiau išgalvotų kainų ir papildomų pasirinkimų TV ekrane, kol savininkas jų nepatvirtino. Jeigu norės konkrečių sumų, siūlau jas pateikti telefono mokėjimo puslapyje.

## QR pateikimas

QR turi būti juodas ant vientiso balto kvadrato, be betono tekstūros, gradiento, logotipo centre ar animacijos. Aplink kodą palikti bent keturių modulių baltą ramybės zoną. Pradėti nuo maždaug 360–420 ekrano pikselių kvadrato 1080p kompozicijoje ir patikrinti iš realaus sėdėjimo atstumo. Tai bandymo pradžia, ne pažadas, kad kiekvienas telefonas nuskenuos iš sofos.

Po kodu parodyti tikrą žmogui perskaitomą trumpą adresą ir mokėjimo paslaugos pavadinimą. Jie turi sutapti su QR paskirtimi. Kol nėra savininko patvirtintos nuorodos, makete palikti aiškų vietos rezervą, ne sugalvotą veikiantį QR ar gavėją.

Pirmam variantui nereikia savo tarpinio tinklalapio vien nuorodos peradresavimui: tai papildoma priežiūra. Jei savininkas jau turi savo domeną ir nori valdyti adresą ilgainiui, trumpas jo domeno adresas galėtų būti vėlesnis pasirinkimas.

## Pultelis ir lango uždarymas

- OK ant puodelio atidaro langą.
- Lange pradinis fokusas ant aiškaus „Grįžti prie muzikos“ mygtuko.
- BACK arba OK ant šio mygtuko uždaro langą ir grąžina fokusą puodeliui.
- Fokusas lieka lange; rodyklės neturi netyčia keisti kanalo fone.
- Langas neužsidaro pats ir neužsidaro vien nuo fokuso judėjimo: žmogui reikia laiko pasiimti telefoną ir nuskenuoti kodą.
- Transliacija nenutraukiama. Mokėjimas nevykdomas televizoriuje ir naršyklės televizoriuje nereikalaujama.

Programėlė negali iš vien QR nuskenavimo sužinoti, ar mokėjimas įvyko. Todėl nerodyti „Mokėjimas gautas“ ar automatinio patvirtinimo. Tam reikėtų atskiros serverinės integracijos, kurios šiame etape nerekomenduoju.

## Ką patikslinčiau Gemini informacijoje

Gemini teisingai siūlo QR su mokėjimo nuoroda kaip paprastą kelią. Tačiau TV atveju integruotas Google Pay / Stripe Android SDK nesuteikia aiškios naudos: mokėtojas vis tiek naudojasi telefonu.

Teiginių, kad visi minėti bankai palaiko konkretų EPC QR arba kad kiekviena Revolut / kitos platformos nuoroda leidžia visiems mokėti kortele ir Google Pay, negalima laikyti patvirtintais. Tai priklauso nuo paslaugos, šalies, paskyros, įrenginio ir konkretaus mokėjimo puslapio. Gemini nurodyti komisiniai taip pat nėra šio projekto patikrintos kainos.

Revolut oficialiai aprašo mokėjimo nuorodas, bet asmeninė Revolut.me nuoroda ir komercinis Hosted Checkout nėra tas pats produktas. Nesirenkame paskyros tipo pagal vien pavadinimą. Nuorodą turi pateikti savininkas, patikrinęs savo paskyrai taikomas sąlygas.

Jei programėlė bus platinama per Google Play, prieš leidimą reikia įvertinti mokėjimų politiką pagal galutinį srautą. Google dokumentacijoje yra išimtis savanoriškiems arbatpinigiams, kai visa įmoka tenka kūrėjui ir nesuteikiama skaitmeninio turinio ar paslaugų. Todėl šioje vizijoje nedėčiau mokamų etikečių, ženkliukų, kanalų ar kitų atrakintų funkcijų. Išimtis nėra automatinis leidimas bet kokiai mokėjimo nuorodai; galutinį variantą tikriname prieš publikavimą.

Oficialūs šaltiniai, tikrinti 2026-11-01:

- Google Play mokėjimų politikos paaiškinimas: https://support.google.com/googleplay/android-developer/answer/10281818?hl=en
- Revolut.me paaiškinimas: https://help.revolut.com/help/transfers/payment-links/revolut-me-link/
- Revolut Hosted Checkout mokėjimo nuorodos: https://developer.revolut.com/docs/guides/merchant/accept-payments/online-payments/hosted-checkout-page/payment-link

## Siūlomas kitas žingsnis

Pirma patvirtinti šią kompoziciją ir tekstą. Tada sukurti vieną statinį lango maketą ant esamo betoninio dizaino, dar be mokėjimo integracijos. Patvirtinus vaizdą, savininkas pateikia pasirinktą nuolatinę nuorodą; tik tada generuojame tikrą QR ir bandome telefonu prieš perkeldami į programėlę.

Patikrinimas: QR paskirtis ir gavėjas, nuskaitymas nuo tikro TV keliomis apšvietimo sąlygomis, pultelio fokusas ir BACK grąžinimas, nenutrūkstantis garsas, prieinami pasirinktos paslaugos mokėjimo būdai. Mokėjimo bandymas – tik savininkui atskirai sutikus.

Šiame etape pakeisti tik diskusijos failai. Programėlės kodas, mokėjimo paskyros ir Git istorija nekeisti.
