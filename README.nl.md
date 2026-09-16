[ 🌐 عربي ](README.ar.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Landed Cost Calculation Benchmark & Supply Chain Reconciliation Excel Toolkit

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-217346.svg)
![Tool Type](https://img.shields.io/badge/Type-Decision%20Support-2251FF.svg)

**<p>Landed Cost Calculator & Reconciliation Template: een professionele benchmarktool voor de praktijk om berekeningen van landed cost in de toeleveringsketen te valideren, uitvoer van Web Service API's van vrachtvervoerders af te stemmen en verschillen in winstgevendheid en kostentoerekening per SKU terug te voeren op hun werkelijke boekhoudkundige logica.</p>**

> **Probeer de gratis webgebaseerde landed-costcalculator. Als u de offline Excel-versie nodig hebt voor uw permanente administratie, auditsporen en herhaald maandelijks gebruik, kunt u deze kopen met een geld-terug-garantie van 30 dagen zonder vragen.**
> 
> [🌐 Probeer de gratis browsercalculator voor landed cost](https://hyvoid.github.io/landed-cost-calculator-excel/)
> 
> [📥 Download het offline Excel-template voor landed cost](https://www.theseusworkshop.com/l/adxwd?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=landed-cost-calculator)


## Veelvoorkomende pijnpunten in de toeleveringsketen en oplossingen voor landed cost

In plaats van alleen cijfers bij te houden, koppelt deze toolkit uw meest frustrerende problemen in de importlogistiek aan gestructureerde analytische oplossingen:

* **Pijnpunt: onduidelijke afwijkingen in 3PL-API's.** 
  **Oplossing: overeenstemming van landed cost op zendingniveau** — stel direct vast of de Web Service van uw expediteur tot hetzelfde totaal van de Cost of Goods Sold (COGS) komt als een onafhankelijke benchmark voor de praktijk.
* **Pijnpunt: verborgen margedaling door importkosten.** 
  **Oplossing: diagnose van variantie per kostencategorie** — bepaal exact waar vracht, douanerechten, havenbehandeling, transportverzekering of andere operationele kostenpools uiteenlopen.
* **Pijnpunt: verstoorde productwinstgevendheid.** 
  **Oplossing: herleiding van landed cost per SKU** — identificeer welke specifieke producten wezenlijk andere kosten voor voorraadwaardering dragen bij verschillende berekeningsmethoden.
* **Pijnpunt: gebrekkige verdeling van logistieke kosten.** 
  **Oplossing: impactanalyse van de toerekeningsbasis** — ontdek of afwijkingen voortkomen uit toerekening op basis van brutogewicht, volume (CBM), commerciële waarde, FOB-douanewaarde of aantallen eenheden.
* **Pijnpunt: onnauwkeurige prijsbeslissingen.** 
  **Oplossing: beoordeling van het effect op unit economics** — visualiseer hoe verschillen in toerekening binnen de toeleveringsketen de landed cost per eenheid en uw totale landed-costmultiplier direct veranderen.
* **Pijnpunt: audit- en compliance-vermoeidheid.** 
  **Oplossing: markering van de ernst van uitzonderingen** — classificeer automatisch of een factuurverschil binnen de boekhoudkundige tolerantie valt, handmatige beoordeling vereist of een kritiek probleem in de ERP-berekening vormt.

## Stapsgewijze tutorial voor het afstemmen van landed cost (quickstartgids)

Volg deze workflow om uw vrachtfacturen te controleren en eenheidskosten efficiënt te valideren:

1. **Stap 1: configureer import- en verzendparameters.**
   Definieer het Case ID, het Shipment ID, de basisvaluta voor rapportage, het boekhoudkundige voorraadbeleid (bijv. ASC 330), de valutawisselkoersen (FX) en de aanvaardbare absolute en procentuele variantiedrempels op het toegewijde blad `00_SETUP_PARAMS`. 

2. **Stap 2: upload commerciële facturen en gegevens van de toeleveringsketen.**
   Plak uw gestructureerde zending- en kostengegevens in de daarvoor bestemde invoerbladen. U kunt commerciële facturen, paklijsten, inkooporders (PO's), douaneaangiften (bijv. CBP Form 7501) en 3PL-vrachtfacturen rechtstreeks vanuit uw ERP-exports samenvoegen.

3. **Stap 3: voer de winstgevendheidsanalyse op SKU-niveau uit.**
   Klik om direct resultaten te krijgen. De benchmark voor de praktijk berekent de landed cost per SKU op basis van uw werkelijke zendinginvoer en kostenpools. De toolkit vergelijkt de resultaten van uw Web Service API automatisch met deze benchmark op het niveau van zending, categorie en SKU.

4. **Stap 4: controleer varianties en voer periodieke verversingen uit.**
   Laad nieuwe testcases zonder de onderliggende berekeningsarchitectuur te breken. Werk uw brongegevens bij, ververs de dashboardvergelijking en besteed alleen tijd aan het beoordelen van de specifieke factuurvarianties die een tolerantiemelding activeren.

5. **Stap 5: standaardiseer uw workflow.**
   👉 **Klaar om zendingen op schaal te controleren?** Begin niet elke keer vanaf nul. [📥 Download het herbruikbare Excel-template voor landed cost](https://www.theseusworkshop.com/l/adxwd?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=landed-cost-calculator) om uw historische afstemmingsgegevens veilig op te slaan, uw maandelijkse vrachtaudits te automatiseren en de kostentoerekeningsmethodiek van uw bedrijf te standaardiseren.

## Waarom ik deze tool voor kostentoerekening heb gebouwd

Een berekening van landed cost kan een getal opleveren dat redelijk lijkt in uw ERP, terwijl toch fundamenteel de verkeerde toerekeningslogica wordt gebruikt.

Dat wordt vooral gevaarlijk voor voorraadwaardering wanneer een geconsolideerde zending veel SKU's en gedeelde logistieke kosten bevat. Zeetransport, havenopslag (demurrage), douane-expeditie, verzekering en rechten vereisen allemaal een verschillende boekhoudkundige behandeling. Een generieke SaaS Web Service levert misschien een schoon resultaat per SKU op, maar een schone interface bewijst niet dat de onderliggende toerekeningsmethode juridisch of financieel passend is.

De fout zit meestal niet in de rekenkunde. Het is **methodologische ondoorzichtigheid**.

Als een dashboard voor de toeleveringsketen meldt dat SKU A een landed cost heeft van $14,82, is de belangrijke vraag niet simpelweg of $14,82 kan worden gereproduceerd. De belangrijke vraag is **waarom dat getal is geproduceerd**.

Deze toolkit creëert een onafhankelijke benchmark voor de praktijk, zodat de twee kostprijsberekeningen kunnen worden vergeleken op basis van exact dezelfde geïmporteerde zending.

Stel bijvoorbeeld dat een gemengde containezending 1.000 eenheden over meerdere SKU's bevat. De geautomatiseerde Web Service verdeelt de vracht op basis van *commerciële waarde*, terwijl de benchmark voor de praktijk exact dezelfde vrachtpool verdeelt op basis van *brutogewicht*. Het zendingtotaal komt perfect overeen, maar de COGS en winstmarges per individuele SKU zullen sterk schommelen.

Vóór het gebruik van dit afstemmingskader:

> "De ERP-cijfers wijken af van de vrachtfactuur."

Na het gebruik van dit afstemmingskader:

> "De totale zendingskosten komen overeen, maar de vrachttoerekening per SKU verschilt omdat de 3PL-API commerciële waarde gebruikt, terwijl ons interne beleid toerekening op brutogewicht voorschrijft."

Dat onderscheid verandert de financiële beoordeling van **handmatig zoeken naar een niet-overeenkomend getal** naar **het identificeren van het specifieke bedrijfsmechanisme dat de margedaling heeft veroorzaakt**.

## Waarom een toegewijde landed-costtool in plaats van eenvoudige spreadsheets?

| Uitdaging bij afstemming in de toeleveringsketen | Traditionele handmatige spreadsheetaanpak | Geautomatiseerde oplossing met het landed-costtemplate |
| :--- | :--- | :--- |
| **Bijhouden van gedeelde 3PL-kostentoerekening** | U vertrouwt op een black-box Web Service om SKU-kosten te produceren; de exacte toerekeningsbasis (gewicht versus waarde) kan niet onafhankelijk worden gecontroleerd. | Een onafhankelijke benchmark voor de praktijk definieert de toerekeningsbasis duidelijk, waardoor uw COGS-berekeningen volledig expliciet en vergelijkbaar worden. |
| **Verkapte fouten in winstgevendheid per SKU** | Een overeenkomend eindtotaal op de vrachtfactuur verbergt wezenlijke margevernietiging op eenheidsniveau. | Factuurafstemming wordt opgesplitst in de niveaus zending, categorie en SKU om totale nauwkeurigheid te garanderen. |
| **Onverklaarde varianties in voorraadwaardering** | Financiële reviewers zien een verschil zonder te weten of het voortkomt uit vrachttoerekening, importbelastingregels, FX-koersen of CIF/FOB-incoterms. | Varianties worden direct geclassificeerd in gestructureerde diagnostische categorieën voor de grondoorzaak, ten behoeve van het boekhoudteam. |
| **Afwijkingen in facturen in vreemde valuta (FX)** | Handmatige dagelijkse omrekeningsaannames introduceren cumulatieve afstemmingsverschillen bij internationale inkooporders. | FX-koersen worden onderhouden in een centrale repository en consistent toegepast op de volledige benchmark van de toeleveringsketen. |
| **Inconsistente toleranties bij vrachtaudits** | Crediteurenmedewerkers gokken handmatig of een factuurverschil "materieel" genoeg is om te onderzoeken. | Configureerbare absolute ($) en procentuele (%) tolerantiedrempels handhaven een gestandaardiseerd beoordelingsbeleid binnen het bedrijf. |
| **Geactiveerde voorraad versus periodieke kosten** | Accountants vermengen per ongeluk geactiveerde voorraadkosten met directe operationele kosten. | Kostenposten vereisen een expliciete tag voor de boekhoudkundige behandeling (bijv. activeren versus ten laste van het resultaat) conform standaardbeleid. |

## Wie heeft deze landed-costsoftware en dit Excel-template nodig?

Deze toolkit is specifiek ontworpen om randgevallen te vangen die generieke calculators missen. Hij is doelgericht gebouwd voor:

* **Operationsmanagers en importeurs in e-commerce:** hebben een *Shopify/Amazon FBA landed-costtemplate* nodig om productmarges te beschermen tegen verborgen expeditiekosten.
* **Controllers in supply chain en logistiek:** hebben een *softwareoplossing voor vrachtaudits* nodig om onnauwkeurige 3PL-facturen en Web Service API-uitvoer aan te vechten.
* **Kostenaccountants en finance analisten:** hebben een *calculator voor importrechten en afstemming in Excel* nodig om te garanderen dat de voorraadwaardering voldoet aan GAAP/ASC 330.
* **Inkoop- en productteams:** hebben een *tool voor unit-economicsmodellering* nodig om de werkelijke inkoopkosten te voorspellen voordat zij internationale inkooporders plaatsen.

Hij is bijzonder nuttig wanneer de onderliggende zee- of luchtvrachtzending meerdere SKU's en gedeelde logistieke kosten bevat, en uw doel is om te bewijzen of een bestaande enterprise-berekening slechts "anders" is of "financieel onjuist."

*(Let op: hoewel krachtig voor analyses en audits, is dit een module voor beslissingsondersteuning en is het **niet** bedoeld om uw productie-ERP, NetSuite-grootboek of enterprise Trade Compliance-systeem volledig te vervangen).*

## Over de maker

Ik bouw lichtgewicht trackers, tools voor vrachtaudits en architecturen voor beslissingsondersteuning voor operaties met te veel bewegende delen om in één hoofd te houden. 

De centrale vraag is eenvoudig: **welke precieze gegevens uit de toeleveringsketen moeten in één dashboard staan om de volgende inkoopbeslissing met vertrouwen te kunnen nemen?**

De Landed Cost Calculation Benchmark & Reconciliation Toolkit is een concrete implementatie van die filosofie. In plaats van nog een generieke vrachtcalculator te bouwen, bundelt hij de professionele redenering die nodig is om complexe landed-costresultaten onafhankelijk te benchmarken, af te stemmen en te auditen.

## Technische details en architectuur

<details>
<summary>Voor technische reviewers, ERP-integratoren en Excel-professionals</summary>

### Gegevensstroom van het systeem en werkmaparchitectuur

De werkmap handhaaft strikt een unidirectionele gegevensstroom om de auditintegriteit te behouden:

```text
Commercial Invoices
3PL Freight Bills
Customs Form 7501
Purchase Orders (POs)
        │
        ▼
┌──────────────────────────┐
│ 00_SETUP_PARAMS          │
│ Global parameters        │
│ FX / tolerance / policy  │
└────────────┬─────────────┘
             │
       ┌─────┴─────┐
       ▼           ▼
┌─────────────┐ ┌─────────────────┐
│ 01_SKU_     │ │ 02_COST_POOL_   │
│ MASTER_INPUT│ │ INPUT           │
│ Shipment/SKU│ │ External costs  │
└──────┬──────┘ └────────┬────────┘
       │                 │
       └────────┬────────┘
                ▼
     ┌──────────────────────┐
     │ 03_PRACTITIONER_CALC │
     │ Independent benchmark│
     └──────────┬───────────┘
                │
        ┌───────┴────────┐
        ▼                ▼
┌────────────────┐ ┌───────────────────┐
│ 04_WEBSERVICE_ │ │ 05_VARIANCE_      │
│ RECON          │ │ DIAGNOSIS         │
│ Multi-level    │ │ Root-cause review │
│ reconciliation │ │                   │
└───────┬────────┘ └─────────┬─────────┘
        │                    │
        └──────────┬─────────┘
                   ▼
        ┌─────────────────────┐
        │ 06_EXECUTIVE_SUMMARY│
        │ Review / audit view │
        └─────────────────────┘

```

| Databaseblad | Laagtype | Analytische rol |
| --- | --- | --- |
| `00_SETUP_PARAMS` | Parameter / aanname | Centrale aansturing van Case ID, Shipment ID, basisvaluta, FX-koersen, GAAP-boekhoudbeleid, woordenboek voor toerekeningsbasis en audittoleranties. |
| `01_SKU_MASTER_INPUT` | Gegevensinvoer | Gestructureerde ingest van zending- en SKU-gegevens uit PO's, commerciële facturen, paklijsten en douanedocumenten. |
| `02_COST_POOL_INPUT` | Gegevensinvoer | Externe kostenpools, waaronder zee-/luchtvracht, rechten, havenbehandeling, transportverzekering, douane-expeditie en diverse uitgaven. |
| `03_PRACTITIONER_CALC` | Benchmarkberekening | Onafhankelijke uitvoering van landed cost volgens de praktijk, met de strikte toerekeningsbasis die aan elke specifieke kostenpost is gekoppeld. |
| `04_WEBSERVICE_RECON` | Afstemming | Directe variantievergelijking van de benchmark voor de praktijk met de Web Service API-uitvoer op het niveau van zending, categorie en SKU. |
| `05_VARIANCE_DIAGNOSIS` | Toewijzing van de grondoorzaak | Gestructureerde controle van materiële afwijkingen en classificatie van hun waarschijnlijke systemische grondoorzaken (bijv. FX-afwijking versus verkeerde gewichtstoerekening). |
| `06_EXECUTIVE_SUMMARY` | Presentatie / rapportage | Geconsolideerd dashboard met matchpercentages op caseniveau, netto financiële variantie, grote margeafwijkingen en diagnostische verdeling. |

De architectuur scheidt bewust **invoer, berekening, afstemming, diagnose en presentatie**. Parameters worden centraal onderhouden in een toegewijd statusblad in plaats van gevaarlijk hardgecodeerd te zijn in stroomafwaartse celformules.

Het geregistreerde schema dekt caseparameters, SKU-kenmerken, metadata van kostenpools en Web Service-payloads. Belangrijke berekende benchmarkuitvoer omvat: totale commerciële waarde, brutogewicht (KG/LBS), volumetrisch gewicht (CBM), douanewaarde, toegerekende vracht, toegerekende rechten, geactiveerde overhead, totale landed cost, landed cost per eenheid en de cruciale landed-costmultiplier.

### Drie veelvoorkomende kostprijsvallen die zelfs ervaren professionals in de toeleveringsketen verrassen

#### Val 1 — een overeenkomend zendingtotaal verbergt een gebrekkige kostentoerekening per SKU

**1. Er werd een beslissing genomen:**
Een 3PL Web Service wordt goedgekeurd omdat de totale landed cost voor de volledige container overeenkomt met het onafhankelijk berekende factuurtotaal van de zending.

**2. De verborgen onjuiste aanname:**
De afstemming werd uitsluitend op het geaggregeerde niveau van de zending uitgevoerd. De gedeelde vracht werd volgens een verschillende methodiek verdeeld tussen de twee systemen, maar het absolute totaal van de vrachtpool bleef gelijk.

**3. De impact op de operatie:**
De totale container lijkt volledig afgestemd, wat interne chaos verbergt:

| Maatstaf | Benchmark voor de praktijk | 3PL Web Service |
| --- | --- | --- |
| Totale vrachtpool | $10.000 | $10.000 |
| Totale landed cost | $60.000 | $60.000 |
| **Landed cost SKU A** | **$18,00/eenheid** | **$16,40/eenheid** |
| **Landed cost SKU B** | **$42,00/eenheid** | **$45,20/eenheid** |

Het macrorapport zegt **MATCH**. De micro-unit economics per SKU (en de daaropvolgende prijsstrategie) zijn volledig verstoord.

**4. De gecorrigeerde afstemmingsaanpak:**
Stem sequentieel af om de integriteit van de marge te behouden:
`Zendingtotaal` → `Kostenpool per categorie` → `Toerekeningslogica per SKU` → `Landed cost per eenheid`

**5. Gecorrigeerde diagnostische uitkomst:**

> **"Het zendingtotaal stemt overeen, maar de vrachttoerekening op SKU-niveau vereist onmiddellijke operationele beoordeling."**
> Het probleem wordt uitsluitend geïsoleerd tot de toerekeningslogica, in plaats van de volledige Web Service-integratie onterecht af te wijzen.

#### Val 2 — een klein dollarbedrag vertegenwoordigt een enorme procentuele variantie

**1. Het gebrekkige beoordelingsproces:**
Een crediteurenmedewerker verwerpt een factuurvariantie omdat het absolute verschil "slechts een paar dollar" is.

**2. Het contextuele falen:**
Een variantie van $3 heeft sterk verschillende gevolgen voor de marge, afhankelijk van de basiskosten per eenheid:

| Basiskosten per eenheid in benchmark | Absolute variantie | Impact van procentuele variantie |
| --- | --- | --- |
| $1.000 | $3 | 0,30% (verwaarloosbaar) |
| $100 | $3 | 3,00% (merkbaar) |
| **$20** | **$3** | **15,00% (kritieke bedreiging van de marge)** |

**3. De geautomatiseerde oplossing:**
Deze tool handhaaft een logica met dubbele drempels, waarbij zowel `TOLERANCE_ABS` als `TOLERANCE_PCT` gelijktijdig moeten slagen voordat de status `MATCH` wordt toegekend.

#### Val 3 — het verschil komt voort uit de "basis", niet uit slechte rekenkunde

**1. De verkeerde diagnose:**
Wanneer een Web Service-resultaat afwijkt van de interne benchmark, gaan reviewers er direct van uit dat er sprake is van een rekenfout of een typefout bij de gegevensinvoer.

**2. De structurele realiteit:**
De berekeningen zijn wiskundig perfect, maar de systemen gebruiken fundamenteel onverenigbare toerekeningsbasissen:

| Toerekeningsbasis van kosten | Afhankelijke SKU-maatstaf |
| --- | --- |
| **Brutogewicht** | Totaal fysiek brutogewicht |
| **Volume (dimgewicht)** | Totaal kubieke meters (CBM) |
| **Commerciële waarde** | Totale waarde van de inkoopfactuur |
| **Douanewaarde** | Totaal aangegeven belastbare waarde |
| **Aantallen eenheden** | Totaal aantal items |

Het toerekenen van een zeevrachtfactuur van $5.000 op basis van **brutogewicht** levert heel andere SKU-COGS op dan het toerekenen van exact dezelfde factuur op basis van **commerciële waarde**.

**3. De diagnostische conclusie:**
In plaats van een vaag *"De API-berekening is onjuist,"* genereert dit template een bruikbaar auditlogboek:

> **"Variantie toe te schrijven aan een mismatch in de toerekeningsbasis: 3PL gebruikte brutogewicht versus intern beleid dat commerciële waarde gebruikt."**

</details>

---

## De bedrijfslogica en methodologie

### Het kernprobleem van de business
De meeste netwerken in de toeleveringsketen en enterprise-ERPsystemen behandelen landed cost als een eenvoudige rekenkundige oefening: het nemen van een geconsolideerde vrachtfactuur en deze verdelen over geïmporteerde eenheden. Landed cost is echter fundamenteel een **strategische beslissing op het gebied van kostenboekhouding**. 

Wanneer API's van third-party logistics (3PL) of black-box SaaS-platforms een uiteindelijke SKU-kostprijs opleveren, verbergen zij de onderliggende toerekeningslogica. Als zware, laagwaardige items een container delen met lichte, hoogwaardige items, dan vervormt een verkeerde toerekeningsbasis (bijv. het verdelen van zeevracht op basis van commerciële waarde in plaats van volume/CBM) uw unit economics ernstig. Deze methodologische ondoorzichtigheid leidt tot te goedkope zware goederen, te dure lichtgewicht goederen en systemische margedaling die traditionele factuuraudits niet kunnen detecteren.

### De methodologie voor de praktijk
Deze toolkit vervangt het model van "black-box-vertrouwen" door een **kader voor Activity-Based Costing (ABC) en afstemming op meerdere niveaus**. 

De methodologie wordt uitgevoerd in drie logische fasen om financiële compliance en nauwkeurige voorraadwaardering te garanderen:

1. **Ontkoppelde mapping van cost drivers (de rule engine):** 
   In plaats van een vlakke procentuele factor op alle goederen toe te passen, verplicht de toolkit dat elke externe kostenpool expliciet wordt gekoppeld aan zijn werkelijke fysieke of financiële driver. 
   * *Zee- en luchtvracht* worden bepaald door ruimteverbruik (volume/CBM of dimgewicht).
   * *Drayage en binnenlands wegtransport* worden bepaald door laadbeperkingen (brutogewicht).
   * *Douanerechten en tarieven* worden bepaald door wettelijke belastingaanslagen (douanewaarde / FOB).
   * *Transportverzekering* wordt bepaald door de blootstelling aan financieel risico (commerciële waarde).
   
2. **Onafhankelijke schaduwberekening (de benchmark):** 
   Voordat de cijfers van een externe API in uw ERP worden geaccepteerd, genereert de werkmap een gelokaliseerde "schaduw"-benchmark. Deze berekent wat de exacte Cost of Goods Sold (COGS) op SKU-niveau *zou moeten* zijn, strikt volgens het aangegeven boekhoudbeleid van uw bedrijf (bijv. GAAP / ASC 330 / IAS 2).

3. **Variantiediagnose op drie niveaus (de audit):**
   Het systeem controleert niet simpelweg of het eindtotaal overeenkomt met de factuur. Het dwingt afstemming af op drie verschillende organisatieniveaus:
   * **Macro (zendingniveau):** komt de totale kasuitstroom overeen met de vrachtfactuur?
   * **Meso (categorieniveau):** heeft de expediteur de rechten versus vracht versus behandeling nauwkeurig beoordeeld, of lekken kosten tussen categorieën?
   * **Micro (SKU-niveau):** werd een specifiek product belast met een onevenredig groot deel van de logistieke kosten, waardoor de brutomarge wordt vernietigd?

### Het strategische resultaat
Door de focus te verschuiven van *rekenkundige verificatie* (komen de cijfers overeen?) naar *methodologische auditing* (is de juiste bedrijfsregel toegepast?), krijgen finance- en operationele teams weer controle over hun gegevens in de toeleveringsketen. Deze logica garandeert dat prijsstrategieën voor consumenten en margeanalyses zijn gebaseerd op de werkelijke economische last van het importeren van een product, in plaats van op een gegeneraliseerd gemiddelde.

---

## Ontdek meer financiële en operationele toolkits

* **Construction & Operations Toolkits** — Excel-gebaseerde controles voor projectkostenbewaking, winstgevendheidsprognoses en operationele workflows op de bouwplaats.
* **Inventory & Reconciliation Toolkits** — praktische modellen voor WMS-voorraadinzicht, afstemming van cyclustellingen en analyse van derving/verlies.
* **Profitability & Costing Toolkits** — geproductiseerde analytische kaders voor job costing in de productie, unit economics in e-commerce en diepgaande margeanalyse.

Ontdek de bredere verzameling templates voor de toeleveringsketen via het GitHub-profiel van het project of de officiële distributiepagina.

## Licentie en gebruik

Deze softwarearchitectuur en dit templateproject zijn vrijgegeven onder de **Apache License 2.0**.

Gebruik, wijzig en herdistribueer deze landed-costtoolkit binnen uw onderneming of persoonlijke projecten in overeenstemming met de standaardvoorwaarden van de Apache License 2.0.
