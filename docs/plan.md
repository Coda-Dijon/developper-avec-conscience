# Développer avec conscience : éthique, open source et impact

**Durée : 6h** · Format : 4C (Connexions, Concepts, Pratique concrète, Conclusions)

## Objectifs pédagogiques

1. Expliquer les valeurs fondatrices de l'open source et identifier les enjeux liés aux licences, au partage de code, à la collaboration ouverte
2. Analyser différentes chartes éthiques du métier (Software Craftsmanship, Ethical Source, Egoless Programming) et discuter de leur application en contexte professionnel
3. Évaluer l'impact éthique, social, environnemental de ses choix de développement (performance, accessibilité, dette technique, biais algorithmiques)
4. Adopter une posture de développeur responsable en étant capable de justifier des choix techniques durables, réfléchis, alignés avec ses valeurs

## Sources

| Source | Apport principal |
|---|---|
| `cours coda ethique 012026.pdf` | Socle : couvre les 4 objectifs, avec des exercices prêts à l'emploi |
| `Developers ethics.pptx` | Accroche (VW, Boeing 737 Max, Cambridge Analytica), serment d'Hippocrate, Milgram, atelier « créer son serment », code ACM |
| `The Software Craftsman.pdf` | Carte mentale Mancuso : manifeste 2008, motivation, pratiques XP, culture du partage |
| `intro-numerique-responsable.pptx` | Chiffres et quiz sur l'impact, ACV, 5 axes NR, réglementation, CoRSeN |
| `Artefact-Tarot-Cards-of-Tech_downloadable_FR.pdf` | 12 cartes d'anticipation des impacts pour l'atelier d'évaluation |

## Principes de conception

- **Fil rouge « charte »** : chaque séquence produit 1 à 2 engagements, qui sont fusionnés en séquence 5.
- **Fil rouge « INR »** 🌱 : un encart numérique responsable revient dans chaque séquence, en plus d'une séquence dédiée.

## Déroulé

| # | Séquence | Durée | Objectif |
|---|---|---|---|
| 0 | Ouverture | 20 min | |
| 1 | Open source et licences | 55 min | Objectif 1 |
| 2 | Chartes éthiques | 55 min | Objectif 2 |
| | *Pause* | 10 min | |
| 3 | **Numérique responsable** | **1h15** | Objectif 3 |
| 4 | Impacts humains du code + Tarot de la Tech | 1h05 | Objectif 3 |
| | *Pause* | 10 min | |
| 5 | Posture et charte | 40 min | Objectif 4 |
| 6 | Clôture et évaluation | 10 min | |
| | **Total** | **6h** | |

---

## 0. Ouverture (20 min)

- **Breaking News** (8 min, *Developers ethics* slide 3) : chaque groupe écrit la une qui annonce le succès spectaculaire de son produit. On la conserve pour la retourner en séquence 5.
- **« Le code n'est jamais neutre »** : exercice `if (age >= 18)` en PHP/JS (*coda* p. 33-42). Quels choix implicites ? Qui est exclu ?
- Les 4 dimensions d'impact (*coda*) : environnement, social, éthique, professionnel.
- 🌱 **Fil INR** : « Chaque ligne de code est un choix technique, mais aussi environnemental. »

## 1. Open source et licences (55 min), objectif 1

- **Connexion** : « Vrai ou faux ? Open source = gratuit. »
- **Concepts** (20 min) :
  - open source ≠ gratuit (*coda* p. 45-48) ;
  - les 4 valeurs fondatrices : transparence, intelligence collective, autonomie/résilience, transmission/bien commun (*coda* p. 49-57) ;
  - licences permissives (MIT, BSD, Apache 2.0) vs copyleft (GPL, AGPL) : « Faites ce que vous voulez » vs « Faites, mais partagez » ;
  - rappel historique FSF (4 libertés) / OSI ;
  - contribuer ne se limite pas à coder : documentation, traduction, tests.
- **Pratique concrète** (25 min) :
  1. Chasse aux licences sur GitHub (*coda* p. 83-84) : identifier, classer, puis-je vendre ? Ce choix est-il éthique ?
  2. Dilemme : « Une grande entreprise utilise votre librairie PHP sans contribuer. MIT ou GPL ? Qui protège qui ? » (*coda* p. 93-95)
- 🌱 **Fil INR** (5 min) :
  - mutualiser plutôt que reproduire (*coda* p. 57) ;
  - l'open source comme levier de **résilience** (axe 4 du NR) ;
  - le lien avec le **réemploi** (le « R » de Réutiliser dans les 5R).
- **Conclusion** : 1 engagement open source pour la charte.

## 2. Chartes éthiques du métier (55 min), objectif 2

- **Connexion** (5 min) : « Les médecins ont un serment. Et nous ? » Expérience de Milgram ; la plupart des devs ne se sentent pas responsables d'un produit non éthique (*Developers ethics* slides 5-15).
- **Concepts en jigsaw, 3 groupes d'experts** (25 min) :
  - **Software Craftsmanship** : les 4 valeurs du manifeste 2008, règle du boy scout, savoir dire NON pour le bien du client, motivation intrinsèque (*Software Craftsman* + *coda* p. 106-111) ;
  - **Egoless Programming** : « le code n'est pas vous », la revue de code comme opportunité (*coda* p. 113-121) ;
  - **Ethical Source** : suis-je responsable de l'usage de mon code ? Licences restrictives d'usage, débat pour/contre (*coda* p. 123-128).
- **Pratique concrète** (15 min) :
  - réponse égocentrée vs egoless à la revue « Cette fonction est trop longue » ;
  - tableau comparatif : Craftsmanship = qualité/technique, Egoless = humain/relationnel, Ethical Source = usage/sociétal.
- 🌱 **Fil INR** (5 min) :
  - « La qualité du code est un acte écologique » : un code mal conçu entraîne des refontes, puis l'obsolescence logicielle, puis le renouvellement matériel (*coda* p. 108-110) ;
  - la « Sustainable Pace » de XP reliée à la durabilité.
- **Conclusion** : 1 engagement pour la charte.
- *Ressources à lire (hors séance)* : code ACM, Programmer's Oath (Uncle Bob), principes IA de Google.

## 3. Numérique responsable (1h15), objectif 3 ⭐

Séquence bâtie sur `intro-numerique-responsable.pptx`, complétée par le deck *coda*.

### Connexion (15 min) : quiz INR avec votes

- Empreinte de la France : 2,7 planètes
- 8 400 ordinateurs vendus par jour en France
- Le numérique représente environ 10 % de l'électricité mondiale
- Environ 200 kg de matières pour fabriquer un smartphone
- 1/4 de la consommation électrique évitable par de simples bons gestes
- Ouverture sur la paréidolie : notre cerveau nous trompe sur ces ordres de grandeur.

### Concepts (25 min)

1. **État des lieux**
   - GIEC, rapport Brundtland (1987), 17 ODD ;
   - le numérique pèse 3,8 % des GES (plus que l'aviation civile), environ 10 % de l'électricité, 0,2 % de l'eau ;
   - ⚠️ chiffres à actualiser avec l'étude GreenIT 2025.
2. **Analyse du Cycle de Vie (ACV)**
   - la fabrication est la phase la plus impactante : 1 PC = 1 500 L d'eau, 22 kg de produits chimiques, 164 kg de déchets ;
   - un smartphone contient plus de 70 matières premières, moins de 10 % sont recyclés ;
   - **lien avec le dev** : un logiciel lourd rend le matériel obsolète plus vite. Le logiciel pilote le renouvellement du matériel.
3. **Cadre du NR**
   - définition et 5 axes stratégiques ;
   - Green for IT / IT for Green / Human for IT / IT for Human ;
   - règle des 5R : Refuser, Réduire, Réutiliser, Recycler, Réparer ;
   - 3 leviers de changement : économique, sociétal, politique (Bâle, Ecodesign, RoHS, Batteries) ;
   - référentiels : RGESN, CoRSeN / ISO 14062, ADEME, loi REEN.

### Pratique concrète (15 min)

- **Audit éclair** (15 min) : par binôme, analyser un site réel avec EcoIndex, GreenIT-Analysis ou Lighthouse. Relier à l'exemple « 12 secondes de recherche produit » de l'INR, puis choisir 3 critères RGESN applicables.

### Conclusion (5 min)

- La sobriété, c'est satisfaire le besoin avec le minimum de ressources. Elle se décide dès la conception et n'est pas une contrainte tardive.
- 1 engagement NR pour la charte.

## 4. Impacts humains du code et Tarot de la Tech (1h05), objectif 3

- **3 stations tournantes de 10 min** :
  1. **Accessibilité** : `<img>` sans `alt` (*coda*), levier sociétal de l'INR (inclusion, fracture numérique), RGAA.
  2. **Dette technique vue comme une dette morale** : transfert de charge vers les collègues, l'entreprise et la planète. Dette consciente, documentée, remboursée.
  3. **Biais algorithmiques** : `if ($score > 70)`. Pourquoi 70 ? Qui a décidé ? Peut-on expliquer la décision ?
- **Étude de cas avec le Tarot de la Tech** (30 min) : une entreprise veut ajouter autoplay vidéo, tracking détaillé, animations complexes et IA de recommandation (*coda*).
  - Chaque groupe tire *Mère Nature* (imposée), puis 2 cartes parmi *Les Oublié·es*, *La Sirène*, *Le Grand Méchant Loup*, *Le Gros Succès*.
  - Il produit une matrice des impacts (environnement / social / éthique) avec des alternatives responsables.
- **Conclusion** (5 min) : la grille d'évaluation en 7 questions : utile ? pour qui ? qui est exclu ? maintenable ? accessible ? quel impact environnemental ? peut-on faire plus simple ?
- 🌱 **Fil INR** : accessibilité = inclusion, simplicité = moins de données, sobriété = durabilité.

## 5. Posture et charte (40 min), objectif 4

- **Connexion** : retourner la Breaking News du matin avec la carte *Le Scandale* : quel serait le pire titre possible ?
- **Concept court** :
  - le développeur comme décideur indirect ; 3 leviers : alerter, refuser, proposer une alternative ;
  - « Ne pas choisir, c'est déjà choisir » ;
  - 🌱 citation d'Edward Everett (« Je ne peux pas tout faire, mais je peux faire quelque chose ») et gestes du quotidien : allonger la durée de vie du matériel, limiter cloud et 4G.
- **Pratique : « Créer notre serment »** (*Developers ethics* slide 19) : 5 min en binôme, 5 en groupe, 5 de mise en commun, 5 de finalisation.
  - Fusion des engagements accumulés : 5 à 8 engagements, dont **au moins 2 liés au NR**.
  - Pour chacun : pourquoi il compte et comment il s'applique concrètement.

## 6. Clôture et évaluation (10 min)

- Quiz vrai/faux éclair (*coda*, validation des acquis), avec en plus « Le numérique est immatériel ? ».
- **Évaluation sommative (en différé)** : atelier en 4 parties (*coda*) à rendre avec la charte :
  1. Contexte : type de service, public cible, objectif fonctionnel
  2. Analyse éthique et environnementale : impacts environnementaux, sociaux, risques éthiques
  3. Propositions responsables : 3 choix techniques justifiés, alternatives, compromis assumés
  4. Position personnelle : ma responsabilité en tant que développeur dans ce projet
- Pour aller plus loin : GreenIT.fr, Institut du Numérique Responsable, formations ecoresponsable.numerique.gouv.fr, ADEME.

---

## Points d'attention

1. **Lacunes à combler dans le support** :
   - histoire FSF / Stallman vs OSI ;
   - responsabilité face aux dépendances (log4shell, left-pad, xz-utils, épuisement des mainteneurs) ;
   - licences Ethical Source nommées (Hippocratic License, Contributor Covenant) ;
   - RGAA / WCAG ;
   - cas réels de biais (COMPAS, Amazon recruiting, algorithme de la CAF).
2. **Erreur dans le deck coda** (p. 126) : « Open Systems Interconnection (OSI) » devrait être **Open Source Initiative**.
3. **Chiffres à rafraîchir** dans le deck INR (WWF 2019, 3,8 % GES) avec l'étude GreenIT 2025.
4. **Deck coda à condenser** : beaucoup de diapositives d'une seule ligne ; le temps gagné va aux ateliers.
