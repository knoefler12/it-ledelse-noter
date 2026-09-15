---
tags: [litteraturnoter, it-infrastruktur, cloud, platforme]
aliases: [Laudon kapitel 5]
---

# Laudon & Laudon (2022) – Kapitel 5: IT Infrastructure and Emerging Technologies

**Kilde:** *Management Information Systems: Managing the Digital Firm*, 17th edition, Global Edition, kapitel 5. Noten bygger på den uploadede bog.

**Sidetal:** Bogens trykte sidetal bruges. Læg 1 til for at finde PDF-siden: bogens s. 198 er PDF-side 199. Kapitelåbningen er s. 194; fagteksten begynder s. 197. Afsluttende case står s. 238–240, efterfulgt af referencer.

**Om figurer og eksempler:** Originale figurer er indsat ved forklaringerne. Figurerne afspejler bogens historiske teknologi- og markedsbillede; de er ikke opdaterede markedsdata. Eksempler mærket *eget eksempel* er illustrationer, ikke bogens cases.

## 1. Hovedpointen på ét minut

**It-infrastruktur er det fælles fundament, som organisationens informationssystemer bygger på.** Det omfatter hardware, software, netværk, datahåndtering og tjenester – også menneskelige kompetencer, uddannelse og styring. Infrastrukturen skal vurderes ud fra, hvilke forretningsmæssige ydelser den gør mulige. (s. 197–199)

Ledelsesopgaven er at vælge et fundament, der passer til organisationens strategi, kan ændres med behovene og har acceptable samlede omkostninger. Derfor er kapitlet lige så meget et ledelseskapitel som et teknologikapitel. (s. 228–232)

> [!important] Det vigtigste at kunne forklare
> 1. Hvorfor infrastruktur er mere end computere og servere.
> 2. Forskellen mellem virtualisering, cloud og cloudmodellerne.
> 3. Hvordan integration og standarder gør systemer anvendelige sammen.
> 4. Hvorfor indkøbspris ikke er det samme som totalomkostning.
> 5. Hvordan strategi, behov og konkurrence indgår i investeringsbeslutninger.

## 2. Infrastruktur som en platform af tjenester

Et **service platform perspective** betyder, at man ser på de tjenester, infrastrukturen leverer, frem for alene at tælle tekniske komponenter. En hurtig computer har eksempelvis værdi, fordi en medarbejder kan udføre sit arbejde bedre – ikke bare fordi processoren har bestemte specifikationer. (s. 197–199)

Bogen medregner blandt andet computing, telekommunikation, datahåndtering, applikationer, fysiske faciliteter, it-ledelse, standarder, uddannelse og forskning/udvikling som infrastrukturtjenester.

![Figur 5.1 – sammenhæng mellem strategi, infrastruktur og kapabiliteter](Laudon-5-1.png)

*Figur 5.1, s. 198.*

**Sådan læser du modellen:** Forretningsstrategi, it-strategi og informationsteknologi påvirker hinanden og den infrastruktur, virksomheden etablerer. Infrastrukturen muliggør ydelser til kunder, leverandører og organisationen selv. De buede forbindelser viser, at påvirkningen ikke kun går fra forretning til teknologi: teknologiske muligheder kan også ændre strategien.

**Business capabilities** betyder, hvad virksomheden faktisk er i stand til at gøre. En evne til at vise kunder korrekte leveringstider kræver eksempelvis adgang til pålidelige ordre-, lager- og produktionsdata. Dette er et eget eksempel på modellens pointe.

## 3. Fem infrastrukturepoker – som overlapper

![Figur 5.2 – it-infrastrukturens udvikling](Laudon-5-2.png)

*Figur 5.2, s. 200; forklaring s. 199–203.*

| Epoke i bogen | Grundidé | Organisatorisk betydning |
| --- | --- | --- |
| **Mainframe/minicomputer, fra 1959** | Store fælles computere; senere mindre maskiner til afdelinger. | Først stærk centralisering, derefter mulighed for lokal computing. |
| **Personal computer, fra 1981** | Individuelle computere til medarbejdere. | Lokale produktivitetsværktøjer som regneark og tekstbehandling. |
| **Client/server, fra 1983** | Klienter og servere deler arbejdet. | Brugerne får adgang til fælles data og tjenester over netværk. |
| **Enterprise computing, fra 1992** | Systemer og netværk forbindes på tværs af virksomheden. | Understøtter sammenhængende processer frem for isolerede afdelingsløsninger. |
| **Cloud/mobile, fra 2000** | Ressourcer leveres over netværk og tilgås fra forskellige enheder. | Kapacitet og tjenester kan anskaffes mere fleksibelt. |

**Nuance:** Epokerne erstatter ikke hinanden fuldstændigt. En organisation kan samtidig have mainframes, pc'er, servere og cloudtjenester. Modellen er en historisk oversigt, ikke en modenhedsskala, hvor alt ældre automatisk er dårligere.

### Client/server og flere lag

![Figur 5.3 – en flerlags client/server-arkitektur](Laudon-5-3.png)

*Figur 5.3, s. 202; forklaring s. 201–202.*

- **Client:** Brugerens adgang til systemet, fx en browser.
- **Web server:** Håndterer webforespørgsler og leverer webindhold.
- **Application server:** Udfører applikationslogik og forbinder til virksomhedens systemer.
- **Data/back-end:** De underliggende data og forretningssystemer.

**N-tier/multitier** betyder flere lag med forskellige opgaver. Flere logiske lag betyder ikke nødvendigvis én fysisk computer pr. lag. Figuren handler om fordeling af arbejdet; den er ikke en liste over obligatoriske maskiner.

## 4. Hvad driver udviklingen?

### Mere regnekraft og lavere komponentpris

**Moore's Law** beskrives som en historisk observation om stigende antal komponenter/transistorer på chips. Bogen gennemgår også populære varianter om regnekraft og pris. Det er en udviklingstendens med tekniske og økonomiske begrænsninger, ikke en naturlov eller garanti. (s. 203–205)

![Figur 5.4 og 5.5 – processorudvikling og faldende chipomkostninger](Laudon-5-4-og-5-5.png)

*Figur 5.4 og 5.5, s. 204. Aflæs den historiske tendens: større teknisk kapacitet og faldende komponentomkostninger. Brug ikke grafen som dokumentation for aktuelle priser eller en præcis fremtidsprognose.*

### Billigere lagring

**Law of Mass Digital Storage:** Stadig mere information kan lagres for et givet beløb. Det gør omfattende digitale databaser og nye dataintensive anvendelser økonomisk mulige. (s. 205–206)

![Figur 5.6 – mere lagerplads pr. dollar](Laudon-5-6.png)

*Figur 5.6, s. 206. Y-aksen viser lagringskapacitet pr. dollar, ikke organisationens samlede lagerudgift. Billigere enheder kan ledsages af større samlet forbrug.*

### Netværk, kommunikation og standarder

**Metcalfe's Law/network economics:** Når flere relevante deltagere tilslutter sig et netværk, kan værdien for deltagerne vokse gennem flere forbindelser og anvendelsesmuligheder. Kapitlet bruger dette til at forklare efterspørgslen efter computing og kommunikation. Det er ikke det samme som, at enhver ekstra bruger altid skaber samme værdi. (s. 205–206)

![Figur 5.7 – faldende kommunikationsomkostninger](Laudon-5-7.png)

*Figur 5.7, s. 207. Faldende pris på kommunikationskapacitet understøtter netværksbaserede løsninger. Grafen viser en historisk prisudvikling, ikke virksomhedens samlede telebudget.*

**Technology standards** gør forskellige produkter i stand til at kommunikere og arbejde sammen. Det kan øge markedets størrelse og skabe stordriftsfordele, fordi flere bruger kompatible løsninger. Tabel 5.1 på s. 208 giver eksempler som Ethernet, TCP/IP og webstandarder. (s. 206–208)

## 5. Infrastrukturens syv komponentområder

![Figur 5.8 – infrastrukturets økosystem](Laudon-5-8.png)

*Figur 5.8, s. 209; forklaring s. 207–212. Firmanavnene er bogens eksempler. Det centrale er de syv områder og behovet for koordinering mellem dem.*

| Område | Hvad omfatter det? | Hvorfor er det relevant? |
| --- | --- | --- |
| **Computer hardware platforms** | Computere, servere og mobile enheder. | Leverer den fysiske behandlingskapacitet. |
| **Operating system platforms** | Styresystemer. | Administrerer maskinens ressourcer og understøtter software. |
| **Enterprise software applications** | Fælles virksomhedsapplikationer og middleware. | Understøtter og forbinder virksomhedens processer. |
| **Data management and storage** | Databaser og lagring. | Gør data tilgængelige og håndterbare. |
| **Networking/telecommunications** | Netværksudstyr og kommunikationstjenester. | Forbinder brugere og systemer. |
| **Internet platforms** | Teknologi og tjenester til virksomhedens webløsninger. | Gør webbaserede tjenester mulige. |
| **Consulting and system integration** | Rådgivning og integrationsekspertise. | Får delene til at fungere sammen med eksisterende systemer. |

**Middleware** forbinder ellers adskilte applikationer. **Legacy systems** er eksisterende, ofte ældre systemer, som organisationen stadig er afhængig af. Et legacy-system kan fortsat løse en vigtig opgave; udfordringen kan være integration og ændring snarere end den daglige funktion. (s. 210–212)

## 6. Hardwaretrends og cloud

### Mobilitet, BYOD og consumerization

**Mobile digital platform** dækker blandt andet smartphones, tablets og andre mobile enheder. **BYOD – Bring Your Own Device** betyder brug af egne enheder i arbejdet. **Consumerization of IT** er det bredere fænomen, hvor teknologi fra forbrugermarkedet trænger ind i organisationer. (s. 212–213)

Det giver medarbejdere flere muligheder, men udfordrer central styring, support og sikkerhed. BYOD er dermed også et spørgsmål om regler og ansvar.

### Virtualisering

**Virtualization** adskiller den logiske adgang til ressourcer fra deres konkrete fysiske organisering. Én server kan eksempelvis optræde som flere virtuelle maskiner; flere lagringsenheder kan fremstå som én samlet ressource. Det kan forbedre kapacitetsudnyttelsen og reducere plads-, energi- og administrationsbehov. (s. 213–214)

**Software-defined storage (SDS)** adskiller styringen af lagring fra den konkrete lagringshardware.

> [!example] Eget eksempel
> En Windows-VM på en Mac illustrerer forskellen mellem fysisk maskine og logisk computermiljø. Det er virtualisering, men ikke i sig selv cloud. Cloud beskriver også, hvordan ressourcer stilles til rådighed og administreres som tjenester.

### Cloud computing og de fem kendetegn

![Figur 5.9 – cloud computing-platform](Laudon-5-9.png)

*Figur 5.9, s. 214. Forskellige enheder tilgår fælles infrastruktur-, applikations- og platformstjenester. Skyen er en leveringsform for ressourcer, ikke fravær af fysiske servere.*

Cloud giver adgang til en fælles pulje af ressourcer over netværk efter behov. Bogen fremhæver fem kendetegn: (s. 214–215)

1. **On-demand self-service:** Brugeren kan selv bestille ressourcer efter behov.
2. **Ubiquitous network access:** Adgang gennem almindelige netværk og enheder.
3. **Resource pooling:** Ressourcer samles og fordeles mellem brugere.
4. **Rapid elasticity:** Kapacitet kan hurtigt øges eller reduceres.
5. **Measured service:** Forbrug måles og kan danne grundlag for afregning.

### IaaS, PaaS og SaaS

| Servicetype | Hvad får kunden? | Enkel huskeregel |
| --- | --- | --- |
| **IaaS – Infrastructure as a Service** | Regnekraft, lagring og netværksressourcer til egne systemer. | Lej infrastrukturen. |
| **PaaS – Platform as a Service** | Infrastruktur og en understøttet platform/værktøjer til at udvikle og køre egne applikationer. | Byg din applikation på en leveret platform. |
| **SaaS – Software as a Service** | En applikation leveret som tjeneste over netværk. | Brug den leverede applikation. |

*Kilde: s. 215, 217–218. Den konkrete ansvarsfordeling afhænger også af produkt og aftale.*

![Figur 5.10 – AWS som samling af tjenester](Laudon-5-10.png)

*Figur 5.10, s. 215. Figuren viser bredden af tjenester, fx computing, lagring og databaser. En udbyder er ikke begrænset til én servicetype; figuren er ikke en rangordning af leverandører.*

### Public, private og hybrid cloud

Denne opdeling handler om cloudens anvendelse og organisering, mens IaaS/PaaS/SaaS handler om, **hvad der leveres**. (s. 218–219; tabel 5.2)

- **Public cloud:** En udbyders tjenester stilles til rådighed for flere kunder. Det betyder ikke, at kundernes data er offentlige.
- **Private cloud:** Cloudinfrastruktur anvendes alene af én organisation. Den kan være internt eller eksternt hostet og administreret.
- **Hybrid cloud:** En kombination af private og offentlige cloudmiljøer.

**Fordele:** Fleksibilitet, adgang til kapacitet og mulighed for mindre indledende investering. **Udfordringer:** Afhængighed af leverandøren, tilgængelighed, sikkerhed, datahåndtering og styring af omkostninger. Cloud er ikke automatisk billigst. (s. 218–219, 229)

### Edge, green computing og processorer

- **Edge computing:** Noget databehandling sker nær datakilden frem for i et fjernt datacenter. Det kan reducere datatrafik og forsinkelse. Eksempelvis kan lokale sensordata sammenfattes før afsendelse til skyen. (s. 219)
- **Green computing/green IT:** Miljøhensyn gennem teknologiens livsforløb: design, fremstilling, brug og bortskaffelse. Energiforbrug, køling og effektiv kapacitetsudnyttelse er centrale emner. (s. 219–220)
- **Multicore processor:** Flere processorkerner på én chip, som kan understøtte samtidig behandling og bedre ressourceudnyttelse. (s. 220)
- **Quantum computing:** Kapitlet introducerer beregning baseret på kvantefysiske principper som en emerging technology. Læs omtalen som bogens introduktion til potentielle anvendelser, ikke som dokumentation for, at teknologien erstatter almindelige computere i alle opgaver. (s. 213)

## 7. Softwareplatforme og integration

### Open source og Linux

Kapitlet fremhæver software, hvis kildekode er tilgængelig og kan ændres under de relevante licensvilkår. Linux bruges som eksempel på en platform, der kan understøtte mange hardwaremiljøer. Ledelsesmæssigt er pris, support, kompetencer, fleksibilitet og innovation relevante. (s. 220–223)

**Nuance:** Bogens korte formulering om, at open source og afledte værker skal være gratis, bør ikke bruges som en universel licensregel. Læs den sammen med bogens omtale af kommercielle Linux-versioner med betalt support. Til studiebrug er hovedpointen åben kode og udviklingsmuligheder; licensvilkår må vurderes konkret.

### Webteknologier – kend forskellene

| Begreb | Rolle i kapitlet |
| --- | --- |
| **Java** | Programmeringssprog, hvor en Java Virtual Machine understøtter kørsel på forskellige platforme. |
| **JavaScript** | Programmeringssprog til blandt andet interaktion i websider. Det er et andet sprog end Java. |
| **HTML/HTML5** | Markup til strukturering af webindhold; HTML5 understøtter blandt andet multimedier. |
| **XML** | Markup til strukturering og udveksling af data med beskrivende tags. |

*Kilde: s. 221–224. Kapitlets omtale af konkrete browserteknologier og produkter skal læses i bogens tidskontekst.*

### Web services og serviceorienteret arkitektur

**Web services** gør funktioner tilgængelige for andre systemer gennem standardiseret kommunikation. Kapitlets fremstilling lægger vægt på XML. **Service-Oriented Architecture (SOA)** organiserer software som selvstændige tjenester, der kan kombineres og genbruges. (s. 224–225)

![Figur 5.11 – Dollar Rent A Cars web services](Laudon-5-11.png)

*Figur 5.11, s. 225. Eksterne systemer kommunikerer gennem web services med virksomhedens eksisterende reservationssystem. Det illustrerer integration uden at udskifte hele back-end-systemet.*

De stiplede forbindelser ved fremtidige forretningspartnere markerer i figurens kontekst mulige fremtidige tilkoblinger. De skal ikke læses som en generel skala for svagt versus stærkt samarbejde.

**Eget eksempel:** En ordreapplikation kalder en lagertjeneste for at se beholdningen og en leveringstjeneste for at beregne forventet levering. Genbrugelige tjenester kan lette integration; de fjerner ikke behovet for fælles dataforståelse og koordinering.

### Købe, outsource eller abonnere?

Tre eksterne kilder til software er softwarepakker fra leverandører, eksternt udviklings-/vedligeholdelsesarbejde og cloudbaserede tjenester. (s. 225–227)

![Figur 5.12 – eksterne kilder til software](Laudon-5-12.png)

*Figur 5.12, s. 226. Grafen viser historiske udgifter, herunder outsourcing og SaaS. Den viser ikke, at egen udvikling er ophørt, eller at én anskaffelsesform altid er bedst.*

**Outsourcing** betyder at overlade opgaver til en ekstern organisation. **Offshore outsourcing** indebærer, at arbejdet udføres i et andet land. Lavere leverandørpris skal ses sammen med koordinering og andre omkostninger. (s. 226–227)

**SLA – Service Level Agreement:** Aftale om tjenester, ansvar og forventede serviceniveauer. Den kan omfatte måling af ydeevne, support, sikkerhed, genetablering efter nedbrud, opgraderinger, betaling og ophør. Ledelsen skal afklare, hvilken tilgængelighed og svartid virksomheden faktisk behøver. (s. 227, 229)

**Mashup** kombinerer funktioner eller data fra flere kilder til en ny anvendelse. **Apps** er specialiserede programmer, som blandt andet kan give mobil adgang til virksomhedssystemer. En voksende samling apps kan også øge omkostningen ved at skifte platform. (s. 227–228)

## 8. Ledelse: ændringer, governance og investeringer

### Skalering og styring

**Scalability** er systemets evne til at håndtere flere brugere eller større belastning. **Elasticity** fremhæver den hurtige tilpasning op og ned, som cloud kan understøtte. Infrastrukturvalg skal tage højde for vækst, opkøb, nye applikationer og faldende aktivitet. (s. 215, 228)

**MDM – Mobile Device Management** hjælper med at administrere og sikre mobile enheder, fx opdatering, backup og håndtering af mistede enheder. Værktøjet skal understøttes af organisatoriske regler. (s. 228–229)

**IT governance** handler her om beslutningsrettigheder, kontrol og omkostningsfordeling: Hvad bestemmes centralt? Hvad må afdelingerne vælge? Hvem betaler? Kapitlet giver ikke én universelt rigtig grad af centralisering. (s. 229)

### TCO – totalomkostningen

![Tabel 5.4 – omkostninger i TCO](Laudon-Tabel-5-4.png)

*Tabel 5.4, s. 230; forklaring s. 229–230.*

**Total Cost of Ownership** medregner mere end anskaffelsen: installation, uddannelse, support, vedligeholdelse, tilknyttet infrastruktur, nedetid, plads og energi.

**Eget eksempel:** To systemer har samme licenspris, men det ene kræver flere specialintegrationer og mere oplæring. De har derfor ikke nødvendigvis samme TCO. TCO sammenligner omkostninger; forretningsmæssige gevinster skal også vurderes for at afgøre, om investeringen er god.

**Rent versus buy** er valget mellem at anskaffe egne ressourcer og købe adgang til eksterne tjenester. Cloud kan reducere visse omkostninger, men forbrug og abonnementer skal stadig styres. (s. 229)

### Investeringsmodellen: seks forhold at undersøge

![Figur 5.13 – competitive forces model for it-infrastruktur](Laudon-5-13.png)

*Figur 5.13, s. 231; forklaring s. 230–232. Dette er kapitlets model med seks investeringsfaktorer, ikke Porters five forces.*

| Faktor | Spørgsmål til en organisation |
| --- | --- |
| **1. Efterspørgsel efter virksomhedens tjenester** | Hvilke behov har kunder, leverandører og medarbejdere? |
| **2. Forretningsstrategi** | Hvilke kapabiliteter kræver de strategiske mål? |
| **3. Egen it-strategi, infrastruktur og omkostninger** | Hvad har vi, hvad koster det, og passer det til strategien? |
| **4. Vurdering af informationsteknologi** | Er teknologien passende, forældet eller for umoden til vores behov? |
| **5. Konkurrenternes tjenester** | Hvilket serviceniveau skal vi kunne matche eller overgå? |
| **6. Konkurrenternes investeringer** | Hvordan står vores investeringer i forhold til andres – og hvorfor? |

Pilene samler faktorerne om virksomhedens infrastruktur. Den stiplede ring organiserer modellens faktorer; teksten etablerer ikke en regel om, at stiplede linjer betyder mindre samarbejde. Modellen er et beslutningsgrundlag, ikke en formel, der beregner det korrekte budget.

**Vigtig nuance:** Man skal ikke nødvendigvis bruge lige så mange penge som konkurrenterne. Et lavere beløb kan skyldes større effektivitet eller utilstrækkelig investering; det må undersøges. (s. 232)

## 9. Kapitlets cases – hvad skal du lære af dem?

| Case | Hovedproblem og pointe | Sider |
| --- | --- | --- |
| **Grab** | Realtidsdata og cloud understøtter fordeling af chauffører efter efterspørgsel. Infrastruktur bidrager til den konkrete service og forretningsmodel. | 195–196 |
| **Glory** | Opkøb har efterladt forskellige systemer og datacentre. Cloud og fælles systemer kræver integration, procesændringer, uddannelse og en trinvis implementering. | 216–217 |
| **Open Source Innovation** | Baidu og Fujitsu åbner software for at understøtte innovation og deltagelse. Værdi kan komme gennem bidrag og relationer, ikke alene lukket ejerskab. | 222–223 |
| **Project JEDI** | Fragmenterede systemer motiverer fælles cloudinfrastruktur. Valget mellem én og flere leverandører involverer kompleksitet, afhængighed, sikkerhed og organisatoriske interesser. | 238–240 |

Casene gengiver bogens historiske situationer, ikke en opdatering af virksomhederne eller projekterne. JEDI-casen skal især bruges til at diskutere argumenterne og ledelsesproblemerne, ikke som nutidig projektstatus.

**Kildebemærkning:** Den unummererede caseillustration på s. 197 omtaler blandt andet rebooking og IBM Cloud, selv om åbningsteksten handler om Grab og AWS. Den er derfor ikke anvendt som dokumentation for Grabs konkrete systemer i noten.

Karriereafsnittet på s. 232–233 understreger, at en it-konsulent skal kunne forbinde teknologiforståelse med kundebehov, analyse og kommunikation. Kapitlet slutter også med repetitionsspørgsmål og praktiske øvelser på s. 234–237.

## 10. Sammenhæng med de to artikler – egen syntese

| Tekst | Hvad hjælper den med at forstå? |
| --- | --- |
| **Laudon kapitel 5** | Infrastrukturens komponenter, leveringsformer og ledelsesmæssige valg. |
| **Staykova, Mathiassen m.fl. (2019)** | Hvordan aktører, arkitektur og governance ændres sammen i et platformsøkosystem. |
| **Rolland, Mathiassen & Rai (2018)** | Hvordan platformmuligheder og digital gæld påvirker hinanden i en konkret brugerorganisation. |

Laudons ord **platform** bruges bredt om tekniske fundamenter. Det betyder ikke automatisk et flerpartssystem med ejere, brugere og komplementorer som i økosystemartiklen.

**Fælles eksempel:** En cloudplatform tilbyder en ny integration. Laudon hjælper med at beskrive teknologien, driftsformen og TCO. Økosystemartiklen hjælper med at analysere nye aktører og adgangsregler. Rolland et al. hjælper med at vurdere, om integrationen løser gammel gæld eller skaber nye afhængigheder.

Relaterede noter: [[Staykova-et-al-2019-Generative-Mechanisms]] · [[Rolland-et-al-2018-Digital-Options-og-Digital-Debt]]

## 11. Ekstra lingo

| Ord | Betydning på almindeligt dansk |
| --- | --- |
| **Contemporary** | Nutidig eller samtidig; i kapitlet gælder det bogens tidsperiode. |
| **Emerging technology** | Teknologi under fremvækst, hvis anvendelser og betydning stadig udvikler sig. |
| **Provisioning** | At klargøre og stille ressourcer til rådighed. |
| **On-premises** | På organisationens eget driftssted frem for alene hos en ekstern leverandør. |
| **Utility/on-demand computing** | Computing som en tjeneste, der kan tilgås efter behov og fx afregnes efter forbrug. |
| **Consolidation** | Samling af ressourcer eller drift for at reducere spredning og dobbeltarbejde. |
| **Interoperability** | At forskellige systemer kan fungere sammen og udveksle information. |
| **Proprietary** | Leverandørkontrolleret/lukket i den relevante sammenhæng. |
| **Switching costs** | Omkostninger og besvær ved at skifte løsning eller leverandør. |
| **Downtime** | Tid, hvor systemet ikke er tilgængeligt til det nødvendige arbejde. |
| **Benchmarking** | Systematisk sammenligning med andre eller med en reference. |
| **Bleeding edge** | Meget ny teknologi med større umodenhed og risiko. |

*Ordlisten er en dansk læsehjælp til kapitlets terminologi, ikke ordrette definitioner.*

## 12. Tjek din forståelse

1. Forklar figur 5.1 med et eksempel på en forretningskapabilitet.
2. Hvorfor kan gamle og nye infrastrukturepoker eksistere samtidig?
3. Kan du have virtualisering uden cloud? Forklar.
4. Hvad køber kunden med henholdsvis IaaS, PaaS og SaaS?
5. Hvorfor betyder public cloud ikke offentligt tilgængelige kundedata?
6. Hvilket problem kan edge computing løse?
7. Hvordan kan SOA forbinde eksisterende systemer uden at erstatte dem alle?
8. Nævn tre TCO-poster ud over hardware- og softwarekøb.
9. Hvorfor giver konkurrenternes it-budget ikke i sig selv det rigtige budget for os?
10. Brug Glory-casen til at forklare, hvorfor cloudmigration også er organisatorisk forandring.

## Egne noter fra undervisningen

- Underviserens pointer:
- Eksempler:
- Spørgsmål:
- Hvad jeg skal slå op igen:
