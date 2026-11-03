# Padėkos mokėjimų būsena – 2026-11-01

## Tikslas

Programėlėje numatomas subtilus „Pavaišinti“ mygtukas ir betoninio stiliaus langas su QR. Telefonu atsidarytų kūrėjo mokėjimo puslapis. Tai padėka „minbelapps“ kūrėjui, ne LRT. Savininkui svarbu neviešinti savo vardo ir pavardės mokėtojams.

## Kas įvyko

- Aptartas tiesioginis bankinis SEPA QR. Jis užkoduotų gavėjo vardą, pavardę ir IBAN; tai netinka norimam privatumo lygiui. Konkretaus banko EPC QR palaikymas nepatikrintas.
- Savininkas turi SEB sąskaitą ir pats atsiskaito per Google Pay. Tai savaime nesuteikia galimybės priimti kitų žmonių Google Pay mokėjimų.
- Aptartas mokėjimų surinkimas per tarpininką: TV rodo QR į mokėjimo puslapį, Google Pay (jei prieinamas) veikia telefone, o tarpininkas išmoka į SEB. Šiam variantui TV programėlėje Google Pay SDK nereikia.
- Codex pasiūlė Buy Me a Coffee ir savininkas pradėjo registraciją. Rekomendacija pateikta per anksti, nepatikrinus visų Lietuvos registracijos reikalavimų; savininkui tai paaiškinta.
- Registracijoje paprašyta profilio paveikslėlio, aprašymo ir svetainės / socialinio profilio nuorodos. Pasiūlytas GitHub profilis, ne privataus projekto nuoroda. Galutiniai pateikti duomenys šiame pokalbyje nepatvirtinti.
- Išmokų nustatymas nukreipė į Stripe Connect. Pasirinkta šalis Lithuania. Ekrane pateikti veiklos tipai: „Individuali įmonė / Individuali veikla pagal pažymą“, „Bendrovė“, „Ne pelno organizacija“.
- Savininkas patvirtino, kad individualios veiklos dar neturi. Nuotraukoje vėliau parodyta pasirinkta „Ne pelno organizacija“ ir struktūra „Other/I'm not sure“. Paaiškinta, kad hobis ar nemokama programėlė nesuteikia ne pelno organizacijos statuso; šis pasirinkimas netinka vien todėl, kad nesiekiama pelno.
- Rekomenduota su neatitinkančia forma registracijos netęsti ir pirmiausia pasitikslinti su Buy Me a Coffee palaikymu. Šiuo metu nepatvirtinta, ar jų paslauga priima būtent tokioje situacijoje esantį Lietuvos kūrėją. Nežinoma, ar savininkas registracijoje nuėjo toliau.

## Laiškas palaikymui

Adresatas: **support@buymeacoffee.com** (nurodytas pačiame registracijos lange).

Subject: **Receiving tips in Lithuania without a registered business**

```text
Hello,

I’m based in Lithuania and create free hobby apps under the name “minbelapps”. I’d like to receive occasional voluntary tips, but I don’t have a registered business or self-employed activity.

Your Stripe onboarding offers only sole proprietor/self-employed, company, and nonprofit options.

Can I use Buy Me a Coffee in my situation? If so, which option should I select?

Also, can my public profile and payment receipts display “minbelapps” without revealing my legal name to supporters? I understand that I must provide my real identity privately for verification.

Thank you!
```

Laiško tekstas ir tema paruošti savininkui. **Išsiuntimas nepatvirtintas; atsakymo dar neturime.** Agentas laiško nesiuntė.

## Aptarti mokesčiai

2026-11-01 tikrintuose oficialiuose puslapiuose:

- Stripe Lietuvos standartinis tarifas standartinėms EEE kortelėms: 1,5 % + 0,25 EUR; standartiniame plane nėra registracijos ar mėnesinio mokesčio. Apytiksliai iš 1 / 3 / 5 EUR liktų 0,73 / 2,70 / 4,67 EUR, prieš pajamų mokesčius ir galimas papildomas sąlygas. Tai tiesioginio Stripe tarifo iliustracija, ne Buy Me a Coffee kainos.
- Buy Me a Coffee: nėra mėnesinio mokesčio; 5 % platformai ir papildomi mokėjimo apdorojimo / išmokėjimo mokesčiai. Jų pagalbos puslapyje nurodyta 2,9 % + 0,30 USD, 0,5 % išmokėjimui ir galimi papildomi mokesčiai. Galutinio tarifo konkrečiai savininko paskyrai EUR nepatvirtinome.
- Aptarta 3–5 EUR neprivalomos padėkos idėja. Galutinės sumos savininkas nepatvirtino.

## Kas dar nepatvirtinta

1. Ar galima priimti tokias įmokas per Buy Me a Coffee be registruotos veiklos Lietuvoje ir kokia registracijos forma tam tinkama.
2. Kokie tikri gavėjo duomenys rodomi viešame puslapyje, mokėjimo lange, kvite ir kituose mokėtojo matomuose įrašuose. Privatumas nepažadėtas; platformai tapatybę reikės atskleisti.
3. Galutiniai mokesčiai, išmokėjimo į SEB sąlygos ir Google Pay prieinamumas realiame mokėjimo puslapyje.
4. Pajamų / veiklos teisinis ir mokestinis vertinimas. Platformos atsakymas savaime nepakeičia Lietuvos reikalavimų.

## Tolesnis žingsnis

Savininkas patikslino, kad individualios veiklos registravimas yra vienas iš platesnių projektų planų ir tikslų. Tai nėra atsisakytas variantas: prieš registruojant reikia pasitikslinti tinkamą veiklos rūšį ir prievoles. 2026-11-01 savininko prašymu paleistas lygiagretus tyrimo agentas; numatytas rezultatas – `questions/individual-activity-research-2026-11-01.md`. Tyrimo išvados dar nepatikrintos; pats registravimas neatliekamas.

Gauti palaikymo atsakymą, jį išsaugoti šiame aplanke ir tik tada spręsti dėl platformos. Neregistruoti veiklos vien remiantis ankstesniu agento pasiūlymu ir nežymėti neatitinkančios teisinės formos. Galima tęsti dizaino aptarimą atskirai nuo mokėjimų aktyvavimo.

**Veikiančios mokėjimo nuorodos ir tikro QR dar nėra. Mokėjimas nebandytas. Šiuo įrašu programėlės kodas nekeičiamas, commit / push neatliekami.**

## Nuorodos

- Dizaino ir veikimo pasiūlymas: [codex-support-proposal.md](codex-support-proposal.md).
- Pradinė diskusija: [chart.txt](chart.txt).
- Gemini pradinė informacija (vertinti kaip pasiūlymus, ne patikrintas garantijas): [geminiINfo.txt](geminiINfo.txt).
- Stripe kainoraštis: https://stripe.com/en-lt/pricing
- Buy Me a Coffee mokesčiai: https://help.buymeacoffee.com/en/articles/8105744-how-to-calculate-charges-on-your-payment
- Google Pay veikimas: https://developers.google.com/pay/api/web/overview
- SEB gavėjo duomenys: https://www.seb.lt/privatiems/kasdiene-bankininkyste/pervedimai/pinigu-pervedimas-banko-viduje
