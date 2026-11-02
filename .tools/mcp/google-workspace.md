# Google Workspace MCP diegimo būsena

2026-11-02. Paruošė Codex.

## Kas įdiegta

Izoliuota aplinka: C:/Users/minda/.local/share/world-and-me-mcp/
- bootstrap/bin/uv.exe: uv 0.13.6
- venv/Scripts/python.exe: Python 3.13.18
- venv/Scripts/workspace-mcp.exe: workspace-mcp 2.3.0
- serverio --help patikrinimas sėkmingas.

Tai nepriklausomas atviro kodo projektas, ne oficialus Google serveris:
https://github.com/taylorwilsdon/google_workspace_mcp
https://workspacemcp.com/quick-start

## Kas NEPADARYTA

Google OAuth klientas nesukurtas ir neduotas. Serveris su Google paskyra neautentifikuotas. Codex / Claude MCP registravimo komanda buvo visa atmesta automatinės saugumo peržiūros, tad šiuo bandymu klientų nustatymai nepakeisti ir launcher nesukurtas. Jokio nuolat veikiančio proceso nepaleista. Google duomenys per šį MCP dar neskaityti ir nerašyti.

Peržiūros priežastis: nuolatinė abiejų klientų konfigūracija su plačiais rašymo įrankiais ir OAUTHLIB_INSECURE_TRANSPORT vietiniam HTTP nebuvo pakankamai konkrečiai patvirtinta. Negalima apeiti atmetimo kitu įrankiu ar netiesioginiu paleidimu.

OpenAI Google Drive papildinys atskiras ir jau patikrintas su minbelapps@gmail.com. Jo prisijungimo tokenų šiam serveriui nekopijuoti ir neieškoti.

## Siūloma pirmoji, mažesnių teisių konfigūracija

Failai šiame aplanke yra tik pavyzdžiai, ne aktyvi konfigūracija.

Pirmas prisijungimas: stdio, tik drive/docs/sheets/slides, --read-only, --tool-tier core, skirta minbelapps@gmail.com. Be Gmail, Calendar, Contacts ar interneto viešinimo. Nenaudoti OAUTHLIB_INSECURE_TRANSPORT, kol nepatvirtintas konkretus callback poreikis ir jo apimtis. Prisijungimo atveju tikrinti, ar Desktop OAuth callback priimamas be šio nustatymo; nežadėti, kad autentifikacija jau veikia.

Šis read-only profilis leidžia skaityti nurodytų Google paslaugų paskyros duomenis, ne tik vieną projekto aplanką. MCP komandų apribojimai nėra Drive aplanko teisių izoliacija. Naudoti atskirą projektų Google paskyrą. Vėlesnis kūrimo / redagavimo profilis reikalaus atskiro aiškaus sutikimo: drive, documents, spreadsheets, presentations rašymo scopes gali apimti daugiau nei vieną failą. Vien įrankių slėpimas nesusiaurina Google suteiktų OAuth scopes.

## Reikalingas Google paskyros savininko žingsnis

1. Su minbelapps@gmail.com atidaryti https://console.cloud.google.com/ ir sukurti atskirą Cloud projektą, pvz. world-and-me-mcp.
2. Įjungti tik Google Drive API, Google Docs API, Google Sheets API ir Google Slides API. API įjungimas ar mokamo plano / billing prijungimas šio diegimo metu neatliktas; mokamų paslaugų automatiškai neaktyvuoti.
3. Google Auth Platform sukonfigūruoti Branding ir Audience. Asmeninei Gmail paskyrai rinktis External; testavimo režime kaip test user pridėti savo projektų paskyrą.
4. Sukurti OAuth client: Desktop app (lokaliam stdio). Atsisiųsti kliento JSON.
5. Saugoti už Git ribų: C:/Users/minda/.local/share/world-and-me-mcp/config/client-secret.json. To failo ir tokenų nekelti į chat, GitHub ar Drive. Neužrašyti jo turinio šioje instrukcijoje.
6. Savininkui patvirtinus tikslų prieigos profilį, aktyviai užregistruoti serverį Codex ir Claude, perkrauti sesijas, atlikti Google prisijungimą naršyklėje.
7. Patikrinti tools/list ir leistiną read-only veiksmą, įsitikinti prisijungusios paskyros tapatybe. Tik tada žymėti serverį veikiančiu. Vėliau atskirai patvirtinti kūrimo / redagavimo prieigą.

Scopes, testavimo režimo prisijungimo galiojimas ir OAuth callback turi būti tikrinami pagal pasirinktos versijos realų elgesį. Ši instrukcija nėra pažadas, kad Google autentifikacija įvyks be papildomų veiksmų.

## Pakartojamumas ir saugojimas

Runtime ir prisijungimo duomenys nėra projekto Git dalis. Pavyzdinė konfigūracija ir instrukcija gali būti versijuojamos tik savininkui patvirtinus commit / push. Programėlės LRT Opus kodas šiuo diegimu nekeistas.

## Projekto registras

Aprašas perkeltas iš integrations/google-workspace/SETUP.md į .tools/mcp/google-workspace.md. Neaktyvūs klientų pavyzdžiai: claude.example.json ir codex.example.toml. Bendras registras: ../README.md. Būsena nepakeista: runtime įdiegtas, Google autentifikacija ir aktyvi registracija klientuose neatliktos.
