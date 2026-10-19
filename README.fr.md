[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Kit Excel de référence de calcul de landed cost et de réconciliation de la chaîne d'approvisionnement

![Licence](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Plateforme](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-217346.svg)
![Type d'outil](https://img.shields.io/badge/Type-Decision%20Support-2251FF.svg)

**<p>Calculatrice de landed cost et modèle de réconciliation : un outil de référence professionnel pour les praticiens, permettant de valider les calculs de landed cost de la chaîne d'approvisionnement, de réconcilier les sorties des API Web Service des transitaires et de retracer les différences de rentabilité et de répartition des coûts au niveau SKU jusqu'à leur logique comptable réelle.</p>**

> **Essayez la calculatrice de landed cost en ligne gratuite. Si vous avez besoin de la version Excel hors ligne pour vos archives permanentes, vos pistes d'audit et votre utilisation mensuelle répétée, vous pouvez l'acheter avec une garantie de remboursement de 30 jours, sans poser de questions.**
> 
> [🌐 Essayez gratuitement la calculatrice de landed cost dans le navigateur](https://hyvoid.github.io/landed-cost-calculator-excel/)
> 
> [📥 Téléchargez le modèle Excel de landed cost hors ligne](https://www.theseusworkshop.com/l/adxwd?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=landed-cost-calculator)


## Points de douleur courants de la chaîne d'approvisionnement et solutions de landed cost

Plutôt que de simplement suivre des chiffres, cette boîte à outils associe vos problèmes logistiques d'importation les plus frustrants à des solutions analytiques structurées :

* **Point de douleur : écarts d'API 3PL peu clairs.** 
  **Solution : accord de landed cost au niveau de l'expédition** — vérifiez instantanément si le Web Service de votre transitaire atteint le même coût total des marchandises vendues (COGS) qu'un référentiel praticien indépendant.
* **Point de douleur : érosion cachée des marges due aux frais d'importation.** 
  **Solution : diagnostic des écarts par catégorie de coûts** — identifiez précisément où divergent le fret, les droits de douane, la manutention portuaire, l'assurance maritime ou d'autres groupes de coûts opérationnels.
* **Point de douleur : rentabilité des produits déformée.** 
  **Solution : traçabilité du landed cost au niveau SKU** — identifiez quels produits spécifiques supportent des coûts d'évaluation des stocks sensiblement différents selon les méthodes de calcul.
* **Point de douleur : répartition défectueuse des coûts logistiques.** 
  **Solution : analyse d'impact de la base de répartition** — découvrez si les écarts proviennent d'une répartition par poids brut, volume cubique (CBM), valeur commerciale, valeur douanière FOB ou nombre d'unités.
* **Point de douleur : décisions de tarification imprécises.** 
  **Solution : analyse de l'impact sur l'économie unitaire** — visualisez comment les différences de répartition dans la chaîne d'approvisionnement modifient directement le landed cost unitaire et votre multiplicateur global de landed cost.
* **Point de douleur : fatigue d'audit et de conformité.** 
  **Solution : signalement de la gravité des exceptions** — classez automatiquement si un écart de facture se situe dans la tolérance comptable, nécessite un examen manuel ou représente un problème critique de calcul ERP.

## Tutoriel étape par étape de la réconciliation du landed cost (guide de démarrage rapide)

Suivez ce flux de travail pour auditer vos factures de fret et valider efficacement les coûts unitaires :

1. **Étape 1 : configurez les paramètres d'importation et d'expédition.**
   Définissez le Case ID, le Shipment ID, la devise de base du reporting, la politique comptable des stocks (par ex., ASC 330), les taux de change (FX) et les seuils d'écart absolus et en pourcentage acceptables sur la feuille dédiée `00_SETUP_PARAMS`. 

2. **Étape 2 : téléversez les factures commerciales et les données de la chaîne d'approvisionnement.**
   Collez vos données structurées d'expédition et de coûts dans les feuilles de saisie désignées. Vous pouvez consolider les factures commerciales, les listes de colisage, les bons de commande (PO), les formulaires de déclaration en douane (par ex., CBP Form 7501) et les factures de fret 3PL directement à partir de vos exports ERP.

3. **Étape 3 : exécutez l'analyse de rentabilité au niveau SKU.**
   Cliquez pour obtenir des résultats instantanément. Le référentiel praticien calcule le landed cost au niveau SKU à partir de vos données d'expédition réelles et de vos groupes de coûts. La boîte à outils compare automatiquement les résultats de votre API Web Service à ce référentiel aux niveaux de l'expédition, de la catégorie et du SKU.

4. **Étape 4 : auditez les écarts et effectuez les rafraîchissements périodiques.**
   Chargez de nouveaux cas de test sans casser l'architecture de calcul sous-jacente. Mettez à jour vos données sources, rafraîchissez la comparaison du tableau de bord et ne passez du temps à examiner que les écarts de facture spécifiques qui déclenchent une alerte de tolérance.

5. **Étape 5 : standardisez votre flux de travail.**
   👉 **Prêt à auditer des expéditions à grande échelle ?** Ne repartez pas de zéro à chaque fois. [📥 Téléchargez le modèle Excel de landed cost réutilisable](https://www.theseusworkshop.com/l/adxwd?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=landed-cost-calculator) pour enregistrer en toute sécurité vos données de réconciliation historiques, automatiser vos audits de fret mensuels et standardiser la méthodologie de répartition des coûts de votre entreprise.

## Pourquoi j'ai conçu cet outil de répartition des coûts

Un calcul de landed cost peut produire un chiffre qui semble raisonnable dans votre ERP tout en utilisant une logique de répartition fondamentalement erronée.

Cela devient particulièrement dangereux pour l'évaluation des stocks lorsqu'une expédition consolidée contient de nombreux SKU et des coûts logistiques partagés. Le fret maritime, la surestarie portuaire, le courtage en douane, l'assurance et les droits exigent tous des traitements comptables différents. Un Web Service SaaS générique peut renvoyer un résultat propre au niveau SKU, mais une interface soignée ne prouve pas que la méthode de répartition sous-jacente est appropriée sur le plan juridique ou financier.

L'échec n'est généralement pas arithmétique. C'est **l'opacité méthodologique**.

Si un tableau de bord de la chaîne d'approvisionnement indique que le SKU A a un landed cost de 14,82 $, la question importante n'est pas simplement de savoir si 14,82 $ peut être reproduit. La question importante est **pourquoi ce chiffre a été produit**.

Cette boîte à outils crée un référentiel praticien indépendant afin que les deux calculs de coûts puissent être comparés sur exactement la même expédition importée.

Par exemple, supposons qu'une expédition en conteneur mixte compte 1 000 unités réparties sur plusieurs SKU. Le Web Service automatisé répartit le fret selon la *valeur commerciale*, tandis que le référentiel praticien répartit exactement le même groupe de fret selon le *poids brut*. Le total de l'expédition correspond parfaitement, mais le COGS et les marges bénéficiaires de chaque SKU varieront énormément.

Avant d'utiliser ce cadre de réconciliation :

> « Les chiffres de l'ERP sont différents de la facture de fret. »

Après avoir utilisé ce cadre de réconciliation :

> « Le coût total de l'expédition correspond, mais la répartition du fret au niveau SKU diffère car l'API du 3PL utilise la valeur commerciale alors que notre politique interne impose une répartition par poids brut. »

Cette distinction transforme la revue financière, passant de la **recherche manuelle d'un chiffre incohérent** à **l'identification du mécanisme économique spécifique qui a causé l'érosion des marges**.

## Pourquoi utiliser un outil de landed cost dédié plutôt que des tableurs basiques ?

| Défi de réconciliation de la chaîne d'approvisionnement | Approche manuelle traditionnelle par tableur | Solution automatisée du modèle de landed cost |
| :--- | :--- | :--- |
| **Suivi de la répartition des coûts partagés 3PL** | Vous comptez sur un Web Service en boîte noire pour produire les coûts SKU ; la base de répartition exacte (poids ou valeur) est impossible à auditer de manière indépendante. | Un référentiel praticien indépendant définit clairement la base de répartition, rendant vos calculs de COGS entièrement explicites et comparables. |
| **Erreurs de rentabilité au niveau SKU masquées** | Un grand total concordant sur la facture de fret masque une destruction significative des marges au niveau unitaire. | La réconciliation des factures est découplée aux niveaux expédition, catégorie et SKU pour garantir une précision totale. |
| **Écarts d'évaluation des stocks inexpliqués** | Les responsables financiers constatent un écart sans savoir s'il provient de la répartition du fret, des règles fiscales à l'importation, des taux FX ou des incotermes CIF/FOB. | Les écarts sont instantanément classés en catégories diagnostiques structurées de cause racine pour l'équipe comptable. |
| **Écarts de factures en devises étrangères (FX)** | Les hypothèses manuelles de conversion quotidienne introduisent des écarts cumulatifs de réconciliation sur les commandes d'achat internationales. | Les taux FX sont conservés dans une base centrale et appliqués de manière cohérente à l'ensemble du référentiel de la chaîne d'approvisionnement. |
| **Tolérances d'audit de fret incohérentes** | Les commis aux comptes fournisseurs devinent manuellement si un écart de facture est suffisamment « significatif » pour être investigué. | Des seuils de tolérance absolus ($) et en pourcentage (%) configurables appliquent une politique de révision d'entreprise standardisée. |
| **Stocks capitalisés ou charges de période** | Les comptables mélangent accidentellement les coûts de stocks capitalisés avec les charges opérationnelles immédiates. | Les écritures de coûts exigent une étiquette explicite de traitement comptable (par ex., capitaliser ou passer en charge) conforme aux politiques standard. |

## Qui a besoin de ce logiciel de landed cost et de ce modèle Excel ?

Cette boîte à outils est conçue spécifiquement pour capturer les cas limites que les calculatrices génériques ne détectent pas. Elle est construite à dessein pour :

* **Responsables des opérations e-commerce et importateurs :** ont besoin d'un *modèle de landed cost Shopify/Amazon FBA* pour protéger les marges produit des frais de transitaire cachés.
* **Contrôleurs de la chaîne d'approvisionnement et de la logistique :** ont besoin d'une *solution logicielle d'audit de fret* pour contester les factures 3PL inexactes et les sorties des API Web Service.
* **Comptables de gestion et analystes financiers :** ont besoin d'un *calculateur de droits d'importation et de réconciliation Excel* pour garantir que l'évaluation des stocks est conforme à GAAP/ASC 330.
* **Équipes d'approvisionnement et de produit :** ont besoin d'un *outil de modélisation de l'économie unitaire* pour prévoir les coûts réels d'approvisionnement avant d'émettre des commandes d'achat internationales.

Elle est particulièrement utile lorsque l'expédition sous-jacente par fret maritime ou aérien contient plusieurs SKU et des coûts logistiques partagés, et que votre objectif est de prouver si un calcul d'entreprise existant est simplement « différent » ou « financièrement incorrect ».

*(Remarque : bien que puissant pour l'analytique et l'audit, ce module d'aide à la décision n'est **pas** destiné à remplacer entièrement votre ERP de production, votre grand livre comptable NetSuite ou votre système d'entreprise de conformité commerciale).*

## À propos du créateur

Je conçois des outils de suivi légers, des outils d'audit de fret et des architectures d'aide à la décision pour des opérations qui comptent trop d'éléments en mouvement pour tout garder en tête. 

La question centrale est simple : **quelles données précises de la chaîne d'approvisionnement doivent figurer dans un seul tableau de bord pour prendre la prochaine décision d'approvisionnement en toute confiance ?**

La boîte à outils de référence de calcul de landed cost et de réconciliation est une implémentation concrète de cette philosophie. Au lieu de concevoir simplement une autre calculatrice de fret générique, elle intègre le raisonnement professionnel nécessaire pour servir de référentiel indépendant, réconcilier et auditer des résultats complexes de landed cost.

## Détails techniques et architecture

<details>
<summary>Pour les réviseurs techniques, les intégrateurs ERP et les praticiens Excel</summary>

### Flux de données du système et architecture du classeur

Le classeur applique strictement un flux de données unidirectionnel pour préserver l'intégrité de l'audit :

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

| Feuille de base de données | Type de couche | Rôle analytique |
| --- | --- | --- |
| `00_SETUP_PARAMS` | Paramètre / hypothèse | Contrôle central du Case ID, du Shipment ID, de la devise de base, des taux FX, de la politique comptable GAAP, du dictionnaire des bases de répartition et des tolérances d'audit. |
| `01_SKU_MASTER_INPUT` | Saisie de données | Ingestion structurée des données d'expédition et de SKU à partir des PO, des factures commerciales, des listes de colisage et des documents douaniers. |
| `02_COST_POOL_INPUT` | Saisie de données | Groupes de dépenses externes, notamment le fret maritime et aérien, les droits, la manutention portuaire, l'assurance maritime, le courtage en douane et les débours divers. |
| `03_PRACTITIONER_CALC` | Calcul de référence | Exécution indépendante du landed cost selon le référentiel praticien, en utilisant la base de répartition stricte associée à chaque poste de coût spécifique. |
| `04_WEBSERVICE_RECON` | Réconciliation | Comparaison directe des écarts entre le référentiel praticien et la sortie de l'API Web Service aux niveaux de l'expédition, de la catégorie et du SKU. |
| `05_VARIANCE_DIAGNOSIS` | Attribution de la cause racine | Audit structuré des écarts significatifs et classification de leurs causes racines systémiques probables (par ex., dérapage FX ou mauvaise répartition par poids). |
| `06_EXECUTIVE_SUMMARY` | Présentation / reporting | Tableau de bord consolidé affichant les taux de correspondance au niveau du cas, la variance financière nette, les principales déviations de marge et la distribution diagnostique. |

L'architecture sépare délibérément **les entrées, le calcul, la réconciliation, le diagnostic et la présentation**. Les paramètres sont conservés de manière centrale dans une feuille d'état dédiée plutôt que d'être dangereusement codés en dur dans les formules de cellules en aval.

Le schéma enregistré couvre les paramètres de cas, les attributs SKU, les métadonnées des groupes de coûts et les charges utiles des Web Services. Les principaux résultats calculés du référentiel comprennent : la valeur commerciale totale, le poids brut (KG/LBS), le poids volumétrique (CBM), la valeur douanière, le fret alloué, les droits alloués, les frais généraux capitalisés, le landed cost total, le landed cost unitaire et le multiplicateur de landed cost crucial.

### Trois pièges de calcul de coûts courants qui surprennent même les praticiens expérimentés de la chaîne d'approvisionnement

#### Piège 1 — un total d'expédition concordant masque une répartition défectueuse des coûts SKU

**1. Une décision a été prise :**
Un Web Service 3PL est approuvé parce que son landed cost total pour l'ensemble du conteneur correspond au total de la facture d'expédition calculé de manière indépendante.

**2. L'hypothèse erronée cachée :**
La réconciliation a été effectuée exclusivement au niveau agrégé de l'expédition. Le fret partagé a été réparti selon une méthodologie différente entre les deux systèmes, mais le total absolu du groupe de fret est resté inchangé.

**3. L'impact sur les opérations :**
Le conteneur total semble entièrement réconcilié, masquant un chaos interne :

| Métrique | Référentiel praticien | Web Service 3PL |
| --- | --- | --- |
| Groupe de fret total | $10,000 | $10,000 |
| Landed cost total | $60,000 | $60,000 |
| **Landed cost du SKU A** | **$18.00/unit** | **$16.40/unit** |
| **Landed cost du SKU B** | **$42.00/unit** | **$45.20/unit** |

Le résultat macro indique **MATCH**. L'économie unitaire au niveau micro des SKU (et la stratégie de tarification qui en découle) est complètement déformée.

**4. L'approche de réconciliation corrigée :**
Réconciliez séquentiellement pour préserver l'intégrité des marges :
`Total de l'expédition` → `Groupe de coûts par catégorie` → `Logique de répartition SKU` → `Landed cost unitaire`

**5. Résultat diagnostique corrigé :**

> **« Le total de l'expédition se réconcilie, mais la répartition du fret au niveau SKU nécessite une revue opérationnelle immédiate. »**
> Le problème est isolé purement au niveau de la logique de répartition plutôt que de rejeter à tort l'intégralité de l'intégration Web Service.

#### Piège 2 — une petite différence en dollars représente un écart en pourcentage massif

**1. Le processus de révision défectueux :**
Un commis aux comptes fournisseurs rejette un écart de facture parce que la différence absolue n'est que de « quelques dollars ».

**2. Le manque de contexte :**
Un écart de 3 $ a des implications de marge très différentes selon le coût unitaire de base :

| Coût unitaire de référence | Écart absolu | Impact de l'écart en pourcentage |
| --- | --- | --- |
| $1,000 | $3 | 0.30% (négligeable) |
| $100 | $3 | 3.00% (perceptible) |
| **$20** | **$3** | **15.00% (menace critique pour la marge)** |

**3. La solution automatisée :**
Cet outil applique une logique à double seuil exigeant que `TOLERANCE_ABS` et `TOLERANCE_PCT` passent simultanément avant d'accorder un statut `MATCH`.

#### Piège 3 — l'écart provient de la « base », pas d'une mauvaise arithmétique

**1. Le mauvais diagnostic :**
Lorsqu'un résultat de Web Service ne correspond pas au référentiel interne, les réviseurs supposent instantanément une erreur de calcul ou une faute de frappe lors de la saisie des données.

**2. La réalité structurelle :**
Les calculs sont mathématiquement parfaits, mais les systèmes utilisent des bases de répartition fondamentalement incompatibles :

| Base de répartition des coûts | Mesure SKU dépendante |
| --- | --- |
| **Poids brut** | Poids brut physique total |
| **Volume (poids dimensionnel)** | Mètres cubes totaux (CBM) |
| **Valeur commerciale** | Valeur totale de la facture d'achat |
| **Valeur douanière** | Valeur imposable déclarée totale |
| **Nombre d'unités** | Nombre total d'articles |

Répartir une facture de fret maritime de 5 000 $ selon le **poids brut** produit un COGS SKU radicalement différent de la répartition de cette même facture selon la **valeur commerciale**.

**3. La conclusion diagnostique :**
Au lieu d'un vague *« Le calcul de l'API est erroné »*, ce modèle génère un journal d'audit exploitable :

> **« Écart attribué à une inadéquation de base de répartition : le 3PL a utilisé le poids brut alors que la politique interne utilise la valeur commerciale. »**

</details>

---

## La logique métier et la méthodologie

### Le problème métier central
La plupart des réseaux de la chaîne d'approvisionnement et des systèmes ERP d'entreprise traitent le landed cost comme un simple exercice arithmétique — prendre une facture de fret consolidée et la diviser entre les unités importées. Cependant, le landed cost est fondamentalement une **décision stratégique de comptabilité analytique**. 

Lorsque les API de logistique tierce (3PL) ou les plateformes SaaS en boîte noire produisent un coût SKU final, elles masquent la logique de répartition sous-jacente. Si des articles lourds et de faible valeur partagent un conteneur d'expédition avec des articles légers et de grande valeur, l'application d'une mauvaise base de répartition (par ex., répartir le fret maritime selon la valeur commerciale au lieu du volume/CBM) déforme gravement votre économie unitaire. Cette opacité méthodologique conduit à une tarification trop basse des marchandises lourdes, une tarification trop élevée des marchandises légères et une érosion systémique des marges que l'audit traditionnel des factures ne peut pas détecter.

### La méthodologie du praticien
Cette boîte à outils remplace le modèle de « confiance en boîte noire » par un **cadre combinant Activity-Based Costing (ABC) et Multi-Tier Reconciliation**. 

La méthodologie est exécutée en trois phases logiques pour garantir la conformité financière et une évaluation précise des stocks :

1. **Cartographie découplée des facteurs de coûts (le moteur de règles) :** 
   Au lieu d'appliquer un multiplicateur forfaitaire en pourcentage à toutes les marchandises, la boîte à outils exige que chaque groupe de coûts externes soit explicitement associé à son véritable facteur physique ou financier. 
   * *Le fret maritime et aérien* dépend de la consommation d'espace (volume/CBM ou poids dimensionnel).
   * *Le transport d'approche et le camionnage intérieur* dépendent des contraintes de charge utile (poids brut).
   * *Les droits de douane et les tarifs* dépendent des impositions fiscales légales (valeur douanière / FOB).
   * *L'assurance maritime* dépend de l'exposition au risque financier (valeur commerciale).
   
2. **Calcul fantôme indépendant (le référentiel) :** 
   Avant d'accepter les chiffres d'une API externe dans votre ERP, le classeur génère un référentiel « fantôme » localisé. Il calcule ce que le coût exact des marchandises vendues (COGS) au niveau SKU *devrait* être, en adhérant strictement aux politiques comptables déclarées de votre entreprise (par ex., GAAP / ASC 330 / IAS 2).

3. **Diagnostic des écarts à trois niveaux (l'audit) :**
   Le système ne vérifie pas simplement si le grand total correspond à la facture. Il impose une réconciliation à trois niveaux organisationnels distincts :
   * **Macro (niveau expédition) :** le flux de trésorerie agrégé correspond-il à la facture de fret ?
   * **Méso (niveau catégorie) :** le transitaire a-t-il correctement évalué les droits par rapport au fret et à la manutention, ou les coûts débordent-ils d'une catégorie à l'autre ?
   * **Micro (niveau SKU) :** un produit spécifique a-t-il été grevé d'une part disproportionnée du coût logistique, détruisant ainsi sa marge brute ?

### Le résultat stratégique
En déplaçant l'attention de la *vérification arithmétique* (les chiffres correspondent-ils ?) vers l'*audit méthodologique* (la règle métier correcte a-t-elle été appliquée ?), les équipes financières et opérationnelles reprennent le contrôle de leurs données de la chaîne d'approvisionnement. Cette logique garantit que les stratégies de tarification des consommateurs et les analyses de marge reposent sur le véritable fardeau économique de l'importation d'un produit, plutôt que sur une moyenne généralisée.

---

## Découvrez d'autres boîtes à outils financières et opérationnelles

* **Boîtes à outils de construction et d'exploitation** — contrôles fondés sur Excel pour le suivi des coûts de projet, les prévisions de rentabilité et les flux opérationnels de chantier.
* **Boîtes à outils d'inventaire et de réconciliation** — modèles pratiques pour la visibilité des stocks WMS, la réconciliation des comptages cycliques et l'analyse des pertes et des réductions.
* **Boîtes à outils de rentabilité et de calcul des coûts** — cadres analytiques packagés pour le calcul des coûts de production, l'économie unitaire e-commerce et l'analyse approfondie des marges.

Découvrez la collection élargie de modèles de chaîne d'approvisionnement via le profil GitHub du projet ou la page de distribution officielle.

## Licence et utilisation

Ce projet d'architecture logicielle et de modèles est publié sous la **Apache License 2.0**.

Utilisez, modifiez et redistribuez cette boîte à outils de landed cost au sein de votre entreprise ou de vos projets personnels, conformément aux conditions standard de l'Apache License 2.0.

