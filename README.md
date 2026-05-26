# Daisy Kunstbar

## Projektbeskrivelse

Daisy Kunstbar er et eksamensprojekt udviklet med fokus på at skabe en moderne og brugervenlig digital løsning til kunstbaren Daisy Kunstbar. Formålet med hjemmesiden var at samle virksomhedens visuelle identitet, information og udvalgte funktioner i én samlet platform.

Løsningen gør det muligt for brugeren at få indblik i kunstbaren, se kommende events, udforske produkter og finde relevant kontaktinformation. Projektet er udviklet med fokus på struktur, performance, responsivt webdesign og en overskuelig brugeroplevelse.

---

## Funktioner

Projektet indeholder følgende funktioner:

### Forside

Forsiden fungerer som introduktion til Daisy Kunstbar og præsenterer virksomhedens identitet, stemning og centrale informationer.

### Kalender

Kalendersiden viser kommende events hentet dynamisk fra Supabase. Events bliver sorteret efter dato og tid og grupperet efter måned for at skabe bedre overblik.

### Shop

Shop-siden viser produkter hentet dynamisk fra Supabase. Brugeren kan filtrere produkter efter kategori og åbne en popup med mere information om det valgte produkt.

### Om-side

Om-siden præsenterer Daisy Kunstbars kerneværdier, kontaktinformation og åbningstider.

### Navigation

Projektet indeholder en fullscreen navigation via burger-menu, som gør det nemt at navigere mellem siderne.

### Responsivt design

Hele løsningen er udviklet responsivt og tilpasser sig mobil, tablet og desktop.

---

## Teknologier

Projektet er udviklet med følgende teknologier:

- Astro
- HTML
- CSS
- JavaScript
- Supabase
- Astro Assets
- GitHub

---

## Projektstruktur

Projektet er opbygget med en komponentbaseret struktur for at skabe et mere overskueligt og genanvendeligt kodegrundlag.

```bash
src/
 ┣ assets/
 ┃ ┣ forside/
 ┃ ┣ kalender/
 ┃ ┣ om/
 ┃ ┗ shop/
 ┣ components/
 ┃ ┣ calenderCard.astro
 ┃ ┣ footer.astro
 ┃ ┣ header.astro
 ┃ ┗ shopCard.astro
 ┣ layouts/
 ┃ ┗ Layout.astro
 ┣ pages/
 ┃ ┣ index.astro
 ┃ ┣ kalender.astro
 ┃ ┣ shop.astro
 ┃ ┗ om.astro
 ┗ styles/
   ┣ global.css
   ┣ header.css
   ┗ footer.css

   ## Dynamisk indhold med Supabase

Supabase blev anvendt som database-løsning til håndtering af dynamisk indhold. til håndtering af dynamisk indhold på hjemmesiden. Dette gjorde det muligt at opdatere indhold uden direkte ændringer i koden og skabte en mere fleksibel og skalerbar løsning.

På kalendersiden blev eventdata hentet dynamisk fra Supabase via fetch. Data blev herefter sorteret efter dato og tidspunkt samt grupperet efter måned for at skabe et mere overskueligt layout for brugeren.

På shop-siden blev produktdata hentet fra Supabase og vist dynamisk i brugerfladen. Her blev databasen anvendt til håndtering af blandt andet produktnavn, kategori, pris, størrelse, beskrivelse og billeder.

Brugen af Supabase understøttede projektets fokus på moderne frontend udvikling og mere struktureret datahåndtering mellem frontend og backend.


## Frontend struktur og komponenter

Projektet blev udviklet med fokus på en struktureret og genanvendelig kodebase. Løsningen er opbygget med Astro og følger en komponentbaseret struktur, som gjorde udviklingsprocessen mere overskuelig og reducerede gentagelser i koden.

Et fælles layout blev anvendt til at samle sidens overordnede struktur, herunder header, main content og footer. Dette gjorde det lettere at vedligeholde design og struktur på tværs af hjemmesidens sider.

Projektet benytter blandt andet følgende komponenter:

- `header.astro`
- `footer.astro`
- `calenderCard.astro`
- `shopCard.astro`
- `Layout.astro`

Denne struktur bidrog til en mere modulær opbygning, hvor komponenter kunne genbruges flere steder i projektet og skabe en mere stabil kodeopbygning.


## GitHub workflow

GitHub blev anvendt som versionsstyringsværktøj gennem hele udviklingsprocessen for at skabe struktur og understøtte et stabilt samarbejde omkring kodningen af hjemmesiden.

Projektet blev samlet i et fælles repository, hvor gruppemedlemmer løbende arbejdede med egne ændringer lokalt i Visual Studio Code. Ændringer blev gemt gennem commits med beskrivende kommentarer og derefter delt via push og pull mellem lokale miljøer og repository.

Under udviklingen blev branches anvendt til nye funktioner og justeringer, inden ændringer blev samlet og merged til den fælles main branch.

Til håndtering af ændringer blev både GitHub Desktop og terminal anvendt. Workflowet gjorde det muligt løbende at følge projektets udvikling, gendanne tidligere versioner ved fejl og skabe en mere struktureret arbejdsproces.
```
