# Datuotų įvykių žemėlapis

Šeši konkretūs įvykiai / duomenų taškai (N), atskiri analitiko vertinimai (V) ir datuotos prognozės (P). Punktyrinė rodyklė reiškia „remia vertinimą“ arba „pagrindžia prognozę“, o ne „sukėlė“. Vienintelė ištisinė įvykių jungtis N4 → N6 reiškia viešai pripažintą atsaką pagal Zelenskio pareiškimą. Ji nesuteikia nepriklausomo techninio priskyrimo. Estijos incidentas neturi jungties į Ukrainos ar Rusijos ataką.

```mermaid
flowchart TB
 N1["N1 · JAV · 2026-10-28: proklamacija 11077; paskelbta 11-02"]
 N2["N2 · Š. Amerika · Q3 2026: 10 989 robotų užsakymai; antrinė publikacija 11-02"]
 N3["N3 · Estija · 2026-11-02: Selver valdiklio nuostatos pakeitimas"]
 N4["N4 · Ukraina · 2026-11-01–02: melagingi Air Alert perspėjimai"]
 N5["N5 · Ukraina · 2026-11-02–03: energetikos smūgiai ir atjungimai"]
 N6["N6 · Rusija · 2026-11-02: atsakomasis įsilaužimas; patvirtinimas paskelbtas 11-03"]
 V1{{"V1 · 2026-11-03: stipri Q3 paklausa ir prekybos neapibrėžtumas"}}
 V2{{"V2 · 2026-11-03: prieigos ir izoliavimo svarba; Estijos ryšys nenustatytas"}}
 V3{{"V3 · 2026-11-03: trumpalaikio elektros tęstinumo rizika"}}
 P1(["P1 · iki 2027-04-30: viešas JAV derybų rezultatas arba priemonė"])
 P2(["P2 · Q4 iki 2026-12-31: robotų užsakymų metinis augimas"])
 P3(["P3 · 2026-11-04–07: su šia žala susieti elektros ribojimai"])
 N4 -->|"atsakas pagal 11-03 paskelbtą pareiškimą"| N6
 N1 -. "remia" .-> V1
 N2 -. "remia" .-> V1
 N3 -. "remia" .-> V2
 N4 -. "remia" .-> V2
 N6 -. "remia" .-> V2
 N5 -. "remia" .-> V3
 N1 -. "pagrindžia" .-> P1
 N2 -. "pagrindžia" .-> P1
 V1 -. "pagrindžia" .-> P1
 N2 -. "pagrindžia" .-> P2
 V1 -. "pagrindžia" .-> P2
 N5 -. "pagrindžia" .-> P3
 V3 -. "pagrindžia" .-> P3
 classDef event fill:#e8f1ff,stroke:#345;
 classDef assessment fill:#fff2ce,stroke:#765;
 classDef forecast fill:#e5f5e8,stroke:#375;
 class N1,N2,N3,N4,N5,N6 event;
 class V1,V2,V3 assessment;
 class P1,P2,P3 forecast;
```

## Taškai: alternatyva be Mermaid

| ID | Data / horizontas | Konkretus taškas |
|---|---|---|
| <a id="n1"></a>N1 | 2026-10-28 | [JAV pradėjo robotikos importo derybas, bet nenustatė naujo muito](../suvestines/2026-11-03-naujienos.md#n1) |
| <a id="n2"></a>N2 | 2026-07-01/2026-09-30 | [Šiaurės Amerikos Q3 robotų užsakymai augo 24,8 procento](../suvestines/2026-11-03-naujienos.md#n2) |
| <a id="n3"></a>N3 | 2026-11-02 | [Estijoje pakeista šaldiklio nuostata, bet produktai nenukentėjo](../suvestines/2026-11-03-naujienos.md#n3) |
| <a id="n4"></a>N4 | 2026-11-01/2026-11-02 | [Ukrainos „Air Alert“ siuntė melagingus pavojaus pranešimus](../suvestines/2026-11-03-naujienos.md#n4) |
| <a id="n5"></a>N5 | 2026-11-02/2026-11-03 | [Smūgiai Ukrainos energetikai sukėlė avarinius atjungimus](../suvestines/2026-11-03-naujienos.md#n5) |
| <a id="n6"></a>N6 | 2026-11-02 | [Zelenskis patvirtino atsakomąjį įsilaužimą į Rusijos perspėjimų sistemą](../suvestines/2026-11-03-naujienos.md#n6) |
| <a id="v1"></a>V1 | 2026-11-03 | [Robotikos paklausa stipri, prekybos sąlygos neapibrėžtos](../prognozes/2026-11-03-vertinimai-ir-prognozes.md#v1) |
| <a id="v2"></a>V2 | 2026-11-03 | [Greitas izoliavimas riboja žalą, bet prieigos rizika išlieka](../prognozes/2026-11-03-vertinimai-ir-prognozes.md#v2) |
| <a id="v3"></a>V3 | 2026-11-03 | [Elektros tęstinumas priklauso nuo pažeidimų ir tinklo apsaugos](../prognozes/2026-11-03-vertinimai-ir-prognozes.md#v3) |
| <a id="p1"></a>P1 | 2026-11-04–2027-04-30, iki 23:59 Europe/Vilnius | [Pasirodys viešas robotikos importo derybų rezultatas arba priemonė](../prognozes/2026-11-03-vertinimai-ir-prognozes.md#p1) |
| <a id="p2"></a>P2 | 2026-10-01–2026-12-31; vertinimas 2027-03-31 | [Q4 robotų užsakymų skaičius viršys ankstesnių metų Q4](../prognozes/2026-11-03-vertinimai-ir-prognozes.md#p2) |
| <a id="p3"></a>P3 | 2026-11-04 00:00–2026-11-07 23:59 Europe/Kyiv | [Po lapkričio 3 d. išliks su šia žala susietų elektros ribojimų](../prognozes/2026-11-03-vertinimai-ir-prognozes.md#p3) |

## Jungtys

| Iš | Į | Reikšmė |
|---|---|---|
| [N1](#n1) | [V1](#v1) | Įvykis remia vertinimą; tai savaime nėra priežastingumas. |
| [N2](#n2) | [V1](#v1) | Įvykis remia vertinimą; tai savaime nėra priežastingumas. |
| [N3](#n3) | [V2](#v2) | Įvykis remia vertinimą; tai savaime nėra priežastingumas. |
| [N4](#n4) | [V2](#v2) | Įvykis remia vertinimą; tai savaime nėra priežastingumas. |
| [N6](#n6) | [V2](#v2) | Įvykis remia vertinimą; tai savaime nėra priežastingumas. |
| [N5](#n5) | [V3](#v3) | Įvykis remia vertinimą; tai savaime nėra priežastingumas. |
| [N1](#n1) | [P1](#p1) | Prognozės faktinis arba analitinis pagrindas. |
| [N2](#n2) | [P1](#p1) | Prognozės faktinis arba analitinis pagrindas. |
| [V1](#v1) | [P1](#p1) | Prognozės faktinis arba analitinis pagrindas. |
| [N2](#n2) | [P2](#p2) | Prognozės faktinis arba analitinis pagrindas. |
| [V1](#v1) | [P2](#p2) | Prognozės faktinis arba analitinis pagrindas. |
| [N5](#n5) | [P3](#p3) | Prognozės faktinis arba analitinis pagrindas. |
| [V3](#v3) | [P3](#p3) | Prognozės faktinis arba analitinis pagrindas. |
| [N4](#n4) | [N6](#n6) | Atsakas pagal Zelenskio viešą patvirtinimą, paskelbtą 2026-11-03; ne nepriklausomas pirminės atakos techninis priskyrimas. |
