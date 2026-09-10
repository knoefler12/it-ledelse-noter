---
title: "Laudon & Laudon (2022) - Kapitel 9 - Enterprise Applications"
aliases:
  - "Laudon - ERP, SCM og CRM"
authors:
  - Kenneth C. Laudon
  - Jane P. Laudon
year: 2022
book: "Management Information Systems: Managing the Digital Firm"
edition: "17th Global Edition"
chapter: 9
pages: "368-401"
course: "M2"
type: litteraturnote
tags:
  - it-ledelse
  - m2
  - enterprise-applications
  - erp
  - scm
  - crm
---

# Laudon & Laudon (2022) - Kapitel 9 - Enterprise Applications

> [!abstract] Hovedpointe
> ERP, SCM og CRM forbinder data og processer, så virksomheden kan koordinere sin drift, sin forsyningskæde og sine kunderelationer. Gevinsterne kræver fælles data, ændrede arbejdsgange og organisatorisk samarbejde. Installation af software er kun en del af opgaven.

## Kilde og afgrænsning

Laudon, K. C., & Laudon, J. P. (2022). *Management Information Systems: Managing the Digital Firm* (17th Global Edition). Pearson. Kapitel 9: *Achieving Operational Excellence and Customer Intimacy: Enterprise Applications*, s. 368-401.

**Teksttype:** Lærebogskapitel. Noten dækker hele kapitlets centrale stof, herunder de fire cases. Slutspørgsmål og øvelser sammenfattes efter deres læringsformål.

> [!info] Sidetal og eksempler
> Alle sidetal henviser til bogens **trykte sider**. I den uploadede PDF er **PDF-side = trykt side + 1**. Figur 9.1 på s. 372 ligger derfor på PDF-side 373.
>
> Virksomheder og teknologier beskrives, som de optræder i 2022-bogen. Egne eksempler og kritiske overvejelser er markeret særskilt.

**Forudsætning:** [[Laudon-2022-Kapitel-2-Afsnit-2.1-2.2-M2|Kapitel 2, afsnit 2.1-2.2 - Forretningsprocesser og systemtyper]].

## 1. Overblik: Hvilket problem løser systemerne?

| Systemtype | Hovedopgave | Typisk problem | Sider |
|---|---|---|---|
| **ERP - Enterprise Resource Planning** | Integrere virksomhedens centrale interne processer og data | Salg, lager og økonomi arbejder med forskellige oplysninger | 371-374 |
| **SCM - Supply Chain Management** | Koordinere efterspørgsel, forsyning, produktion og distribution | Virksomheder bestiller og producerer ud fra mangelfuld information | 374-380 |
| **CRM - Customer Relationship Management** | Samle kundeinformation og understøtte salg, service og marketing | Kunden møder afdelinger, der ikke kender kundens øvrige kontakt med virksomheden | 381-388 |

**Operational excellence** handler om velfungerende og effektiv drift. **Customer intimacy** handler om at forstå kunderne og opbygge tætte, værdifulde relationer. De to mål forklarer kapitlets titel.

> [!important] To forskellige måder at inddele systemer på
> TPS, MIS, DSS og ESS fra kapitel 2 beskriver især støtte til transaktioner, information og beslutninger. ERP, SCM og CRM beskriver især, hvilke processer og relationer systemerne integrerer. Et ERP-system kan derfor både behandle transaktioner og levere ledelsesinformation.
>
> **Enterprise applications** er samlebetegnelsen. **Enterprise systems** bruges i dette kapitel mere specifikt om ERP.

## 2. ERP: Fælles data og integrerede processer (s. 371-374)

### Hvordan fungerer ERP?

Et ERP-system består af integrerede softwaremoduler og en fælles, central database. Modulerne understøtter forskellige funktioner, men arbejder med fælles oplysninger. Når data registreres i én proces, kan de bruges i andre processer (s. 371-372, figur 9.1).

**Bogeksemplets logik:** En salgsordre kan sætte flere sammenhængende handlinger i gang: kreditkontrol, reservation af lager, forsendelse og opdatering af økonomiske oplysninger. Hvis varen mangler, kan ordren udløse produktion og bestilling af materialer. Andre afdelinger kan følge samme ordres status.

Integrationen reducerer behovet for at indtaste og afstemme de samme oplysninger i flere separate systemer. Den giver samtidig ledelsen et mere samlet billede af virksomheden.

### Hvilke processer understøttes?

Tabel 9.1 viser blandt andet følgende (s. 373):

| Område | Eksempler |
|---|---|
| Finans og regnskab | Finansbogføring, debitorer, kreditorer, likviditet og rapportering |
| HR | Personaleoplysninger, løn, rekruttering, tidsregistrering og uddannelse |
| Produktion og logistik | Indkøb, lager, produktionsplanlægning, materialebehov, kvalitet og vedligehold |
| Salg og marketing | Ordrebehandling, priser, fakturering, kreditkontrol og salgsplanlægning |

### Best practices, configuration og customization

ERP-software bygger på foruddefinerede processer, som leverandøren betragter som **best practices**: velafprøvede måder at udføre arbejdet på. Virksomheden skal vælge funktioner og afklare, hvordan dens processer passer til softwaren (s. 372-373).

- **Configuration:** Tilpasning gennem systemets eksisterende indstillinger og konfigurationstabeller. Eksempel: hvordan omsætningen grupperes i rapporter.
- **Customization:** Mere indgribende specialtilpasning, fx omskrivning af softwarekode. Det kan gøre systemet vanskeligere at integrere, vedligeholde og opdatere.

Bogen anbefaler generelt at begrænse specialtilpasning og i stedet tilpasse processerne til systemets standardfunktioner. Det indebærer organisatoriske ændringer, ikke blot et teknisk valg.

> [!question] Kritisk læsning - egen overvejelse
> “Best practice” betyder ikke automatisk “bedst i enhver organisation”. Spørg, hvilke processer der med fordel kan standardiseres, og hvilke særlige behov der er afgørende for organisationens opgave eller konkurrenceevne.

### Forretningsværdi

ERP kan give hurtigere processer, mere ensartede data og bedre beslutningsgrundlag på tværs af virksomheden. Alcoa-eksemplet illustrerer, hvordan fælles processer og data kan reducere dobbeltarbejde og forkorte forløbet fra indkøbsanmodning til betaling (s. 373-374).

**Cycle time** er den samlede gennemløbstid fra start til afslutning. Ventetid mellem afdelinger tæller også med.

## 3. SCM: Koordinering af forsyningskæden (s. 374-380)

### Supply chain, upstream og downstream

En **supply chain** er netværket af organisationer og processer, der skaffer råvarer, omdanner dem til produkter og leverer dem til kunder. Kæden omfatter bevægelser af materialer, information og betalinger. Returvarer kan bevæge sig tilbage gennem kæden (s. 374-376).

- **Upstream:** Leverandører og deres leverandører, set fra den virksomhed, analysen tager udgangspunkt i.
- **Internal supply chain:** Virksomhedens egne processer, hvor input omdannes til output.
- **Downstream:** Distribution og levering frem mod kunderne.
- **Tier 1, 2 og 3:** Leverandørled. Tier 1 leverer direkte til fokusvirksomheden; tier 2 leverer til tier 1 osv.

Nike-eksemplet viser, at et enkelt produkt kan afhænge af mange leverandørled. Virksomheden har derfor brug for viden om mere end sine direkte leverandører (s. 375-376, figur 9.2).

### Hvorfor er information afgørende?

Forsinkede eller unøjagtige oplysninger kan føre til både udsolgte varer og for store lagre. Andre følger er uudnyttet kapacitet, dyr transport og dårlig leveringsevne (s. 376).

**Just-in-time (JIT)** søger at få komponenter frem, når produktionen skal bruge dem, og færdigvarer videre, når de er klar. Det begrænser lagerbinding, men kræver præcis information og koordination.

**Safety stock** er sikkerhedslager: en buffer mod usikkerhed. Lageret koster penge, men kan mindske risikoen for, at produktion eller levering stopper.

### Bullwhip effect - piskesmældseffekten

Små udsving i slutkundernes efterspørgsel kan blive forstærket til større udsving i bestillinger længere oppe i kæden. Hvert led reagerer på sine egne oplysninger og antagelser i stedet for det faktiske samlede behov (s. 376-377, figur 9.3).

I bogens Pampers-eksempel varierede distributørernes ordrer mere end forbrugernes efterspørgsel. Kampagner og bestillingsmønstre bidrog til at forvrænge signalet.

**Konsekvensen:** Producenter og leverandører kan opbygge for store lagre eller ændre produktionen uhensigtsmæssigt. Deling af oplysninger om faktisk efterspørgsel kan mindske problemet, men bestillings- og planlægningspraksis spiller også en rolle.

> [!example] Eget, forenklet eksempel
> Kunder køber 110 enheder mod normalt 100. Butikken bestiller 120 for at være sikker, distributøren bestiller 140, og producenten planlægger 160. Eksemplet illustrerer forstærkningen; tallene er ikke fra bogen.

### Planning og execution er forskellige opgaver

| Begreb | Hvad systemet understøtter | Eksempel | Sider |
|---|---|---|---|
| **Supply chain planning** | Planlægning af, hvad der bør produceres, opbevares og transporteres | Hvor meget skal produceres, hvor og hvornår? | 377-378 |
| **Demand planning** | Vurdering af det forventede behov for produkter | Hvor stor bliver efterspørgslen næste måned? | 377-378 |
| **Supply chain execution** | Gennemførelse og styring af det faktiske vareflow | Lagerpluk, forsendelse og transport | 378 |

En god plan er utilstrækkelig, hvis lager og transport ikke kan udføre den. Omvendt løser effektiv lagerdrift ikke en dårlig efterspørgselsprognose.

### Push versus pull

**Push** er overvejende prognosestyret: Virksomheden producerer og distribuerer ud fra forventet efterspørgsel. Bogen forbinder det med **build-to-stock** (s. 379).

**Pull** er efterspørgselsstyret: Faktiske ordrer eller køb udløser aktiviteter bagud i kæden. Bogen forbinder det med **build-to-order**, men omtaler også genopfyldning på baggrund af faktisk salg.

> [!important] Figur 9.4 skal læses som styringslogik
> I pull-modellen bevæger efterspørgselssignalet sig fra kunden tilbage mod leverandørerne. Det betyder ikke, at de fysiske varer bevæger sig væk fra kunden, eller at alle lagre forsvinder.

Internettet gør det muligt at udveksle information på tværs af globale kæder. Frem for kun at sende oplysninger sekventielt fra nabo til nabo kan flere aktører koordinere samtidigt: **concurrent supply chains** (s. 378-380, figur 9.5).

## 4. CRM: Samlet kundebillede og koordineret kontakt (s. 381-388)

### Hvad er CRM?

CRM samler og analyserer kundeoplysninger fra flere dele af virksomheden og gør dem tilgængelige for de relevante funktioner. Målet er en fælles forståelse af kunden, som kan bruges i salg, service og marketing (s. 381-382, figur 9.6).

Et **touchpoint** er et kontaktpunkt mellem kunden og virksomheden, fx en butik, telefon, e-mail, hjemmeside eller social kanal. Kunden kan bevæge sig mellem kontaktpunkter, mens virksomheden stadig skal kunne følge relationen.

### Tre centrale anvendelser

| Anvendelse | Funktioner | Pointen | Sider |
|---|---|---|---|
| **Sales force automation (SFA)** | Kundeemner, kontakter, tilbud, salgsprognoser og deling af kundeoplysninger | Sælgerne får bedre overblik og kan koordinere indsatsen | 383 |
| **Customer service** | Henvendelseshistorik, videresendelse til rette medarbejder og selvbetjening | Kunden får sammenhængende hjælp uden at gentage alt | 383 |
| **Marketing** | Målgrupper, kampagner, vurdering af kundeemner og evaluering af respons | Indsatsen kan målrettes og vurderes | 383-384 |

**Cross-selling** betyder at sælge supplerende produkter til en eksisterende kunde. Det adskiller sig fra at få kunden til at vælge en dyrere version af samme produkt.

Udvidede CRM-pakker kan også rumme **PRM - Partner Relationship Management**, som understøtter samarbejde med salgspartnere, og **ERM - Employee Relationship Management**, som understøtter fx medarbejdermål, præstation og træning. ERM er ikke det samme som ERP (s. 382).

### Operational CRM versus analytical CRM

**Operational CRM** understøtter de direkte aktiviteter i kundekontakten: salg, kundeservice og marketing. **Analytical CRM** analyserer data fra disse aktiviteter sammen med andre kilder for at finde mønstre og understøtte beslutninger (s. 385-386).

Analytisk CRM kan samle data i et **data warehouse** eller en analytisk platform og bruge **OLAP** og **data mining** til at identificere kundesegmenter, profitable kunder og risiko for kundefrafald (figur 9.10).

> [!example] Eget eksempel
> Registrering og behandling af en kundeklage er operationelt CRM. En analyse af, om gentagne klager hænger sammen med opsigelser, er analytisk CRM. Analysen kan efterfølgende ændre, hvordan kundeservice håndterer bestemte henvendelser.

### Customer lifetime value og churn

**Customer lifetime value (CLTV)** vurderer kundens økonomiske værdi gennem relationens forventede levetid. Bogen fremhæver omsætning, omkostninger til at skaffe og servicere kunden samt relationens forventede længde (s. 386).

En kunde med høj omsætning er derfor ikke nødvendigvis den mest profitable kunde. En kostbar serviceindsats kan ændre vurderingen.

**Churn rate** er et mål for kundefrafald. CRM kan hjælpe med at identificere kunder, der risikerer at forlade virksomheden, og understøtte fastholdelse (s. 386).

CRM kan skabe værdi gennem bedre service, mere relevant marketing, krydssalg og lavere omkostninger ved at skaffe og fastholde kunder. Det kræver, at indsigterne faktisk ændrer virksomhedens handlinger.

## 5. Implementering: Hvorfor er enterprise applications svære? (s. 388-392)

Udfordringerne omfatter høje omkostninger, tidskrævende ændringer, uddannelse og nye ansvarsforhold. Når processer integreres, kan en ændring i én afdeling få betydning for andre. SCM kræver desuden samarbejde mellem selvstændige virksomheder (s. 388-389).

Tre centrale problemer:

1. **Procesforståelse:** Organisationen skal kende sine faktiske arbejdsgange. Woolworths-casen viser problemer, når vigtige eksisterende processer og rapporteringsbehov ikke er tilstrækkeligt forstået og dokumenteret.
2. **Datakvalitet og fælles definitioner:** Afdelinger skal være enige om fx kunde- og produktdata. Forkerte og dublerede oplysninger skal renses gennem **data cleansing**.
3. **Afhængighed og switching costs:** Når software og organisation er tæt integreret, kan det blive dyrt at skifte system eller leverandør.

### Udviklingen beskrevet i bogen

Enterprise suites forbinder i stigende grad ERP, SCM og CRM med hinanden og med eksterne partnere. Kapitlet beskriver cloud, mobil adgang, social CRM, business intelligence og AI som udviklingsretninger i bogens samtid (s. 389-392).

**Social CRM** integrerer information og dialog fra sociale kanaler i virksomhedens kundearbejde. Det er mere end blot at have en profil på sociale medier.

**Business intelligence** kan føjes til enterprise applications, så fælles data bruges til dashboards, analyser og vurdering af alternative handlinger. Det forbinder kapitlet med MIS/DSS-stoffet i kapitel 2.

> [!question] Kritisk læsning - egen overvejelse
> Cloud kan ændre, hvem der driver infrastrukturen. Det afgør ikke i sig selv, hvem der skal definere data, ændre arbejdsgange eller få medarbejderne til at bruge løsningen. De organisatoriske spørgsmål består.

## 6. Cases: Hvad illustrerer de?

### Lenzing: Planlægning og bæredygtighed (s. 369-371)

Fiberproducenten havde komplekse globale forsyningsforhold og omfattende manuel planlægning. Mangelfuld koordinering kunne give både overproduktion og vareknaphed.

En cloudbaseret planlægningsløsning blev kombineret med ændringer i **Sales and Operations Planning (S&OP)**, som forbinder efterspørgselsprognoser med drift og økonomi. Bedre planlægning kan både understøtte leveringsevne og reducere ressourceforbrug og spild.

**Husk:** Casen forbinder teknologi, ledelse og organisering. Resultatet kan ikke alene tilskrives softwaren.

### Adidas: Sammenhængende kundeoplevelse (s. 387-388)

Adidas bruger i casen en fælles CRM-platform til at forbinde salg, service, marketing og e-handel. Kundeoplysninger skal understøtte personlige oplevelser og sammenhæng mellem kontaktpunkter.

**Husk:** “Samlet kundebillede” er et middel. Værdien opstår, når kunden møder mere relevante produkter, kommunikation og service.

### Versum: Nyt ERP efter udskillelse (s. 391-392)

Efter udskillelsen fra Air Products skulle Versum etablere systemer, der passede til den nye virksomhed. Det gamle ERP var stærkt specialtilpasset. Virksomheden valgte et nyt SAP S/4HANA-system i en privat cloud med ekstern drift.

Casen fremhæver standardisering, en stram tidsramme og datarensning. Kunde- og leverandørrelaterede registreringer skulle blandt andet samles i en fælles **Business Partner**-struktur. Implementeringen skete samlet globalt, en **big bang**, fordi overgangsaftalens tidsramme begrænsede mulighederne for en gradvis overgang.

**Husk:** Big bang var et valg under bestemte betingelser. Casen dokumenterer ikke, at denne tilgang altid er bedst.

### COVID-19: Effektivitet og robusthed i forsyningskæder (s. 398-400)

Pandemien forstyrrede både produktion, transport og efterspørgsel. Tidligere salgsmønstre blev et dårligere grundlag for prognoser, og virksomheder manglede overblik over afhængigheder længere oppe i kæden.

Casen diskuterer blandt andet større spredning af leverandører og geografiske afhængigheder, bedre overblik over underleverandører og revurdering af lagre. En lille, billig komponent kan være afgørende for en hel produktion.

> [!important] En spænding, du bør kunne forklare
> JIT og små lagre kan øge effektiviteten under stabile forhold (s. 376). Buffere og alternative leverandører kan øge **resilience**, altså evnen til at håndtere og komme sig efter forstyrrelser (s. 398-400).
>
> Det er derfor relevant at vurdere både omkostninger i normal drift og konsekvenserne af afbrydelser. Bedre digitale oplysninger hjælper, men skaber ikke alene ekstra produktionskapacitet eller transportmuligheder.

### Karriereafsnit og slutopgaver (s. 392-397)

Karriereeksemplet fremhæver procesforståelse, indsamling og dokumentation af behov, instruktioner og håndtering af problemer efter implementering. Kommunikation og samarbejde indgår sammen med systemforståelsen.

Slutspørgsmål og øvelser træner især at forbinde et konkret forretningsproblem med relevante data, processer og systemfunktioner. Brug dem til at øve argumentationen: **Hvorfor passer denne løsning til netop dette problem?**

## 7. Sprognøgle: Fagbegreber og engelsk, du skal kunne genkende

Tabellen supplerer forklaringerne ovenfor. Sidetallene peger på den relevante faglige sammenhæng; de danske oversættelser er notehjælp.

| Engelsk | Dansk betydning i sammenhængen | Sider |
|---|---|---|
| Enterprise / enterprise-wide | Virksomhed / på tværs af hele virksomheden | 371-374 |
| Suite / module | Samling af sammenhængende programmer / en funktionel del af systemet | 371-372 |
| Integrated | Integreret: dele fungerer sammen og udveksler data | 371-372 |
| Best practices | Velafprøvede standardmåder at udføre arbejdet på | 372-373 |
| Configuration / customization | Indstillinger inden for standarden / særlig tilpasning, fx kodeændringer | 372-373 |
| Procurement | Indkøb og processerne omkring anskaffelse | 373-374 |
| Accounts receivable / payable | Debitorer, dvs. tilgodehavender / kreditorer, dvs. skyldige beløb | 373 |
| Cycle time | Samlet gennemløbstid | 374 |
| Inventory / stockout | Lagerbeholdning / en efterspurgt vare er ikke på lager | 376 |
| Safety stock | Sikkerhedslager som buffer mod usikkerhed | 376 |
| Demand / forecast | Efterspørgsel / prognose om fremtidigt behov | 376-379 |
| Replenishment | Genopfyldning af lager | 377-379 |
| Lead time | Tiden fra et behov eller en ordre opstår, til leverancen er klar eller modtaget | 377-380 |
| Planning / execution | Planlægning / gennemførelse af aktiviteter | 377-378 |
| Sequential / concurrent | Efter hinanden / samtidigt | 380 |
| Touchpoint | Kontaktpunkt mellem kunde og virksomhed | 381 |
| Prospect / lead | Potentiel kunde / et konkret kundeemne, der kan bearbejdes | 383 |
| Campaign | En planlagt marketingindsats | 383-384 |
| Retention / churn | Fastholdelse / kundefrafald | 385-386 |
| Customer lifetime value | Kundens forventede økonomiske værdi gennem relationen | 386 |
| Data warehouse | Samlet datagrundlag, indrettet til analyse på tværs af kilder | 385-386 |
| OLAP | Online Analytical Processing: analyse af data på tværs af dimensioner, fx tid, produkt og kundegruppe | 386 |
| Data mining | Metoder til at finde mønstre og sammenhænge i data | 386 |
| Switching costs | Omkostninger og besvær ved at skifte løsning eller leverandør | 389 |
| Data cleansing | Rettelse og oprydning i data, fx fejl og dubletter | 389, 391 |
| SaaS | Software as a Service: software leveret som en tjeneste | 370, 390 |
| Big bang implementation | Samlet overgang til det nye system frem for en gradvis indførelse | 391-392 |
| Resilience | Robusthed og evne til at tilpasse sig og komme sig efter forstyrrelser | 398-400 |

> [!tip] Generelt akademisk engelsk
> **Contemporary** betyder *nutidig/samtidig* i forhold til tekstens egen tid, her bogens 2022-kontekst. **Enhance** betyder forbedre; **facilitate** betyder muliggøre eller lette; **leverage** bruges om at udnytte noget til et formål. Ordene er ikke selvstændige modeller. **Imbrication** er derimod et særskilt begreb fra Leonardi-teksten og er ikke en af dette kapitels modeller.

## 8. Figur- og modeloversigt til dine screenshots

Alle **10 nummererede figurer** og kapitlets tabel er med nedenfor. Forklaringerne kan beholdes under de billeder, du indsætter.

| Nr. | Bogens titel | Trykt side | PDF-side | Det vigtigste spørgsmål |
|---|---|---:|---:|---|
| 9.1 | How Enterprise Systems Work | 372 | 373 | Hvordan forbinder en fælles database afdelingerne? |
| Tabel 9.1 | Business Processes Supported by Enterprise Systems | 373 | 374 | Hvilke konkrete processer kan ERP understøtte? |
| 9.2 | Nike's Supply Chain | 375 | 376 | Hvor ligger upstream, downstream og leverandørleddene? |
| 9.3 | The Bullwhip Effect | 377 | 378 | Hvorfor vokser udsvingene op gennem kæden? |
| 9.4 | Push- versus Pull-Based Supply Chain Models | 379 | 380 | Hvad udløser aktiviteterne: prognoser eller efterspørgsel? |
| 9.5 | The Emerging Internet-Driven Supply Chain | 380 | 381 | Hvordan kan flere aktører koordinere samtidigt? |
| 9.6 | Customer Relationship Management (CRM) | 382 | 383 | Hvordan samles salg, service og marketing omkring kunden? |
| 9.7 | How CRM Systems Support Marketing | 384 | 385 | Hvad fortæller kampagnens responsfordeling? |
| 9.8 | CRM Software Capabilities | 384 | 385 | Hvilke funktioner understøtter CRM? |
| 9.9 | Customer Loyalty Management Process Map | 385 | 386 | Hvordan indgår kundeinformation i en serviceproces? |
| 9.10 | Analytical CRM | 386 | 387 | Hvordan bliver kontaktdata til analytisk indsigt? |

### Figur 9.1 - ERP-arkitektur

> [!example] Indsæt figur 9.1 her - s. 372 / PDF 373

Cylinderen i midten er den fælles database. Afdelingerne omkring den bruger og opdaterer data gennem deres funktioner. Pilene viser udveksling med databasen. **Pointen er fælles information på tværs af afdelinger**, ikke fire uafhængige databaser.

### Tabel 9.1 - Processer i ERP

> [!example] Indsæt tabel 9.1 her - s. 373 / PDF 374

Brug tabellen til at gå fra systemnavnet “ERP” til faktiske arbejdsopgaver. Vælg fx en salgsordre, og forklar, hvorfor både salg, lager og regnskab berøres.

### Figur 9.2 - Forsyningskædens led

> [!example] Indsæt figur 9.2 her - s. 375 / PDF 376

Nike er fokusvirksomhed. Til venstre ligger leverandører i flere led; til højre ligger distribution og kunder. Dobbeltpilene understreger forbindelser og informationsudveksling i begge retninger. Figuren er en forenkling af et større netværk.

### Figur 9.3 - Forstærkning af udsving

> [!example] Indsæt figur 9.3 her - s. 377 / PDF 378

Følg udsvingene fra kunderne til højre tilbage mod leverandørerne til venstre: Udsvingene bliver større upstream. De tegnede kurver illustrerer en mekanisme; de er ikke en graf med dokumenterede procenttal. **Større udsving er ikke det samme som vedvarende vækst i efterspørgslen.**

### Figur 9.4 - Push og pull

> [!example] Indsæt figur 9.4 her - s. 379 / PDF 380

Øverst driver prognoser produktion og forsyning. Nederst går signalet fra kundens behov tilbage gennem kæden. Pilretningen i pull skal læses som det udløsende ordre-/efterspørgselssignal, ikke som den fysiske leveringsretning.

### Figur 9.5 - Samtidig koordinering

> [!example] Indsæt figur 9.5 her - s. 380 / PDF 381

Figuren viser et netværk med flere forbindelser mellem producenter, leverandører, distributører, kunder og logistikaktører. De stiplede dobbeltpile viser kommunikation og informationsudveksling. **Stiplingen betyder ikke svagt samarbejde.** Pointen er, at information ikke kun behøver gå sekventielt gennem naboleddene.

### Figur 9.6 - Kunden i centrum

> [!example] Indsæt figur 9.6 her - s. 382 / PDF 383

Kunden står i centrum af salg, service og marketing. Det er en begrebsoversigt: De tre sektorers størrelse viser ikke procentandele eller en bestemt prioritering.

### Figur 9.7 - Kampagnerespons

> [!example] Indsæt figur 9.7 her - s. 384 / PDF 385

Cirkeldiagrammet fordeler kampagnerespons mellem kontaktkanaler. **Andel af samlet respons er ikke det samme som konverteringsrate for kanalen.**

Egen analytisk pointe: En kanal kan give mange svar, fordi virksomheden har kontaktet mange flere mennesker der. For at vurdere effektivitet skal du også kende fx antal kontaktede, omkostninger og faktiske køb.

### Figur 9.8 - CRM-funktioner

> [!example] Indsæt figur 9.8 her - s. 384 / PDF 385

Fælles kundedata forbindes med funktioner inden for salg, marketing og service. Hvert område har både operationelle funktioner og analyse. Figuren er en **funktionsoversigt**, ikke en obligatorisk tidsrækkefølge for arbejdsopgaver.

### Figur 9.9 - Serviceproces og kundeloyalitet

> [!example] Indsæt figur 9.9 her - s. 385 / PDF 386

Rektangler er aktiviteter; diamanter er beslutningspunkter; cylinderen er en database. Den stiplede forbindelse til databasen angiver adgang til kundeoplysninger.

Efter modtagelse af en servicehenvendelse undersøges kundeinformationen. Tilgængelige oplysninger bruges til at score kunden. Høj værdi og loyalitet kan føre til særlige tilbud og ydelser. Kunder uden de pågældende oplysninger eller uden høj score bliver sendt videre til en servicemedarbejder og får deres henvendelse behandlet. **Figuren siger ikke, at kun værdifulde kunder får hjælp.**

### Figur 9.10 - Fra data til analyse

> [!example] Indsæt figur 9.10 her - s. 386 / PDF 387

Datakilder til venstre samles i et data warehouse eller en analytisk platform. OLAP og data mining bruges til analyser, der giver fx kundesegmenter, kundeprofiler og viden om frafald. Skeln mellem **datakilder**, **analyseværktøjer** og **analysens resultater**.

## 9. Det skal du især undgå at blande sammen

| Forveksling | Præcisering |
|---|---|
| ERP er bare en database | ERP omfatter integrerede moduler og processer, der bruger fælles data |
| Fælles data er automatisk korrekte data | Data kræver fælles definitioner, kvalitet og vedligehold |
| SCM handler kun om transport | Det omfatter også efterspørgsel, planlægning, indkøb, produktion og koordinering |
| Pull betyder ingen lagre | Pull handler om, hvad der udløser aktiviteter og genopfyldning |
| CRM er bare en kundeliste | CRM forbinder kundeoplysninger med salg, service, marketing og analyse |
| Stor omsætning betyder høj kundeværdi | CLTV inddrager også omkostninger og relationens forventede varighed |
| Standardisering fjerner behovet for organisatoriske valg | Standardisering kræver netop valg om fælles processer og ansvar |
| Digitale forsyningskæder er automatisk robuste | Synlighed hjælper, men afhængigheder og fysisk kapacitet skal også håndteres |

## 10. Repetition uden at kigge

> [!question]- 1. Hvordan kan ERP ændre mere end virksomhedens IT?
> Fælles moduler og data kræver sammenhængende processer, fælles definitioner og ændringer i roller og arbejdsgange. Afdelinger bliver mere afhængige af hinandens registreringer (s. 371-374, 388-389).

> [!question]- 2. Forklar bullwhip effect med egne ord.
> Små udsving i kundernes efterspørgsel forstærkes i ordrer upstream. Aktørerne reagerer på lokale og forvrængede signaler. Deling af faktisk efterspørgsel og ændret planlægning kan mindske problemet (s. 376-377).

> [!question]- 3. Hvad er forskellen på planning og execution?
> Planning fastlægger, hvad der bør ske, fx produktionsmængder. Execution understøtter gennemførelsen, fx lagerpluk og forsendelse (s. 377-378).

> [!question]- 4. Hvordan hænger operationelt og analytisk CRM sammen?
> Operationelt CRM understøtter kundekontakten og skaber data. Analytisk CRM bruger data til at finde mønstre og understøtte beslutninger, som kan ændre den efterfølgende kundekontakt (s. 385-386).

> [!question]- 5. Hvorfor er JIT ikke altid den eneste relevante prioritet?
> Små lagre mindsker lagerbinding, men øger afhængigheden af rettidige leverancer. Ved forstyrrelser kan buffere og alternative leverandører være værdifulde (s. 376, 398-400).

> [!question]- 6. Hvad ville du undersøge før en ERP-implementering?
> Med afsæt i kapitlet: Processer, datakvalitet, fælles definitioner, relevante standardfunktioner, behov for tilpasning, ansvar, uddannelse, integrationsbehov og konsekvenser for den løbende drift (s. 388-392).

## Forbindelser

- [[Laudon-2022-Kapitel-2-Afsnit-2.1-2.2-M2|Kapitel 2 - Forretningsprocesser og systemtyper]]
- [[Leonardi-2011-When-Flexible-Routines-Meet-Flexible-Technologies-M2|Leonardi - Rutiner og teknologi]]
- [[ERP]]
- [[Supply Chain Management]]
- [[Customer Relationship Management]]

**Egen kobling til Leonardi:** ERP-stoffet rejser spørgsmålet om, hvornår organisationen ændrer sine rutiner, og hvornår den ændrer teknologien. Leonardi kan bruges til at analysere denne relation nærmere; det er en kobling mellem dine tekster, ikke Laudon-kapitlets egen model.
