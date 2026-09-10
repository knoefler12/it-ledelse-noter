---
title: "M2 - Forberedelse til gruppearbejde om TPS, MIS, BI, ERP, CRM og SCM"
aliases:
  - "M2 - Seks informationssystemer"
course: "M2"
type: undervisningsforberedelse
sources:
  - "Laudon & Laudon (2022), kapitel 2, afsnit 2-1 og 2-2"
  - "Laudon & Laudon (2022), kapitel 9"
  - "Leonardi (2011)"
tags:
  - m2
  - informationssystemer
  - leonardi
  - affordances
  - imbrication
---

# M2 - Forberedelse til gruppearbejde om seks informationssystemer

> [!abstract] Sådan bruger du noten
> Du bliver tildelt ét af seks systemer og skal bagefter være den eneste ekspert i din matrixgruppe. Start med **lynoversigten**, og gå derefter til systemets seks svar. Hvert system afsluttes med et kort oplæg, som kan bruges mundtligt.

## Kilder og status for eksemplerne

- Laudon & Laudon (2022), *Management Information Systems*, kapitel 2, afsnit 2-1 og 2-2, s. 73-86.
- Laudon & Laudon (2022), kapitel 9, s. 368-401.
- Leonardi (2011), *When Flexible Routines Meet Flexible Technologies*, især s. 150-155.

Sidetal nedenfor henviser til de trykte sider. Beskrivelserne af systemernes formål og funktioner bygger på Laudon & Laudon. Anvendelsen af **affordance**, **constraint** og **imbrication** bygger på Leonardi. Da undervisningsopgaven ikke giver én bestemt organisation, er imbrication-forløbene markeret som **fair formodninger**.

## Lynoversigt

| System | Kort forklaring | Primært fokus | Typiske brugere | Typiske data |
|---|---|---|---|---|
| **TPS** | Registrerer og gennemfører daglige transaktioner | Stabil drift og præcis registrering | Frontpersonale, administrative medarbejdere, driftsledere | Ordrer, betalinger, timer, reservationer og lagerbevægelser |
| **MIS** | Sammenfatter driftsdata i faste ledelsesrapporter | Kontrol og opfølgning | Mellemledere og funktionsledere | Aggregerede TPS-data, budgetter, planer og afvigelser |
| **BI** | Organiserer og analyserer data til beslutninger | Indsigt, mønstre og analyse | Analytikere og ledere på flere niveauer | Data fra TPS, ERP, CRM, SCM og eksterne kilder |
| **ERP** | Integrerer centrale interne processer og data | Sammenhæng på tværs af virksomheden | Medarbejdere og ledere i salg, økonomi, HR, indkøb og produktion | Fælles stamdata og transaktionsdata på tværs af funktioner |
| **CRM** | Samler og bruger data om kunder og kontaktpunkter | Salg, service, marketing og kunderelationer | Sælgere, marketing, kundeservice og salgsledere | Kontakt-, købs-, service-, kampagne- og loyalitetsdata |
| **SCM** | Koordinerer efterspørgsel, forsyning og vareflow | Samarbejde gennem forsyningskæden | Indkøbere, planlæggere, lager, produktion, logistik og partnere | Prognoser, ordrer, lager, kapacitet, levering og transport |

> [!important] Kategorierne overlapper
> TPS, MIS og BI siger især noget om **behandling og anvendelse af data**. ERP, CRM og SCM siger især noget om **hvilke processer og relationer der forbindes**. Et ERP-system kan derfor indeholde TPS-funktioner, levere MIS-rapporter og være datakilde for BI.

## Leonardi-værktøjskassen

### Organizational routine

En **organisatorisk rutine** er et tilbagevendende mønster af handlinger mellem flere deltagere. Det er mere end en skriftlig procedure og mere end én persons vane. Eksempler er ordrebehandling, månedsrapportering og håndtering af kundeklager.

### Affordance

En **affordance** er en mulighed for målrettet handling, som opstår i relationen mellem:

1. en bruger eller brugergruppe med et mål, og
2. teknologiens faktiske egenskaber.

Et dashboard er en systemfunktion. For en salgschef, der vil opdage faldende salg, kan muligheden for hurtigt at sammenligne regioner være en affordance. En medarbejder uden adgang eller analyseansvar oplever ikke nødvendigvis samme affordance (Leonardi, s. 153-154).

### Constraint

En **constraint** er en oplevet begrænsning i relationen mellem brugerens mål og teknologiens muligheder. Den samme standardisering kan være en affordance for en økonomichef, der ønsker ens data, og en constraint for en specialist, der har brug for lokale undtagelser.

### Imbrication

**Imbrication** betyder, at menneskelig og materiel agency sammenføjes i overlappende lag. Tidligere valg bliver indlejret i systemer og rutiner og danner grundlag for senere ændringer (Leonardi, s. 150-155).

Et typisk analyseforløb er:

- Brugerne oplever en **constraint** og ændrer eller konfigurerer teknologien.
- Den nye teknologi giver en **affordance**, og brugerne ændrer rutinen for at udnytte den.
- Den nye rutine skaber nye mål og kan synliggøre en ny constraint.

Dette er et forklaringsmønster, ikke en regel om, at alle organisationer altid reagerer sådan.

---

# TPS - Transaction Processing System

## 1. Formål og rutiner

TPS registrerer og behandler de daglige, gentagne transaktioner, som er nødvendige for driften. En transaktion er ikke kun en betaling. Det kan også være en ordre, reservation, lønregistrering, modtagelse af en vare eller ændring i lagerbeholdningen (Laudon & Laudon, s. 76-77).

Systemet understøtter typisk strukturerede rutiner med på forhånd fastlagte trin og beslutningsregler:

- registrering og ekspedition af salgsordrer
- løn- og tidsregistrering
- lageropdatering og varemodtagelse
- booking og reservation
- fakturering og betaling

Kerneformålet er **driftsstabilitet, hastighed og præcision**. Hvis TPS ikke fungerer, kan den daglige drift hurtigt gå i stå.

## 2. Brugere og data

**Brugere:** Salgsmedarbejdere, kassepersonale, lønmedarbejdere, lagerpersonale, kundeservice, driftsledere og automatiske enheder som scannere eller webshops.

**Data:** Enkeltstående hændelser med tid, beløb, antal, kunde, medarbejder, vare og status. TPS-data er ofte detaljerede og aktuelle. Lønsystemet i figur 2.2 modtager medarbejderdata, opdaterer medarbejderfilen og producerer løn, rapporter og information til andre systemer (s. 77).

## 3. Affordances

For en medarbejder, der vil ekspedere en ordre korrekt, kan TPS give mulighed for at:

- registrere hændelsen én gang i en ensartet form
- kontrollere gyldighed, lager eller kredit efter faste regler
- se den aktuelle status på en ordre eller betaling
- udføre mange gentagne behandlinger hurtigt
- dokumentere, hvem der gjorde hvad og hvornår

Affordancen er fx **muligheden for at ekspedere en ordre på et pålideligt datagrundlag**. Den er relationel: Den samme logfunktion kan opleves som dokumentationshjælp af en leder og som overvågning af en medarbejder.

## 4. Constraints

- Faste felter og procestrin kan gøre undtagelser vanskelige at registrere.
- Obligatoriske data kan forsinke arbejdet, hvis oplysningerne ikke er tilgængelige.
- En forkert registrering kan spredes til efterfølgende processer og rapporter.
- Adgangsregler kan forhindre en medarbejder i at rette en fejl uden godkendelse.
- Fokus på det registrerbare kan gøre kvalitativ kontekst mindre synlig.

Constraints er kontekstafhængige. Kreditkontrol kan begrænse en sælger, der vil hjælpe en bestemt kunde, men støtte økonomiafdelingens mål om at begrænse tab.

## 5. Imbrication - fair formodning

En webshop registrerer oprindeligt ordrer, men lagerpersonalet skal manuelt kontrollere lageret. Det opleves som en constraint, fordi medarbejderne vil love kunderne en præcis levering. Organisationen forbinder TPS med realtidslageret. Funktionen giver mulighed for automatisk reservation, og salgsrutinen ændres, så varen reserveres ved ordren. Senere skaber den nye rutine et behov for automatisk genbestilling.

Historien viser lagene: manuel kontrol → teknisk lagerintegration → ny reservationsrutine → nyt behov for genbestilling. System og rutine er gensidigt formet over tid.

## 6. Sammenhæng til andre systemer

- **MIS** sammenfatter TPS-data i faste rapporter.
- **BI** analyserer TPS-data og kombinerer dem med andre kilder.
- **ERP** kan samle TPS-funktioner fra salg, lager, økonomi og HR i én løsning.
- **CRM** kan modtage køb, henvendelser og andre kundetransaktioner.
- **SCM** bruger salgs- og lagertransaktioner til genopfyldning og planlægning.

> [!quote] Mundtligt oplæg på cirka 45 sekunder
> TPS holder den daglige drift kørende ved at registrere gentagne transaktioner som ordrer, timer og lagerbevægelser. Det bruges især af front- og driftspersonale og arbejder med detaljerede, aktuelle data. En central affordance er, at medarbejderen kan gennemføre og dokumentere en transaktion hurtigt efter faste regler. De samme regler kan være en constraint, når virkeligheden ikke passer i felterne. Over tid kan sådanne begrænsninger føre til systemændringer, som bagefter ændrer arbejdsrutinen. TPS leverer desuden grunddata til MIS, BI, ERP, CRM og SCM.

---

# MIS - Management Information System

## 1. Formål og rutiner

MIS sammenfatter typisk data fra TPS i regelmæssige rapporter om virksomhedens performance. Det understøtter rutinepræget planlægning, kontrol og opfølgning på kendte spørgsmål (Laudon & Laudon, s. 78-79).

Typiske rutiner er:

- uge- og månedsrapportering
- sammenligning af realiserede tal med budget eller plan
- opfølgning på salg, omkostninger og produktivitet
- identifikation og eskalering af afvigelser
- fordeling af standardrapporter til ledere

## 2. Brugere og data

**Brugere:** Mellemledere, funktionsledere, controllere og medarbejdere, der producerer ledelsesrapportering.

**Data:** Primært aggregerede interne data fra TPS, suppleret med budgetter, planer, mål og tidligere perioder. Figur 2.4 viser fx faktisk salg i forhold til planlagt salg. Et forholdstal på 0,85 betyder 85 % af planen, ikke en vækst på 85 % (s. 79).

## 3. Affordances

For en leder, der vil følge driften, kan MIS give mulighed for at:

- få et regelmæssigt og ensartet overblik
- sammenligne enheder, produkter og perioder
- se afvigelser fra mål
- rette opmærksomheden mod områder, der kræver handling
- koordinere opfølgning med andre ledere på et fælles talgrundlag

En rapportfunktion bliver altså en affordance, når den hjælper en bestemt leder med at opdage og håndtere relevante afvigelser.

## 4. Constraints

- Faste rapporter besvarer især på forhånd definerede spørgsmål.
- Aggregering kan skjule variationer og lokale forklaringer.
- Forsinket perioderapportering kan give et gammelt billede af situationen.
- Mål og KPI'er kan styre opmærksomheden mod det målbare.
- Lederen kan se, **at** der er en afvigelse, uden at rapporten forklarer **hvorfor**.

## 5. Imbrication - fair formodning

Ledelsen modtager oprindeligt en månedlig salgsrapport. Når markedet ændrer sig hurtigt, opleves rapportens forsinkelse som en constraint. Systemet konfigureres til ugentlige rapporter og regionale afvigelser. Den nye synlighed giver en affordance: Lederne indfører et ugentligt opfølgningsmøde. Mødet skaber siden et ønske om kommentarer direkte i rapporten, hvilket bliver et nyt krav til teknologien.

## 6. Sammenhæng til andre systemer

- **TPS** leverer detaljerede transaktionsdata.
- **ERP** kan være både datakilde og platform for MIS-rapporterne.
- **CRM** leverer fx salgs- og servicedata; **SCM** leverer leverings- og lagerdata.
- **BI** kan give friere og mere avanceret analyse end de faste MIS-rapporter.

> [!quote] Mundtligt oplæg på cirka 45 sekunder
> MIS giver især mellemledere faste rapporter til planlægning og kontrol. Systemet sammenfatter typisk TPS-data og sammenligner resultater med planer eller tidligere perioder. Affordancen er et fælles, regelmæssigt overblik, som gør afvigelser synlige. En constraint er, at faste og aggregerede rapporter kan skjule årsager og besvare nye spørgsmål dårligt. Hvis ledelsen fx kræver hyppigere rapporter, kan systemet ændres, hvorefter lederne udvikler en ny ugentlig opfølgningsrutine. BI, ERP, CRM og SCM kan levere eller videreanalysere dataene.

---

# BI - Business Intelligence

## 1. Formål og rutiner

BI omfatter data og softwareværktøjer, der organiserer, analyserer og gør data tilgængelige som beslutningsgrundlag. BI kan understøtte flere ledelsesniveauer og omfatter mere end dashboards (Laudon & Laudon, s. 77-81; analytisk CRM s. 385-386).

Typiske rutiner er:

- opbygning og vedligeholdelse af rapporter og dashboards
- ad hoc-analyser og søgning efter mønstre
- segmentering og prognoser
- drill-down fra et overblik til mere detaljerede data
- fælles gennemgang og fortolkning af nøgletal

## 2. Brugere og data

**Brugere:** Dataanalytikere, controllere, mellemledere, topledere og i self-service BI også almindelige fagbrugere.

**Data:** Data fra TPS, ERP, CRM og SCM, ofte samlet i et data warehouse eller en analytisk platform. Der kan også indgå eksterne markeds-, befolknings- eller vejrdata. BI kan bruge historiske såvel som aktuelle data.

## 3. Affordances

Afhængigt af brugerens mål kan BI give mulighed for at:

- kombinere data, der tidligere lå i adskilte systemer
- opdage mønstre og afvigelser, som er svære at se i rådata
- undersøge et tal gennem filtrering og drill-down
- sammenligne scenarier, perioder og grupper
- dele en fælles visualisering i beslutningsarbejdet

For en indkøbschef kan kombinationen af salgsprognose og lagerdata skabe mulighed for at planlægge indkøb mere præcist. For en analytiker kan adgang til de samme data skabe mulighed for at teste nye forklaringer.

## 4. Constraints

- Resultaterne begrænses af datakvalitet og datadefinitioner.
- Et dashboard fremhæver nogle mål og skjuler andre.
- Brugere kan forveksle korrelation med årsagssammenhæng.
- Modeller bygger på antagelser og historiske mønstre, som kan bryde sammen ved store forandringer.
- Begrænset adgang eller manglende analysekompetence kan gøre funktionerne ubrugelige for visse grupper.

BI skaber ikke automatisk en korrekt beslutning. Systemet gør bestemte analyser mulige; mennesker skal stadig fortolke resultaterne.

## 5. Imbrication - fair formodning

En organisation begynder med et centralt analyseteam. Afdelingerne oplever ventetiden på rapporter som en constraint og indfører self-service BI. Fagbrugere kan nu selv filtrere og visualisere data, hvilket giver en affordance og skaber en ny rutine med lokale analyser før ledelsesmøder. De forskellige afdelinger producerer efterhånden modstridende tal. Det opleves som en ny constraint, og organisationen indfører fælles datadefinitioner og governance.

## 6. Sammenhæng til andre systemer

- **TPS** leverer detaljerede hændelsesdata.
- **ERP** leverer sammenhængende interne data.
- **CRM** leverer kunde-, salgs- og servicedata.
- **SCM** leverer data om efterspørgsel, lager, kapacitet og levering.
- **MIS** er ofte mere fast og rutineorienteret; BI kan være mere udforskende. I praksis overlapper de.

> [!quote] Mundtligt oplæg på cirka 45 sekunder
> BI samler og analyserer data, så ledere og analytikere kan opdage mønstre og træffe bedre oplyste beslutninger. Det kan bruge data fra alle de øvrige systemer. En affordance er fx at kunne gå fra et samlet salgstal ned til region og produkt. Constraints opstår ved dårlig datakvalitet, misvisende visualiseringer og modeller, som bygger på forældede antagelser. Self-service BI kan ændre analysearbejdet, men kan bagefter skabe behov for fælles datadefinitioner. BI overlapper med MIS, men er ofte mere fleksibelt og analytisk end faste ledelsesrapporter.

---

# ERP - Enterprise Resource Planning

## 1. Formål og rutiner

ERP integrerer centrale interne processer gennem softwaremoduler og en fælles database. En registrering i én proces bliver tilgængelig for andre funktioner (Laudon & Laudon, s. 371-374).

Systemet understøtter fx:

- salgsordre fra kreditkontrol til levering og fakturering
- indkøb fra rekvisition til betaling
- økonomi, debitorer, kreditorer og rapportering
- lager, produktion og materialebehov
- HR, tidsregistrering og løn

## 2. Brugere og data

**Brugere:** Medarbejdere og ledere i salg, økonomi, indkøb, lager, produktion og HR samt systemadministratorer og procesansvarlige.

**Data:** Fælles stamdata om kunder, leverandører, medarbejdere og produkter samt transaktioner som ordrer, fakturaer, lagerbevægelser og betalinger.

## 3. Affordances

For brugere, der vil koordinere et tværgående forløb, kan ERP give mulighed for at:

- registrere data én gang og genbruge dem på tværs
- se samme ordres status fra flere afdelinger
- standardisere processer og begreber
- automatisere afhængigheder mellem procestrin
- få et samlet billede af ressourcer og økonomi

For økonomiledelsen kan standardisering være en affordance, fordi enheder kan sammenlignes. For en lagerarbejder kan den aktuelle ordrestatus gøre korrekt plukning mulig.

## 4. Constraints

- Standardprocesser og obligatoriske felter kan passe dårligt til lokale behov.
- Fejl i fælles data kan påvirke mange funktioner.
- Afdelinger bliver afhængige af, at andre registrerer korrekt og rettidigt.
- Roller og adgangsregler kan gøre hurtige undtagelser vanskelige.
- Omfattende customization kan gøre systemet svært at opgradere; begrænset customization kan omvendt tvinge rutiner ind i en uhensigtsmæssig standard (s. 372-373, 388-392).

## 5. Imbrication - fair formodning

En virksomhed har forskellige indkøbsrutiner i hver afdeling. Ledelsen vil have fælles overblik, men ERP-standardprocessen passer ikke til alle lokale godkendelser. Det opleves som en constraint. Organisationen konfigurerer godkendelsesniveauer og standardiserer samtidig leverandørdata. Den fælles workflowfunktion giver mulighed for central opfølgning, så der etableres en ny rutine med fælles indkøbsstyring. Senere synliggør rutinen et behov for en særlig hasteprocedure.

Det er imbrication, fordi både systemets konfiguration og indkøbsrutinen bærer spor af de tidligere valg.

## 6. Sammenhæng til andre systemer

- ERP indeholder ofte **TPS-funktioner**, fx ordre- og lønbehandling.
- ERP-data kan danne grundlag for **MIS-rapporter** og **BI-analyser**.
- **CRM** kan sende kundeordrer til ERP og modtage ordre- og leveringsstatus.
- **SCM** kan bruge ERP's lager-, indkøbs- og produktionsdata og sende planer tilbage.

> [!quote] Mundtligt oplæg på cirka 45 sekunder
> ERP forbinder centrale interne processer gennem integrerede moduler og fælles data. Det bruges bredt i salg, økonomi, HR, indkøb og produktion. En affordance er, at flere afdelinger kan koordinere ud fra samme ordre og status. Standarder og obligatoriske workflows kan samtidig være constraints for lokale arbejdsgange. Organisationen kan konfigurere systemet og ændre sine rutiner, hvorefter nye behov opstår; det er et imbrikationsforløb. ERP kan indeholde TPS, levere data til MIS og BI og udveksle data med CRM og SCM.

---

# CRM - Customer Relationship Management

## 1. Formål og rutiner

CRM samler og anvender kundeinformation på tværs af salg, marketing, service og kontaktpunkter. Målet er sammenhængende kundekontakt, bedre service og mere værdifulde kunderelationer (Laudon & Laudon, s. 381-388).

Systemet understøtter fx:

- registrering og opfølgning på kundeemner og salgsmuligheder
- tilbud, salgsaktiviteter og prognoser
- kundesager og kontakt-/servicehistorik
- kampagner, segmentering og responsmåling
- fastholdelse, cross-selling og vurdering af kundefrafald

## 2. Brugere og data

**Brugere:** Sælgere, salgsledere, marketingmedarbejdere, kundeservice, callcentre og analytikere. Kunder kan bruge selvbetjeningsfunktioner.

**Data:** Kontaktoplysninger, touchpoints, køb, tilbud, servicehenvendelser, klager, kampagnerespons, præferencer, loyalitet og eventuelt customer lifetime value.

## 3. Affordances

CRM kan i relation til forskellige brugermål give mulighed for at:

- se kundens tidligere kontakt på tværs af kanaler
- følge kundeemner og aftale næste salgsaktivitet
- sende en sag til den medarbejder, der bedst kan løse den
- målrette kampagner og relevante tilbud
- identificere kunder med høj værdi eller risiko for frafald

For en servicemedarbejder kan det fælles kundebillede skabe mulighed for at hjælpe kunden uden at bede om hele historien igen. For salgsledelsen kan pipeline-data skabe mulighed for at koordinere salgsindsatsen.

## 4. Constraints

- Faste kategorier kan forenkle komplekse kunder og henvendelser.
- Medarbejdere kan opleve registrering som ekstraarbejde eller kontrol.
- Adgang til ét “samlet kundebillede” kan skabe risiko for forældede eller forkerte profiler.
- Scoring kan prioritere profitable kunder og påvirke, hvilken service kunder får.
- Systemet kan fremme standardiseret kontakt, som opleves upersonlig.

Figur 9.9 viser præferencebehandling af værdifulde, loyale kunder. Det gør det relevant at spørge, hvem der får hvilke tilbud og serviceniveauer (s. 385).

## 5. Imbrication - fair formodning

Sælgere fører først egne kundelister. Ledelsen oplever manglende fælles overblik som en constraint og indfører et CRM med fælles pipeline. Funktionen giver mulighed for at fordele og følge kundeemner, så teamet indfører ugentlige pipeline-møder. Møderne gør det tydeligt, at standardkategorierne ikke passer til alle salg. Systemet konfigureres derfor med nye stadier. Den nye teknologi bygger på den rutine, som den tidligere teknologi selv var med til at skabe.

## 6. Sammenhæng til andre systemer

- Kundekøb og henvendelser kan registreres som **TPS-data**.
- **ERP** håndterer typisk ordre, fakturering og levering efter salget.
- **SCM** bruger efterspørgsels- og ordredata til planlægning.
- **MIS** kan rapportere salg og service efter faste mål.
- **BI** og analytical CRM analyserer segmenter, churn og CLTV.

> [!quote] Mundtligt oplæg på cirka 45 sekunder
> CRM skaber et fælles kundebillede til salg, service og marketing. Brugerne arbejder med kontakt-, købs-, kampagne- og servicedata. En affordance er, at en servicemedarbejder kan se kundens historik og give sammenhængende hjælp. Faste kategorier, registreringskrav og kundescoring kan være constraints. Hvis sælgernes behov fører til nye pipelinefelter, og disse bagefter skaber en ny møderutine, ser vi imbrication. CRM sender ordrer til ERP, skaber TPS-data og leverer kunde- og efterspørgselsdata til BI, MIS og SCM.

---

# SCM - Supply Chain Management

## 1. Formål og rutiner

SCM koordinerer efterspørgsel, forsyning, produktion, lager og distribution gennem et netværk af organisationer. Formålet er at få varer og information gennem kæden med passende omkostninger, leveringsevne og robusthed (Laudon & Laudon, s. 374-380, 398-400).

Typiske rutiner er:

- efterspørgselsprognoser og supply chain planning
- indkøb og leverandørkoordinering
- produktions- og kapacitetsplanlægning
- genopfyldning og lagerstyring
- lagerpluk, forsendelse og transport
- håndtering af forsinkelser, returvarer og forsyningsrisici

## 2. Brugere og data

**Brugere:** Indkøbere, demand planners, produktionsplanlæggere, lagerpersonale, logistikmedarbejdere, ledere og eksterne leverandører eller logistikpartnere.

**Data:** Salg og efterspørgsel, prognoser, kundeordrer, lagerbeholdning, materialebehov, produktionskapacitet, leveringstider, transport, leverandørstatus og lokationer.

## 3. Affordances

SCM kan give brugerne mulighed for at:

- se lager og forventet behov på tværs af lokationer
- koordinere planer med leverandører og distributører
- reagere på forsinkelser og omfordele forsyninger
- reducere bullwhip effect gennem bedre deling af faktisk efterspørgsel
- sammenligne service, lageromkostninger og risiko i planlægningen
- følge afhængigheder længere upstream i forsyningsnetværket

For en produktionsplanlægger kan fælles leverandør- og lagerdata skabe mulighed for at ændre planen før en mangel stopper produktionen.

## 4. Constraints

- Systemets prognoser kan videreføre fejl og forældede historiske mønstre.
- Standardiserede data og processer kan være svære at håndhæve mellem selvstændige virksomheder.
- Manglende data fra underleverandører giver begrænset synlighed.
- Optimering af én virksomheds lager kan flytte omkostninger eller risiko til andre led.
- JIT og små lagre kan øge afhængigheden af præcise og rettidige leverancer.

Den samme lave lagerbeholdning kan være en affordance i forhold til kapitalbinding og en constraint i forhold til forsyningssikkerhed.

## 5. Imbrication - fair formodning

En producent planlægger ud fra månedlige leverandøroplysninger. Forsinkelser opdages for sent og opleves som en constraint. Leverandørportalen ændres, så partnere deler status løbende. Funktionen giver mulighed for tidligere omplanlægning, og der opstår en ny daglig undtagelsesrutine. Rutinen viser derefter, at virksomheden mangler data om leverandørernes underleverandører, hvilket fører til nye krav om tier 2-data.

## 6. Sammenhæng til andre systemer

- **TPS** leverer aktuelle ordre- og lagerbevægelser.
- **ERP** leverer stamdata, indkøb, lager og produktionsstatus.
- **CRM** og salg leverer kundeordrer og efterspørgselsinformation.
- **MIS** rapporterer fx leveringsevne og lager i faste intervaller.
- **BI** analyserer prognosefejl, leverandørperformance, risiko og scenarier.

> [!quote] Mundtligt oplæg på cirka 45 sekunder
> SCM forbinder efterspørgsel, leverandører, produktion, lager og levering. Brugerne er blandt andre indkøbere, planlæggere og logistikmedarbejdere, og de arbejder med prognoser, ordrer, lager, kapacitet og leveringstid. En affordance er at opdage en kommende mangel og omplanlægge. Dårlige prognoser, manglende leverandørdata og JIT-afhængighed kan være constraints. Hvis forsinkelser fører til en ny portal, som bagefter skaber en daglig undtagelsesrutine, er det imbrication. SCM udveksler især data med TPS, ERP, CRM, MIS og BI.

---

# Sammenhængen mellem de seks systemer

En realistisk ordre kan bevæge sig sådan gennem landskabet:

1. **CRM** registrerer kunden, salgsarbejdet og relationen.
2. **TPS** registrerer selve ordren som en transaktion.
3. **ERP** forbinder ordren med lager, økonomi, produktion og fakturering.
4. **SCM** bruger efterspørgslen til forsyning, genopfyldning og levering.
5. **MIS** sammenfatter salget og leveringen i faste rapporter.
6. **BI** kombinerer dataene og undersøger mønstre, årsager og scenarier.

> [!warning] Dette er en analytisk illustration
> Det er ikke en obligatorisk teknisk rækkefølge. I et konkret softwarelandskab kan funktionerne være samlet i én platform, fordelt mellem flere produkter eller organiseret på en anden måde.

| Hvis spørgsmålet er ... | Kig især på ... |
|---|---|
| Hvad skete der i den enkelte ordre? | TPS |
| Hvordan klarede afdelingen sig i denne måned? | MIS |
| Hvilke mønstre og forklaringer findes i data? | BI |
| Hvordan hænger de interne processer og data sammen? | ERP |
| Hvad ved vi om kunden og relationen? | CRM |
| Hvordan skaffer, producerer og leverer vi varen? | SCM |

# Seks spørgsmål, du kan stille til ethvert system

1. **Mål:** Hvilket konkret mål har denne brugergruppe?
2. **Funktion:** Hvilke tekniske egenskaber er faktisk tilgængelige?
3. **Affordance:** Hvilken handling bliver mulig i relationen mellem mål og funktion?
4. **Constraint:** Hvilket mål bliver vanskeligt at opnå, og for hvem?
5. **Historie:** Hvilke tidligere rutiner og systemvalg har skabt situationen?
6. **Forandring:** Ændres teknologien, rutinen eller begge over flere omgange?

# Forbindelser

- [[Laudon-2022-Kapitel-2-Afsnit-2.1-2.2-M2|Laudon & Laudon - Kapitel 2, afsnit 2.1-2.2]]
- [[Laudon-2022-Kapitel-9-Enterprise-Applications-M2|Laudon & Laudon - Kapitel 9]]
- [[Leonardi-2011-When-Flexible-Routines-Meet-Flexible-Technologies-M2|Leonardi - Affordance, constraint og imbrication]]
- [[Organisatoriske rutiner]]
- [[Business intelligence]]
- [[Enterprise applications]]
