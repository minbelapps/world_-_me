# Seno žaidimo atkūrimas

Atnaujinta 2026-11-03. **Būsena: vykdomas asmeninis projektas.** Pradėtas su ChatGPT. Perimta pasiekiama prototipo aptarimo medžiaga, ne visas kodas ar visas pokalbių archyvas.

## Paskirtis

Atkurti savininkui svarbų seną žaidimą ir kartu įgyti projektavimo bei programavimo patirties. Asmeninis rezultatas yra pakankama pradžios priežastis. Jei sukurtas produktas ar jo dalys vėliau turės platesnį pritaikymą, jį galima vystyti toliau, neapsiribojant pirmuoju veikiančiu prototipu.

Žaidimo originalus pavadinimas, atkuriamų taisyklių visuma ir platinimo sumanymas pasiekiamose ištraukose nenustatyti. Jei ateityje bus pasirinktas viešas ar komercinis platinimas, tuomet reikės atskirai įvertinti naudojamo turinio ir teisių klausimus; dabar tai ne vykdoma užduotis.

## Kas matyti iš ankstesnių pokalbių

ChatGPT projekte „Game project“ pasiekiamos dviejų pokalbių ištraukos leidžia aprašyti techninį sumanymą:

- Dvimatė kvadratinė lenta ir vienetai: pėstininkas, tankas, aptarta galimybė kitų tipų.
- Vieneto vieta, pasukimas, dydis ir užimami lentos langeliai.
- Vietovės tipai – lyguma, upė, kalva – bei judėjimo ribojimai pagal vietovę ir kitus vienetus.
- Žaidimo taisyklių ir skaičiavimų atskyrimas nuo vaizdavimo.
- Istoriškai pasirinkta React / TypeScript ir Pixi.js kryptis, aptarti vaizdai, tekstūros ir grafinio variklio sąsaja.
- Vaizdavimo pavyzdžiuose aprašyta 10 × 10 lenta, vieneto perkėlimas paspaudimu ir užimto langelio paryškinimas.

Asistentas teigė paruošęs `PixiGraphicsEngine`, `GraphicsEngine` ir `PixiPreviewApp` pavyzdžius. Viename bandyme savininkas pateikė realią klaidą: peržiūroje nerasti `./graphics/PixiGraphicsEngine` ir `./graphics/GraphicsEngine`. Po to asistentas aprašė savarankišką pavyzdį su laikinais vienetų duomenimis ir generuotomis tekstūromis.

**Šiame perėmime programos kodas nerastas ir nepaleistas.** Todėl ankstesnio asistento „Done“ nelaikome mūsų patikrintu veikiančiu prototipu. Technologijų ir paketų pavadinimai išsaugoti kaip istoriniai pasirinkimai, ne kaip šiandien patikrintos versijos ar nauja rekomendacija. Senų bendrų bibliotekų palyginimų automatiškai neperkeliame kaip galiojančių faktų.

## Šaltiniai

- ChatGPT projektas: „Game project“; identifikatorius `g-p-67e16867c5ac8191870c01fb5a12126e`.
- [State Management Alternatives](https://chatgpt.com/c/67dd3715-42c4-8007-a44e-a05c35b9e378) → [pasiekiamos ištraukos kopija](saltiniai/state-management-istrauka.md).
- [Pixi.js 2D Example and libraries](https://chatgpt.com/c/67df03ae-f9c4-8007-9074-6845bcce996d) → [pasiekiamos ištraukos kopija](saltiniai/pixi-istrauka.md).

Perskaityta po penkis pasiekiamus apsikeitimus kiekviename pokalbyje. Tai nėra pilnas visos ankstesnės istorijos, projektui prisegtų failų ar Canvas kodo archyvas.

## Ką atkurti prieš tęsiant

1. Originalaus žaidimo pavadinimą, norimą rezultatą ir jau sutartas taisykles.
2. Dabartinį vietinį kodą ar Canvas pavyzdžius, priklausomybes bei paleidimo komandą.
3. Tikrą veikiančią prototipo būseną: ką galima parodyti ir kokios klaidos likusios.
4. Vieną savininko pasirinktą artimiausią žingsnį. Darbo iš naujo nepradėti vien todėl, kad matoma tik dalis ankstesnio konteksto.

Atskira GitHub repozitorija numatoma vėliau, ją sukurs savininkas. Prioritetas ir tempas centriniame projekte dar nenustatyti.
