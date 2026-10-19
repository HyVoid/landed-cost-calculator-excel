[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Excel-Toolkit für Landed-Cost-Benchmark & Supply-Chain-Reconciliation

![Lizenz](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Plattform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-217346.svg)
![Tooltyp](https://img.shields.io/badge/Type-Decision%20Support-2251FF.svg)

**<p>Landed-Cost-Rechner & Reconciliation-Vorlage: Ein professionelles Praktiker-Benchmark-Tool zur Validierung von Supply-Chain-Landed-Cost-Berechnungen, zur Reconciliation von Web-Service-API-Ergebnissen aus der Spedition und zur Zurückverfolgung von Profitabilitäts- und Kostenallokationsunterschieden auf SKU-Ebene auf ihre tatsächliche Buchhaltungslogik.</p>**

> **Testen Sie den kostenlosen webbasierten Landed-Cost-Rechner. Wenn Sie die Offline-Excel-Version für Ihre dauerhaften Aufzeichnungen, Prüfprotokolle und wiederkehrende monatliche Nutzung benötigen, können Sie sie mit einer 30-tägigen Geld-zurück-Garantie ohne Rückfragen kaufen.**
> 
> [🌐 Testen Sie den kostenlosen Landed-Cost-Browser-Rechner](https://hyvoid.github.io/landed-cost-calculator-excel/)
> 
> [📥 Laden Sie die Offline-Landed-Cost-Excel-Vorlage herunter](https://www.theseusworkshop.com/l/adxwd?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=landed-cost-calculator)


## Häufige Supply-Chain-Schmerzpunkte und Landed-Cost-Lösungen

Anstatt einfach nur Zahlen zu verfolgen, ordnet dieses Toolkit Ihre frustrierendsten Importlogistik-Probleme strukturierten analytischen Lösungen zu:

* **Schmerzpunkt: Unklare 3PL-API-Abweichungen.** 
  **Lösung: Reconciliation der Landed Cost auf Sendungsebene** — überprüfen Sie sofort, ob der Web Service Ihres Spediteurs denselben Gesamt-Wareneinsatz (COGS) erreicht wie ein unabhängiges Praktiker-Benchmark.
* **Schmerzpunkt: Versteckter Margenverfall durch Importgebühren.** 
  **Lösung: Diagnose von Abweichungen nach Kostenkategorien** — lokalisieren Sie genau, wo Fracht, Zollabgaben, Hafenabfertigung, Seetransportversicherung oder andere betriebliche Kostenpools auseinandergehen.
* **Schmerzpunkt: Verzerrte Produktprofitabilität.** 
  **Lösung: Nachverfolgung der Landed Cost auf SKU-Ebene** — identifizieren Sie, welche konkreten Produkte bei unterschiedlichen Berechnungsmethoden wesentlich unterschiedliche Bestandsbewertungskosten tragen.
* **Schmerzpunkt: Fehlerhafte Verteilung der Logistikkosten.** 
  **Lösung: Analyse der Auswirkungen der Allokationsbasis** — decken Sie auf, ob Abweichungen von der Allokation nach Bruttogewicht, Kubikvolumen (CBM), Warenwert, FOB-Zollwert oder Mengeneinheiten herrühren.
* **Schmerzpunkt: Ungenaue Preisentscheidungen.** 
  **Lösung: Überprüfung der Auswirkungen auf die Stückkosten** — visualisieren Sie, wie sich Unterschiede in der Supply-Chain-Allokation direkt auf die Stück-Landed-Cost und Ihren gesamten Landed-Cost-Multiplikator auswirken.
* **Schmerzpunkt: Prüfungs- und Compliance-Müdigkeit.** 
  **Lösung: Kennzeichnung der Schwere von Ausnahmen** — klassifizieren Sie automatisch, ob eine Rechnungsabweichung innerhalb der Buchhaltungstoleranz liegt, eine manuelle Prüfung erfordert oder ein kritisches ERP-Berechnungsproblem darstellt.

## Schritt-für-Schritt-Tutorial zur Landed-Cost-Reconciliation (Schnellstartanleitung)

Folgen Sie diesem Workflow, um Ihre Frachtrechnungen zu prüfen und Stückkosten effizient zu validieren:

1. **Schritt 1: Import- und Versandparameter konfigurieren.**
   Legen Sie die Case ID, die Shipment ID, die Basis-Berichtswährung, die Bestandsbuchhaltungsrichtlinie (z. B. ASC 330), die Devisenkurse (FX) und die akzeptablen absoluten/prozentualen Abweichungsschwellen auf dem dedizierten `00_SETUP_PARAMS`-Blatt fest. 

2. **Schritt 2: Handelsrechnungen und Supply-Chain-Daten hochladen.**
   Fügen Sie Ihre strukturierten Sendungs- und Kostendaten in die vorgesehenen Eingabeblätter ein. Sie können Handelsrechnungen, Packlisten, Bestellungen (POs), Zollanmeldungen (z. B. CBP Form 7501) und 3PL-Frachtrechnungen direkt aus Ihren ERP-Exporten konsolidieren.

3. **Schritt 3: Profitabilitätsanalyse auf SKU-Ebene durchführen.**
   Ein Klick liefert sofort Ergebnisse. Das Praktiker-Benchmark berechnet die Landed Cost auf SKU-Ebene basierend auf Ihren tatsächlichen Sendungseingaben und Kostenpools. Das Toolkit vergleicht Ihre Web-Service-API-Ergebnisse automatisch auf Sendungs-, Kategorie- und SKU-Ebene mit diesem Benchmark.

4. **Schritt 4: Abweichungen prüfen und regelmäßige Aktualisierungen pflegen.**
   Laden Sie neue Testfälle, ohne die zugrunde liegende Berechnungsarchitektur zu beeinträchtigen. Aktualisieren Sie Ihre Quelldaten, aktualisieren Sie den Dashboard-Vergleich, und prüfen Sie nur die spezifischen Rechnungsabweichungen, die eine Toleranzwarnung auslösen.

5. **Schritt 5: Ihren Workflow standardisieren.**
   👉 **Bereit, Sendungen in großem Maßstab zu prüfen?** Fangen Sie nicht jedes Mal bei null an. [📥 Laden Sie die wiederverwendbare Landed-Cost-Excel-Vorlage herunter](https://www.theseusworkshop.com/l/adxwd?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=landed-cost-calculator), um Ihre historischen Reconciliation-Daten sicher zu speichern, Ihre monatlichen Frachtrechnungsprüfungen zu automatisieren und die Kostenallokationsmethodik Ihres Unternehmens zu standardisieren.

## Warum ich dieses Kostenallokations-Tool entwickelt habe

Eine Landed-Cost-Berechnung kann eine Zahl erzeugen, die in Ihrem ERP vernünftig aussieht, während sie grundlegend falsche Allokationslogik verwendet.

Das wird besonders gefährlich für die Bestandsbewertung, wenn eine konsolidierte Sendung viele SKUs und gemeinsame Logistikkosten enthält. Seefracht, Hafenliegegeld, Zollabwicklung, Versicherung und Zölle erfordern alle unterschiedliche buchhalterische Behandlungen. Ein generischer SaaS-Web-Service mag ein sauberes SKU-Ergebnis liefern, aber eine saubere Benutzeroberfläche beweist nicht, dass die zugrunde liegende Allokationsmethode rechtlich oder finanziell angemessen ist.

Das Problem liegt meist nicht in der Arithmetik. Es ist die **Intransparenz der Methode**.

Wenn ein Supply-Chain-Dashboard berichtet, dass SKU A eine Landed Cost von $14,82 hat, ist die wichtige Frage nicht einfach, ob $14,82 reproduziert werden kann. Die wichtige Frage ist **warum diese Zahl zustande gekommen ist**.

Dieses Toolkit schafft ein unabhängiges Praktiker-Benchmark, damit die beiden Kostenberechnungen an genau derselben importierten Sendung verglichen werden können.

Nehmen wir zum Beispiel an, eine gemischte Containersendung umfasst 1.000 Einheiten über mehrere SKUs. Der automatisierte Web Service alloziert Fracht nach *Warenwert*, während das Praktiker-Benchmark denselben Frachtpool nach *Bruttogewicht* alloziert. Die Sendungssumme stimmt perfekt überein, doch individuelle SKU-COGS und Gewinnmargen werden stark schwanken.

Vor der Nutzung dieses Reconciliation-Frameworks:

> „Die ERP-Zahlen unterscheiden sich von der Frachtrechnung.“

Nach der Nutzung dieses Reconciliation-Frameworks:

> „Die Gesamtsendungskosten stimmen überein, aber die Frachtallokation auf SKU-Ebene unterscheidet sich, da die 3PL-API Warenwert verwendet, während unsere interne Richtlinie Bruttogewicht-Allokation vorschreibt.“

Diese Unterscheidung verwandelt die Finanzprüfung von der **manuellen Suche nach einer nicht übereinstimmenden Zahl** in die **Identifizierung des spezifischen betriebswirtschaftlichen Mechanismus, der den Margenverfall verursacht hat**.

## Warum ein spezielles Landed-Cost-Tool statt einfacher Tabellenkalkulationen verwenden?

| Supply-Chain-Reconciliation-Herausforderung | Traditioneller manueller Tabellenkalkulations-Ansatz | Automatisierte Landed-Cost-Vorlagen-Lösung |
| :--- | :--- | :--- |
| **Verfolgung der Allokation gemeinsamer 3PL-Kosten** | Sie verlassen sich auf einen Blackbox-Web-Service, um SKU-Kosten zu erzeugen; die genaue Allokationsbasis (Gewicht vs. Wert) kann nicht unabhängig geprüft werden. | Ein unabhängiges Praktiker-Benchmark definiert die Allokationsbasis klar und macht Ihre COGS-Berechnungen vollständig explizit und vergleichbar. |
| **Verdeckte Fehler in der Profitabilität auf SKU-Ebene** | Eine übereinstimmende Gesamtsumme auf der Frachtrechnung verbirgt eine wesentliche Vernichtung der Marge auf Einzelebene. | Die Reconciliation von Rechnungen wird in Sendungs-, Kategorie- und SKU-Ebenen entkoppelt, um vollständige Genauigkeit sicherzustellen. |
| **Unerklärte Abweichungen bei der Bestandsbewertung** | Finanzprüfer sehen eine Lücke, ohne zu wissen, ob sie von Frachtallokation, Importsteuerregeln, FX-Kursen oder CIF/FOB-Incoterms herrührt. | Abweichungen werden sofort in strukturierte diagnostische Ursachenkategorien für das Buchhaltungsteam klassifiziert. |
| **Abweichungen bei Fremdwährungsrechnungen (FX)** | Manuelle tägliche Umrechnungsannahmen führen zu kumulativen Reconciliation-Lücken über internationale Bestellungen hinweg. | FX-Kurse werden in einem zentralen Repository gepflegt und konsistent über das gesamte Supply-Chain-Benchmark angewendet. |
| **Inkonsistente Toleranzen bei der Frachtrechnungsprüfung** | Kreditorenbuchhalter schätzen manuell, ob eine Rechnungsabweichung „wesentlich“ genug ist, um sie zu untersuchen. | Konfigurierbare absolute ($) und prozentuale (%) Toleranzschwellen erzwingen eine standardisierte Prüfungsrichtlinie des Unternehmens. |
| **Aktivierte Bestände vs. Periodenaufwendungen** | Buchhalter vermischen versehentlich aktivierte Bestandskosten mit sofortigen betrieblichen Aufwendungen. | Kosteneinträge erfordern eine explizite Kennzeichnung der buchhalterischen Behandlung (z. B. aktivieren vs. als Aufwand buchen), die mit Standardrichtlinien konform ist. |

## Wer benötigt diese Landed-Cost-Software und Excel-Vorlage?

Dieses Toolkit wurde speziell entwickelt, um Grenzfälle zu erfassen, die generische Rechner übersehen. Es ist zweckbestimmt für:

* **E-Commerce-Operations-Manager und Importeure:** Benötigen eine *Shopify/Amazon-FBA-Landed-Cost-Vorlage*, um Produktmargen vor versteckten Speditionsgebühren zu schützen.
* **Supply-Chain- und Logistik-Controller:** Benötigen eine *Softwarelösung zur Prüfung von Frachtrechnungen*, um ungenaue 3PL-Rechnungen und Web-Service-API-Ergebnisse anzufechten.
* **Kostenbuchhalter und Finanzanalysten:** Benötigen ein *Excel für Importzollberechnung und Reconciliation*, um sicherzustellen, dass die Bestandsbewertung GAAP/ASC 330 entspricht.
* **Beschaffungs- und Produktteams:** Benötigen ein *Tool zur Modellierung der Stückkosten*, um die tatsächlichen Beschaffungskosten vor der Ausstellung internationaler Bestellungen vorherzusagen.

Es ist besonders nützlich, wenn die zugrunde liegende See-/Luftfrachtsendung mehrere SKUs und gemeinsame Logistikkosten enthält und Ihr Ziel es ist, nachzuweisen, ob eine bestehende Unternehmensberechnung lediglich „anders“ oder „finanziell falsch“ ist.

*(Hinweis: Obwohl leistungsstark für Analysen und Prüfungen, ist dies ein Entscheidungsunterstützungsmodul und ist **nicht** dazu bestimmt, Ihr Produktions-ERP, Ihr NetSuite-Hauptbuch oder das Handelscompliance-System Ihres Unternehmens vollständig zu ersetzen).*

## Über den Entwickler

Ich entwickle schlanke Tracker, Tools zur Prüfung von Frachtrechnungen und Architekturen zur Entscheidungsunterstützung für Betriebe, die zu viele bewegliche Teile haben, um sie im Kopf zu behalten. 

Die zentrale Frage ist einfach: **Welche präzisen Supply-Chain-Daten müssen in einem Dashboard zusammenkommen, um die nächste Beschaffungsentscheidung sicher zu treffen?**

Das Toolkit für Landed-Cost-Benchmark und Supply-Chain-Reconciliation ist eine konkrete Umsetzung dieser Philosophie. Anstatt nur einen weiteren generischen Frachtrechner zu entwickeln, bündelt es die professionelle Argumentation, die erforderlich ist, um komplexe Landed-Cost-Ergebnisse unabhängig zu benchmarken, abzustimmen und zu prüfen.

## Technische Details und Architektur

<details>
<summary>Für technische Prüfer, ERP-Integratoren und Excel-Praktiker</summary>

### Systemdatenfluss und Arbeitsmappen-Architektur

Die Arbeitsmappe erzwingt strikt einen einseitig gerichteten Datenfluss, um die Integrität der Prüfung zu wahren:

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

| Tabellenblatt | Ebenentyp | Analytische Rolle |
| --- | --- | --- |
| `00_SETUP_PARAMS` | Parameter / Annahme | Zentrale Steuerung für Case ID, Shipment ID, Basiswährung, FX-Kurse, GAAP-Buchhaltungsrichtlinie, Wörterbuch der Allokationsbasen und Prüftoleranzen. |
| `01_SKU_MASTER_INPUT` | Dateneingabe | Strukturierte Aufnahme von Sendungs- und SKU-Daten aus POs, Handelsrechnungen, Packlisten und Zolldokumenten. |
| `02_COST_POOL_INPUT` | Dateneingabe | Externe Kostenpools einschließlich See-/Luftfracht, Zoll, Hafenabfertigung, Seetransportversicherung, Zollabwicklung und sonstigen Auslagen. |
| `03_PRACTITIONER_CALC` | Benchmark-Berechnung | Unabhängige Ausführung der Praktiker-Landed-Cost unter Verwendung der strengen Allokationsbasis, die jedem spezifischen Kostenposten zugeordnet ist. |
| `04_WEBSERVICE_RECON` | Reconciliation | Direkter Abweichungsvergleich des Praktiker-Benchmarks gegen das Web-Service-API-Ergebnis auf Sendungs-, Kategorie- und SKU-Ebene. |
| `05_VARIANCE_DIAGNOSIS` | Ursachenzuordnung | Strukturierte Prüfung wesentlicher Abweichungen und Klassifizierung ihrer wahrscheinlichen systemischen Ursachen (z. B. FX-Kursfehler vs. Gewichtsfehlallokation). |
| `06_EXECUTIVE_SUMMARY` | Präsentation / Berichtswesen | Konsolidiertes Dashboard, das Übereinstimmungsraten auf Fallebene, nettofinanzielle Abweichungen, wesentliche Marginabweichungen und die Verteilung der Diagnosen anzeigt. |

Die Architektur trennt bewusst **Eingaben, Berechnung, Reconciliation, Diagnose und Präsentation**. Parameter werden zentral in einem dedizierten Zustandsblatt gepflegt, anstatt sie gefährlich hartcodiert in nachgelagerte Zellformeln zu schreiben.

Das registrierte Schema umfasst Fallparameter, SKU-Attribute, Kostenpool-Metadaten und Web-Service-Nutzdaten. Wichtige berechnete Benchmark-Ergebnisse umfassen: Gesamtwarenwert, Bruttogewicht (KG/LBS), Volumengewicht (CBM), Zollwert, zugewiesene Fracht, zugewiesene Zollabgaben, kapitalisierte Gemeinkosten, Gesamt-Landed-Cost, Stück-Landed-Cost und den entscheidenden Landed-Cost-Multiplikator.

### Drei häufige Kostenfallen, in die selbst erfahrene Supply-Chain-Praktiker tappen

#### Falle 1 — Eine übereinstimmende Sendungssumme verbirgt fehlerhafte SKU-Kostenallokation

**1. Eine Entscheidung wurde getroffen:**
Ein 3PL-Web-Service wird freigegeben, weil seine Gesamt-Landed-Cost für den gesamten Container mit der unabhängig berechneten Gesamtsumme der Sendungsrechnung übereinstimmt.

**2. Die verborgene fehlerhafte Annahme:**
Die Reconciliation wurde ausschließlich auf aggregierter Sendungsebene durchgeführt. Gemeinsame Fracht wurde zwischen den beiden Systemen über eine unterschiedliche Methodik alloziert, aber die absolute Gesamtsumme des Frachtpools blieb konstant.

**3. Die Auswirkungen auf den Betrieb:**
Der Gesamtcontainer erscheint vollständig abgestimmt, was internes Chaos verbirgt:

| Kennzahl | Praktiker-Benchmark | 3PL-Web-Service |
| --- | --- | --- |
| Frachtpool gesamt | $10,000 | $10,000 |
| Landed Cost gesamt | $60,000 | $60,000 |
| **Stück-Landed-Cost – SKU A** | **$18.00/unit** | **$16.40/unit** |
| **Stück-Landed-Cost – SKU B** | **$42.00/unit** | **$45.20/unit** |

Das Makroergebnis lautet **MATCH**. Die Stückkosten auf Mikroebene (SKU-Ebene) (und die daraus resultierende Preisstrategie) sind vollständig verzerrt.

**4. Der korrigierte Reconciliation-Ansatz:**
Führen Sie die Reconciliation sequenziell durch, um die Marginintegrität zu wahren:
`Sendungssumme` → `Kategoriekostenpool` → `SKU-Allokationslogik` → `Stück-Landed-Cost`

**5. Korrigiertes Diagnoseergebnis:**

> **„Die Sendungssumme stimmt überein, aber die Frachtallokation auf SKU-Ebene erfordert eine sofortige betriebliche Prüfung.“**
> Das Problem ist rein auf die Allokationslogik isoliert, anstatt die gesamte Web-Service-Integration fälschlich abzulehnen.

#### Falle 2 — Eine kleine Dollar-Differenz stellt eine massive prozentuale Abweichung dar

**1. Der fehlerhafte Prüfungsprozess:**
Ein Kreditorenbuchhalter weist eine Rechnungsabweichung als unbedeutend ab, weil die absolute Differenz „nur ein paar Dollar“ beträgt.

**2. Das Kontextversagen:**
Eine Abweichung von $3 hat je nach Basisstückkosten enorm unterschiedliche Auswirkungen auf die Marge:

| Benchmark-Stückkosten | Absolute Abweichung | Prozentuale Abweichungsauswirkung |
| --- | --- | --- |
| $1,000 | $3 | 0.30% (unerheblich) |
| $100 | $3 | 3.00% (merklich) |
| **$20** | **$3** | **15.00% (kritische Marginbedrohung)** |

**3. Die automatisierte Lösung:**
Dieses Tool erzwingt eine Logik mit zwei Schwellenwerten, die verlangt, dass sowohl `TOLERANCE_ABS` als auch `TOLERANCE_PCT` gleichzeitig erfüllt sind, bevor ein `MATCH`-Status vergeben wird.

#### Falle 3 — Die Abweichung rührt von der „Basis“, nicht von fehlerhafter Arithmetik

**1. Die Fehldiagnose:**
Wenn ein Web-Service-Ergebnis nicht mit dem internen Benchmark übereinstimmt, nehmen Prüfer sofort einen Rechenfehler oder einen Tippfehler bei der Dateneingabe an.

**2. Die strukturelle Realität:**
Die Berechnungen sind mathematisch perfekt, aber die Systeme verwenden grundlegend inkompatible Allokationsbasen:

| Kostenallokationsbasis | Abhängige SKU-Kennzahl |
| --- | --- |
| **Bruttogewicht** | Gesamtes physisches Bruttogewicht |
| **Volumen (Volumengewicht)** | Gesamte Kubikmeter (CBM) |
| **Warenwert** | Gesamtwert der Einkaufsrechnung |
| **Zollwert** | Gesamter deklarierter zollpflichtiger Wert |
| **Mengeneinheiten** | Gesamtanzahl der Artikel |

Die Allokation einer Seefrachtrechnung über $5.000 nach **Bruttogewicht** liefert drastisch andere SKU-COGS als die Allokation derselben Rechnung nach **Warenwert**.

**3. Die diagnostische Schlussfolgerung:**
Anstelle einer vagen *„Die API-Berechnung ist falsch“,* generiert diese Vorlage ein handlungsrelevantes Prüfprotokoll:

> **„Die Abweichung ist auf eine abweichende Allokationsbasis zurückzuführen: 3PL nutzt Bruttogewicht, während die interne Richtlinie Warenwert nutzt.“**

</details>

---

## Die Geschäftslogik und Methodik

### Das zentrale betriebswirtschaftliche Problem
Die meisten Supply-Chain-Netzwerke und Unternehmens-ERP-Systeme behandeln Landed Cost als einfache arithmetische Übung — eine konsolidierte Frachtrechnung nehmen und auf die importierten Einheiten verteilen. Landed Cost ist jedoch grundlegend eine **strategische Entscheidung der Kostenrechnung**. 

Wenn APIs von Logistikdienstleistern (3PL) oder Blackbox-SaaS-Plattformen eine endgültige SKU-Kosten ausgeben, verschleiern sie die zugrunde liegende Allokationslogik. Wenn schwere, geringwertige Artikel einen Transportcontainer mit leichten, hochwertigen Artikeln teilen, verzerrt die Anwendung der falschen Allokationsbasis (z. B. Verteilung von Seefracht nach Warenwert statt nach Volumen/CBM) Ihre Stückkosten massiv. Diese Intransparenz der Methode führt zu zu günstig kalkulierten schweren Gütern, zu teuer kalkulierten leichten Gütern und systemischem Margenverfall, den traditionelle Rechnungsprüfungen nicht erkennen können.

### Die Praktiker-Methodik
Dieses Toolkit ersetzt das „Blackbox-Vertrauen“-Modell durch ein **Activity-Based Costing (ABC) und Multi-Tier Reconciliation Framework**. 

Die Methodik wird in drei logischen Phasen umgesetzt, um finanzielle Compliance und eine genaue Bestandsbewertung sicherzustellen:

1. **Zuordnung entkoppelter Kostentreiber (Das Regelwerk):** 
   Anstatt einen pauschalen prozentualen Multiplikator auf alle Güter anzuwenden, schreibt das Toolkit vor, dass jeder externe Kostenpool explizit seinem tatsächlichen physischen oder finanziellen Treiber zugeordnet wird. 
   * *See- und Luftfracht* werden durch räumliche Inanspruchnahme bestimmt (Volumen/CBM oder Volumengewicht).
   * *Vor- und Nachlauf sowie Inland-Lkw-Transport* werden durch Nutzlastbeschränkungen bestimmt (Bruttogewicht).
   * *Zölle und Abgaben* werden durch gesetzliche Steuerfestsetzungen bestimmt (Zollwert / FOB).
   * *Seetransportversicherung* wird durch finanzielle Risikoexposition bestimmt (Warenwert).
   
2. **Unabhängige Schattenberechnung (Das Benchmark):** 
   Bevor die Zahlen eines externen API in Ihr ERP übernommen werden, generiert die Arbeitsmappe ein lokalisiertes „Schatten“-Benchmark. Es berechnet, was der exakte Wareneinsatz (COGS) auf SKU-Ebene *sein sollte*, strikt unter Einhaltung der deklarierten Buchhaltungsrichtlinien Ihres Unternehmens (z. B. GAAP / ASC 330 / IAS 2).

3. **Dreistufige Abweichungsdiagnose (Die Prüfung):**
   Das System prüft nicht einfach, ob die Gesamtsumme mit der Rechnung übereinstimmt. Es erzwingt eine Reconciliation auf drei unterschiedlichen Organisationsebenen:
   * **Makro (Sendungsebene):** Stimmt der aggregierte Geldabfluss mit der Frachtrechnung überein?
   * **Meso (Kategorieebene):** Hat der Spediteur Zoll vs. Fracht vs. Abfertigung korrekt bewertet, oder werden Kosten über Kategorien hinweg vermischt?
   * **Mikro (SKU-Ebene):** Wurde ein bestimmtes Produkt mit einem unverhältnismäßigen Anteil der Logistikkosten belastet und dadurch seine Bruttomarge zerstört?

### Das strategische Ergebnis
Durch die Verlagerung des Fokus von der *arithmetischen Verifizierung* (stimmen die Zahlen überein?) auf die *methodische Prüfung* (wurde die richtige Geschäftsregel angewendet?), gewinnen Finanz- und Betriebsteams die Kontrolle über ihre Supply-Chain-Daten zurück. Diese Logik stellt sicher, dass Preisstrategien für Endverbraucher und Marginanalysen auf der tatsächlichen wirtschaftlichen Belastung des Imports eines Produkts basieren anstatt auf einem verallgemeinerten Durchschnitt.

---

## Entdecken Sie weitere Finanz- und Operations-Toolkits

* **Bau- und Operations-Toolkits** — Excel-basierte Kontrollen für Projektkostenverfolgung, Profitabilitätsprognose und betriebliche Abläufe auf der Baustelle.
* **Bestands- und Reconciliation-Toolkits** — Praxistaugliche Modelle für WMS-Bestandstransparenz, Reconciliation von Zykluszählungen und Schwund-/Verlustanalyse.
* **Profitabilitäts- und Kostenrechnungs-Toolkits** — Produktisierte analytische Frameworks für Auftragskostenrechnung in der Fertigung, E-Commerce-Stückkosten und tiefgehende Marginanalyse.

Entdecken Sie die breitere Sammlung von Supply-Chain-Vorlagen über das GitHub-Profil des Projekts oder die offizielle Vertriebsseite.

## Lizenz und Nutzung

Dieses Softwarearchitektur- und Vorlagenprojekt wird unter der **Apache License 2.0** veröffentlicht.

Nutzen, modifizieren und verbreiten Sie dieses Landed-Cost-Toolkit in Ihren Unternehmens- oder persönlichen Projekten gemäß den Standardbedingungen der Apache License 2.0.

