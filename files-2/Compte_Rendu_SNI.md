<div align="center">

<img src="photo_elbouni.png" width="160" style="border-radius:50%;border:5px solid #006633;box-shadow:0 6px 24px rgba(0,102,51,0.30);display:block;margin:20px auto;" />

**El Bouni Yassine**

*Réalisateur du Projet*

ENCG Settat — Université Hassan 1ᵉʳ | Promotion 2025/2026

---

# COMPTE RENDU

## Analyse de la Base de Données SNI

*Analyse Financière & Risque de Crédit | 2015 – 2019*

</div>

---

| | |
|:---|:---|
| **Institution** | ENCG Settat — Université Hassan 1ᵉʳ |
| **Source** | `Base_de_donnes_-_SNI.xlsx` — Feuille Base Keep |
| **Période** | 2015 – 2019 |
| **Observations** | 1 521 observations \| 482 entreprises \| 40 variables |
| **Date** | 28 mars 2026 |

---

## 1. Présentation Générale de la Base

La base de données SNI couvre **482 entreprises marocaines** réparties sur **17 secteurs d'activité**, pour un total de **1 521 observations** sur cinq exercices consécutifs (2015 à 2019). Chaque observation est caractérisée par **40 variables** combinant des indicateurs financiers quantitatifs, des variables qualitatives de gouvernance, ainsi qu'une variable binaire de **défaut de crédit**.

| **Indicateur** | **Valeur** |
|:---|:---|
| Nombre d'entreprises uniques | 482 |
| Nombre total d'observations | 1 521 |
| Nombre de variables | 40 |
| Période couverte | 2015 – 2019 |
| Taux de défaut global | **3,48 % (53 défauts)** |
| Forme juridique dominante | SA — 71,5 % (1 088 obs.) |
| Appartenance à un groupe | 62,1 % (945 obs.) |
| Cotées en bourse | 3,8 % (58 obs.) |

La répartition annuelle est décroissante : 356 obs. en 2015, 371 en 2016, 336 en 2017, 254 en 2018 et 204 en 2019, reflétant les délais de collecte et certification des états financiers.

---

## 2. Structure du Portefeuille

### 2.1 Répartition sectorielle

Les dix premiers secteurs concentrent la quasi-totalité des observations. Le **Commerce et la réparation automobile** constitue le secteur le plus représenté (497 obs., 149 entreprises), suivi de l'**Agro-alimentaire** (190 obs.) et du **BTP** (172 obs.).

| **#** | **Secteur** | **Nb obs.** | **Nb entrep.** |
|:---:|:---|:---:|:---:|
| 1 | Commerce & réparation automobile | 497 | 149 |
| 2 | Agro-alimentaire et tabac | 190 | 58 |
| 3 | Bâtiments et travaux publics | 172 | 50 |
| 4 | Autres sections | 130 | 43 |
| 5 | Métallurgie / IMEE | 118 | 37 |
| 6 | Chimie et parachimie | 78 | 26 |
| 7 | Transport et communication | 60 | 21 |
| 8 | Promotion immobilière | 56 | 21 |
| 9 | Industries manufacturières diverses | 48 | 17 |
| 10 | Production électricité / gaz / eau | 46 | 16 |

### 2.2 Structure juridique et gouvernance

La **Société Anonyme (SA)** représente 71,5 % des observations (1 088). Plus de **six entreprises sur dix (62,1 %)** appartiennent à un groupe. Seules **3,8 %** des entreprises sont cotées en bourse.

| **SA** | **SARL** | **En groupe** | **Cotées** |
|:---:|:---:|:---:|:---:|
| **71,5 %** | **28,2 %** | **62,1 %** | **3,8 %** |
| 1 088 obs. | 429 obs. | 945 obs. | 58 obs. |

---

## 3. Analyse Financière — Évolution 2015-2019

> **ℹ️ Note :** Toutes les valeurs sont exprimées en médiane (M MAD) afin de limiter l'influence des valeurs extrêmes.

### 3.1 Chiffre d'affaires et rentabilité

| **Année** | **CA méd. (M MAD)** | **RN méd. (M MAD)** | **EBE méd. (M MAD)** | **Marge nette (%)** |
|:---:|---:|---:|---:|:---:|
| 2015 | 357,83 | 5,73 | 19,78 | 1,68 % |
| 2016 | 382,32 | 7,30 | 27,12 | 1,98 % |
| 2017 | 341,08 | 8,68 | 23,90 | 2,00 % |
| 2018 | 369,00 | 7,53 | 22,67 | 1,61 % |
| 2019 | 384,72 | 7,67 | 24,16 | 1,54 % |
| **Var. 15→19** | **+7,5 %** | **+33,9 %** | **+22,1 %** | — |

Le **CA médian** progresse de **+7,5 %** entre 2015 et 2019. Le **résultat net médian** affiche une hausse plus marquée de **+33,9 %**, passant de 5,73 M à 7,67 M MAD — signe d'une amélioration de l'efficacité opérationnelle. La **marge nette médiane** reste faible (1,5 %–2,0 %), caractéristique d'une concurrence forte sur les marchés domestiques.

### 3.2 Structure du bilan

| **Année** | **CP méd. (M MAD)** | **Total Bilan (M MAD)** | **Dette fin. (M MAD)** | **Ratio Dette/CP** |
|:---:|---:|---:|---:|:---:|
| 2015 | 89,40 | 328,90 | 9,21 | 0,082 |
| 2016 | 101,48 | 372,06 | 8,44 | 0,072 |
| 2017 | 98,44 | 369,71 | 7,75 | 0,065 |
| 2018 | 98,94 | 370,93 | 8,73 | 0,080 |
| 2019 | 94,94 | 375,05 | 7,60 | 0,090 |

Le total bilan progresse de **+14 %**. La dette financière médiane reste faible et décroissante, avec un **ratio Dette/CP maintenu sous 0,10** — levier financier très conservateur.

### 3.3 Liquidité et besoin en fonds de roulement

| **Année** | **BFR méd. (M MAD)** | **FDR méd. (M MAD)** | **Trésorerie nette (M MAD)** |
|:---:|---:|---:|:---:|
| 2015 | 156,88 | 99,39 | **-32,20** |
| 2016 | 167,67 | 111,11 | **-33,74** |
| 2017 | 177,19 | 112,16 | **-37,34** |
| 2018 | 179,61 | 111,22 | **-33,25** |
| 2019 | 164,19 | 104,66 | **-46,74** |

> **⚠️ Signal d'alerte :** Le BFR excède systématiquement le FDR, générant une trésorerie nette négative persistante (de -32,2 M à -46,7 M MAD). Dépendance structurelle aux concours bancaires à court terme.

### 3.4 Délais de règlement

| **Année** | **Délai clients méd. (j)** | **Délai fourn. méd. (j)** | **Écart (j)** |
|:---:|:---:|:---:|:---:|
| 2015 | 100,0 | 132,0 | -32,0 |
| 2016 | 104,6 | 130,8 | -26,2 |
| 2017 | 101,9 | 138,2 | -36,3 |
| 2018 | 110,5 | 135,5 | -25,0 |
| 2019 | **113,3** | 132,7 | -19,4 |

Les délais clients s'allongent de 100 à **113 jours** (+13,3 %). Ces niveaux — nettement supérieurs aux standards internationaux de 30–60 jours — témoignent des pratiques de paiement propres au tissu économique marocain.

---

## 4. Analyse du Risque de Crédit

### 4.1 Taux de défaut global et par année

Sur l'ensemble de la période, **53 défauts** ont été enregistrés sur 1 521 observations, soit un **taux de défaut global de 3,48 %**.

| **Année** | **Nb obs.** | **Nb défauts** | **Taux de défaut** | **Tendance** |
|:---:|:---:|:---:|:---:|:---|
| 2015 | 356 | 17 | **4,78 %** | — |
| 2016 | 371 | 4 | **1,08 %** | ↘ Baisse |
| 2017 | 336 | 6 | **1,79 %** | ↗ Légère hausse |
| 2018 | 254 | 11 | **4,33 %** | ↗ Hausse |
| 2019 | 204 | 15 | **7,35 %** | **↑↑ Forte hausse** |

### 4.2 Risque par secteur

| **Secteur** | **Taux de défaut** | **Niveau de risque** |
|:---|:---:|:---:|
| Promotion immobilière | **12,50 %** | **ÉLEVÉ** |
| Autres sections | **6,92 %** | **MODÉRÉ** |
| Métallurgie / IMEE | **6,78 %** | **MODÉRÉ** |
| Bâtiments et travaux publics | **5,81 %** | **MODÉRÉ** |
| Activités financières | **5,00 %** | **MODÉRÉ** |
| Textile, habillement et cuirs | **4,88 %** | **FAIBLE** |
| Production électricité / gaz / eau | **4,35 %** | **FAIBLE** |
| Chimie et parachimie | **2,56 %** | **FAIBLE** |
| Industries manufacturières diverses | **2,08 %** | **FAIBLE** |
| Commerce & automobile | **1,61 %** | **TRÈS FAIBLE** |
| Agro-alimentaire et tabac | **1,58 %** | **TRÈS FAIBLE** |
| Transport et communication | **0,00 %** | **NUL** |

---

## 5. Synthèse par Secteur — Indicateurs Clés

| **Secteur** | **CA (M)** | **RN (M)** | **EBE (M)** | **CP (M)** | **Cli.(j)** | **Fou.(j)** | **Défaut** |
|:---|---:|---:|---:|---:|:---:|:---:|:---:|
| Commerce & Auto | 390,7 | 6,7 | 16,3 | 69,5 | 90 | 93 | 1,6 % |
| Agro-alimentaire | 417,3 | 5,2 | 25,4 | 109,3 | 76 | 112 | 1,6 % |
| BTP | 306,9 | 4,1 | 14,8 | 64,3 | 251 | 187 | **5,8 %** |
| Métallurgie / IMEE | 573,7 | 10,9 | 39,3 | 143,5 | 149 | 150 | **6,8 %** |
| Chimie / Parachimie | 352,1 | 22,5 | 40,9 | 164,3 | 120 | 143 | 2,6 % |
| Transport / Com. | 319,1 | 16,0 | 40,3 | 104,3 | 93 | 254 | **0,0 %** |
| Prom. Immobilière | 385,0 | 9,0 | 35,5 | **541,8** | 234 | **605** | **12,5 %** |
| Ind. Manufacturières | 413,6 | 4,3 | 26,1 | 162,2 | 94 | 117 | 2,1 % |
| Élec. / Gaz / Eau | **688,3** | 25,1 | **73,1** | 94,9 | 81 | 108 | 4,3 % |

**▸ Faits saillants**

- **Promotion Immobilière** : capitaux propres exceptionnels (541,8 M MAD) et délais fournisseurs extrêmes (605 jours) — cycle d'exploitation très long.
- **Électricité / Gaz / Eau** : CA médian le plus élevé (688,3 M MAD) et EBE le plus fort (73,1 M MAD) — nature monopolistique de ces activités.
- **Chimie / Parachimie** : rentabilité nette supérieure (RN 22,5 M MAD) malgré un CA modéré — meilleures marges opérationnelles.
- **BTP** : délais clients les plus longs (251 jours) — risque de liquidité structurel significatif.

---

## 6. Points d'Attention et Recommandations

### 6.1 Alertes identifiées

> **🔴 TRÉSORERIE NÉGATIVE**
> Sur toute la période, la trésorerie nette médiane reste négative avec une dégradation notable en 2019 (-46,7 M MAD). Vulnérabilité systémique aux chocs de liquidité.

> **🟠 ALLONGEMENT DÉLAIS CLIENTS**
> Progression continue des délais clients (100 à 113 jours). Combinée à la hausse du taux de défaut en 2019 (7,35 %), cela suggère une détérioration de la qualité du portefeuille.

> **🟠 CONCENTRATION DU RISQUE**
> Trois secteurs — Promotion Immobilière, Métallurgie/IMEE et BTP — concentrent l'essentiel du risque de défaut.

### 6.2 Recommandations analytiques

| **Axe** | **Recommandation** |
|:---|:---|
| Modélisation du risque | Développer des modèles de scoring (régression logistique, random forest, gradient boosting) en exploitant les 40 variables disponibles. |
| Segmentation sectorielle | Construire des modèles distincts par secteur, notamment pour l'immobilier, le BTP et l'industrie lourde. |
| Déséquilibre des classes | Appliquer des techniques de rééchantillonnage (SMOTE, undersampling) pour traiter les 3,48 % de défauts. |
| Données manquantes | Analyser la réduction des observations en 2018–2019 pour distinguer attrition naturelle et problèmes de collecte. |
| Variables qualitatives | Intégrer les scores de gouvernance (réputation, qualité info financière, compétitivité) dans les modèles prédictifs. |

---

## 7. Conclusion

La base de données SNI constitue un **outil d'analyse financière et de crédit de qualité**, couvrant un panel représentatif du tissu entrepreneurial marocain sur cinq années. Les enseignements principaux sont :

- Rentabilité médiane faible mais en amélioration : **+33,9 %** de résultat net sur la période.
- Financement conservateur : levier financier très limité (ratio Dette/CP < 0,10).
- Tension de liquidité structurelle : trésorerie nette systématiquement négative.
- Risque de défaut hétérogène : particulièrement élevé dans l'immobilier (12,5 %) et le BTP (5,8 %).
- Tendance haussière du défaut en fin de période : **7,35 % en 2019** — vigilance accrue requise.

Ces résultats constituent une base solide pour le développement de **modèles prédictifs de risque de crédit** et pour l'élaboration de politiques d'octroi de financement différenciées par secteur.

---

<div align="center">

<img src="photo_elbouni.png" width="115" style="border-radius:50%;border:4px solid #006633;box-shadow:0 4px 16px rgba(0,102,51,0.22);display:block;margin:16px auto;" />

**El Bouni Yassine**

*Réalisateur du projet*

ENCG Settat — Université Hassan 1ᵉʳ | Promotion 2025/2026

*Document généré le 28 mars 2026*

</div>
