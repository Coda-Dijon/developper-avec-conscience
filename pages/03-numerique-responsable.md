---
layout: section
num: 3
color: lime
duration: 1h15
objective: Objectif 3
---

# Numérique responsable

Le numérique n'est pas immatériel

<!--
Séquence reprise de l'« Introduction au numérique responsable » de l'Académie NR (INR),
sous licence CC BY-NC-ND 4.0 : textes et visuels repris sans modification, source créditée sur chaque slide.
-->

---

# Test sondage

<div class="nb-split nb-split-r">
<div>

## Lequel de ces légumes est le plus triste ?

- A · Le poivron
- B · La tomate

</div>
<div class="nb-grid-2">
  <Figure src="/images/inr/pareidolie-poivron.webp" alt="Un poivron coupé en deux dont l'intérieur évoque un visage" caption="A · Le poivron" h="8.5rem" tilt="l" />
  <Figure src="/images/inr/pareidolie-tomate.webp" alt="Une tranche de tomate dont la chair évoque un visage triste" caption="B · La tomate" h="8.5rem" tilt="r" />
</div>
</div>

<div v-click class="nb-split nb-split-r mt-4">
<div class="nb-center">
  <Sticker color="lime" :rotate="-2">✓ Les 2 sont bonnes !</Sticker>
</div>
<Card title="🧠 La paréidolie" color="white" class="nb-small">

Notre cerveau **identifie une forme familière**, souvent un visage, dans un **stimulus vague** : nuage, fumée, tache d'encre… ou légume. **Notre cerveau peut nous tromper**, y compris sur les ordres de grandeur du numérique.

</Card>
</div>

<Source inr />

<!--
Faire voter la salle, puis cliquer pour révéler la réponse : les 2 sont bonnes.
Paréidolie : identifier une forme familière dans un stimulus vague (nuage, fumée, tache d'encre, légume…).
-->

---

# Plan

<div class="nb-split nb-split-l">
<div>

1. État de notre planète
2. Les impacts du numérique
3. Pourquoi faut-il changer ?
4. Le numérique responsable, késaco ?
5. Comment agir dès maintenant ?
6. Comment agir à mon niveau ?
7. Conclusion, aller plus loin

</div>
<Figure src="/images/inr/bitmoji-lune.webp" alt="Avatar adossé à un croissant de lune" bare h="17rem" />
</div>

<Source inr />

---
layout: statement
---

# 1 · État de notre planète

---

# Changement climatique

<div class="nb-split nb-split-l">
  <Figure src="/images/inr/changement-climatique-facteurs.webp" alt="Plusieurs facteurs sont responsables du changement climatique… mais les gaz à effet de serre en sont les principaux. Ils sont en partie émis naturellement, mais grandement par les activités humaines." h="18rem" />
  <div>
    <Figure src="/images/inr/gaz-effet-de-serre.webp" alt="Les gaz à effet de serre : le dioxyde de carbone CO2, le méthane CH4 et les autres gaz" h="7rem" />
    <Card color="lime" class="mt-6">
      <strong>En grande partie liées à la production d'énergie</strong>
    </Card>
  </div>
</div>

<Source inr />

---

# Changement climatique

<div class="nb-split">
<Figure src="/images/inr/rechauffement-thermometre.webp" alt="Frise de la dernière ère glaciaire, il y a 10 000 ans, à aujourd'hui, puis +1 à 5 °C en 2100" h="15rem" />
<div class="nb-small">

Réchauffement de **5 degrés** d'ici à fin 2100 :

- Montée des eaux : +82 cm
- **700 millions** de personnes devront changer d'habitat
- Cycle de l'eau se modifie
- Événements climatiques extrêmes plus fréquents
- Maladies tropicales se développent
- Biodiversité menacée : **20 à 30 %** des espèces végétales et animales pourraient disparaître

**3,3 milliards** d'êtres humains exposés au changement climatique

🎬 [Vidéo ADEME](https://www.youtube.com/watch?v=NfaeoCORuzk)

</div>
</div>

<Source inr />

<!-- Chiffres : rapport du GIEC, groupe de travail 2. https://www.ipcc.ch/ -->

---

# A des impacts sur

<div class="nb-center">
  <Figure src="/images/inr/impacts-societe-economie-environnement.webp" alt="Diagramme : impacts sur la société (réfugiés climatiques, effets sur la santé), l'économie (conflits politiques, conséquences des catastrophes naturelles) et l'environnement (perte de la biodiversité, épuisement des ressources naturelles, acidification des océans)" h="23rem" />
</div>

<Source inr />

---

# Impact sur les ressources

<div class="nb-center">
  <Figure src="/images/inr/epuisement-ressources.webp" alt="Tableau d'épuisement des ressources : au rythme actuel de notre consommation, il n'y aura plus d'argent, d'or, de plomb, de cuivre, d'uranium, de pétrole, de gaz naturel, de fer, d'aluminium et de charbon, avec des échéances entre 2030 et 2150 environ" caption="Les ressources de notre planète sont limitées et menacées" h="21rem" />
</div>

<Source inr />

---
clicks: 1
---

<div class="nb-split nb-split-l">
<Quiz
  question="Chaque année, combien de fois la France consomme-t-elle les ressources naturelles que la Terre peut régénérer ?"
  :options="['4,1 fois', '1,75 fois', '0,7 fois', '2,7 fois']"
  :answer="3"
  source="Chiffres WWF 2019"
/>
<Figure src="/images/inr/bitmoji-boule-cristal.webp" alt="Avatar devant une boule de cristal" bare h="15rem" />
</div>

<Source inr />

<!-- Pour aller plus loin : le jour du dépassement, https://www.overshootday.org/ -->

---

# Le développement durable

> « Le Développement Durable est un développement qui répond aux besoins du présent sans compromettre la capacité des générations futures à répondre à leurs propres besoins. »
> Rapport Brundtland, 1987

<div class="nb-center mt-4">
  <Figure src="/images/inr/developpement-durable-venn.webp" alt="Diagramme de Venn : Société, Économie et Environnement. Leurs intersections sont Équitable, Vivable et Viable ; au centre, Durable." h="14rem" />
</div>

<Source inr />

---

# Développement durable · ODD

<div class="nb-split nb-split-r">
<Figure src="/images/inr/odd.webp" alt="Les 17 Objectifs de Développement Durable répartis entre biosphère, société et économie" h="20rem" />
<div>

**17 Objectifs de Développement Durable** permettant de mettre en pratique le cadre (multifactoriel) de pensée du développement durable.

🔗 [Les 17 ODD (ONU)](https://www.un.org/sustainabledevelopment/fr/objectifs-de-developpement-durable/)

</div>
</div>

<Source inr />

---
layout: statement
---

# 2 · Les impacts du numérique

---
clicks: 1
---

<div class="nb-split nb-split-l">
<Quiz
  question="Combien d'ordinateurs sont vendus en France chaque année ?"
  :options="['1,5 million', '3,1 millions', '4,7 millions', '8,4 millions']"
  :answer="1"
  source="8 400 ordinateurs par jour"
/>
<Figure src="/images/inr/bitmoji-boule-cristal.webp" alt="Avatar devant une boule de cristal" bare h="15rem" />
</div>

<Source inr />

---

# Le numérique en chiffres

<div class="nb-split">
<div>
  <Figure src="/images/inr/numerique-chiffres-1.webp" alt="40 smartphones achetés dans le monde chaque seconde ; 281 milliards d'e-mails envoyés chaque jour ; 50 millions de tweets publiés chaque jour, soit plus de 25 milliards par an ; 31 pages imprimées par jour et par salarié ; 50 milliards d'objets connectés en 2020 ; 600 watts consommés par chaque employé pendant 8 h, soit l'équivalent de 2 radiateurs" h="12rem" />
  <Figure src="/images/inr/numerique-chiffres-2.webp" alt="53 millions de tonnes de déchets électroniques en 2019 dans le monde ; leur nombre a augmenté de 21 % en 5 ans ; leur taux de recyclage est de 17,4 %" h="8rem" class="mt-4" />
</div>
<div class="nb-small">

Certains usages posent questions en termes d'impacts :

- Montres, gadgets, NFT…
- Réalité augmentée

D'autres apportent des solutions intéressantes / une valeur ajoutée sociétale :

- Le télétravail permet d'éviter les déplacements
- Lorsque nous y avons accès, le numérique permet de décloisonner les territoires

</div>
</div>

<Source inr />

---
clicks: 1
---

# L'énergie

L'énergie que nous consommons est majoritairement produite à partir d'énergies fossiles.

<Quiz
  question="Selon vous, la consommation électrique du numérique mondial correspond à :"
  :options="['1 % de l’électricité', '10 % de l’électricité', '20 % de l’électricité', '30 % de l’électricité']"
  :answer="1"
/>

<Source inr />

---

# L'énergie

<div class="nb-split nb-split-r">
<Figure src="/images/inr/production-energie-mondiale.webp" alt="Courbe de la production d'énergie mondiale de 1860 à 2000, en forte hausse avec le moteur à essence, l'ampoule, l'aviation civile et l'énergie nucléaire" h="21rem" />
<div>

Pour produire de l'énergie, **il faut de l'eau…**

**Beaucoup d'eau !**

*L'eau est une ressource finie…*

</div>
</div>

<Source inr />

<!-- Centrales thermiques, cogénération, géothermie, centrales à charbon : turbines à vapeur et circuits de refroidissement. -->

---

# Impacts environnementaux du numérique

<div class="nb-split nb-split-l">
<div class="nb-grid-3">
  <Card title="3,8 %" color="magenta">de GES<br><em>Plus de GES que l'aviation civile</em></Card>
  <Card title="0,2 %" color="blue">de la consommation d'eau</Card>
  <Card title="10 %" color="lime">de l'électricité mondiale</Card>
</div>
<Figure src="/images/inr/bitmoji-explosion.webp" alt="Avatar à côté d'un thermomètre qui explose" bare h="18rem" />
</div>

<Source inr />

<!-- Les 3,8 % pourraient doubler d'ici la fin de cette décennie. Voir les chiffres 2025 de GreenIT en fin de séquence. -->

---

# Analyse du Cycle de Vie

<div class="nb-center">
  <Figure src="/images/inr/cycle-de-vie.webp" alt="Cycle de vie d'un équipement : matières premières, fabrication, transport, distribution, utilisation, fin de vie, valorisation" h="22rem" />
</div>

<Source inr />

---
clicks: 1
---

# Nos smartphones

<div class="nb-split nb-split-l">
<Quiz
  question="Combien de kg de matières premières pour fabriquer 1 smartphone de 5,5 pouces ?"
  :options="['10 kg', '50 kg', '100 kg', '200 kg']"
  :answer="3"
  source="Plus de 70 matières premières différentes du tableau périodique des éléments"
/>
<Figure src="/images/inr/tableau-periodique.webp" alt="Tableau périodique des éléments, avec en surbrillance ceux qui entrent dans la fabrication d'un smartphone" h="14rem" />
</div>

<Source inr />

<!--
Certaines matières manqueront d'ici la fin du siècle, beaucoup plus tôt pour d'autres.
Certaines sont actuellement limitées : risque en termes d'approvisionnement.
Certaines se trouvent dans des zones géographiques en conflit.
-->

---

# Nos smartphones

<div class="nb-split nb-split-r">
<div>

- **Moins de 10 %** des téléphones sont collectés pour être recyclés
- Contiennent des **métaux rares** avec un fort impact environnemental

</div>
<Figure src="/images/inr/smartphone-terres-rares.webp" alt="Produire 1 tonne de terres rares génère 60 000 m³ de déchets gazeux contenant de l'acide hydrochlorique, 200 m³ d'acide déversé dans l'eau et 1 à 1,4 tonne de déchets radioactifs" h="20rem" />
</div>

<Source inr />

---

# Impacts économiques

<div class="nb-grid-2">
<Card color="white">
  <Figure src="/images/inr/pouce-bas.webp" alt="Pouce vers le bas : impacts négatifs" bare h="4.5rem" />

- **Création d'applications… inutilisées** : mobilise du temps, des ressources, du budget
- **Écrans, ordinateurs, téléphones moins robustes** : sont devenus des biens jetables, nous consommons plus…

</Card>
<Card color="white">
  <Figure src="/images/inr/pouce-haut.webp" alt="Pouce vers le haut : impacts positifs" bare h="4.5rem" />

- De nouvelles **économies** : façons de travailler, voient le jour
- Permet la **croissance de la productivité et de la performance**
- Accélération des échanges / facilite la prise de décision

</Card>
</div>

<Source inr />

---

# Impacts sociaux

<div class="nb-grid-2 nb-small">
<Card color="white">
  <Figure src="/images/inr/pouce-bas.webp" alt="Pouce vers le bas : impacts négatifs" bare h="4rem" />

- Être **addictifs** : peut isoler socialement
- **Fracture numérique** : isoler quand nous ne sommes pas formés, ou quand nous vivons dans une zone manquant d'infrastructure
- Effets sur la santé du **DAS** (Débit d'Absorption Spécifique)
- Limiter **l'autonomie des utilisateurs déficients** : objets numériques pas toujours conçus pour tous

</Card>
<Card color="white">
  <Figure src="/images/inr/pouce-haut.webp" alt="Pouce vers le haut : impacts positifs" bare h="4rem" />

- **Travail à distance** : permet le développement des territoires
- **Rester en contact** avec nos proches, partout dans le monde
- **Pallier certaines déficiences** : technologies d'assistance (outils d'agrandissement, lecteurs d'écran…)

</Card>
</div>

<Source inr />

---

# Impacts sociaux

<div class="nb-split">
<div>
  <Figure src="/images/inr/illectronisme.webp" alt="L'illectronisme, qui touche 17 % de la population française, est la difficulté, voire l'incapacité, que rencontre une personne à utiliser les appareils numériques. Nous parlons de fracture numérique." h="11rem" />
  <Figure src="/images/inr/rgaa.webp" alt="Le Référentiel Général d'Amélioration de l'Accessibilité (RGAA) est une norme pour rendre accessibles les outils numériques" h="7rem" class="mt-4" />
</div>
<Figure src="/images/inr/accessibilite-numerique.webp" alt="L'accessibilité numérique regroupe les problématiques d'accès aux contenus et services web : par les personnes handicapées, et plus généralement par tous les utilisateurs, quels que soient leurs dispositifs ou leurs conditions d'environnement" h="20rem" />
</div>

<Source inr />

<!-- RGAA : https://accessibilite.numerique.gouv.fr/ · WCAG : https://www.w3.org/WAI/standards-guidelines/wcag/ -->

---
layout: statement
---

# 3 · Pourquoi faut-il changer ?

---

# Pourquoi faut-il changer ? · Levier économique

**La pression économique concernant le coût de l'énergie s'intensifie**

<div class="nb-center my-6">
  <Figure src="/images/inr/levier-economique.webp" alt="Mais rendre le numérique plus responsable peut être une opportunité pour les entreprises" h="9rem" />
</div>

> **Optimiser** un service numérique **permet de réduire les coûts d'énergie** tout au long du cycle de vie.

<Source inr />

---

# Pourquoi faut-il changer ? · Levier sociétal

<div class="nb-split">
<div>

**Inclusion numérique** : rendre accessible le numérique à chaque individu !

**Accessibilité numérique** : mettre le numérique **à la portée de tous**, notamment aux personnes en situation de handicap

</div>
<div>
  <Figure src="/images/inr/inclusion-40.webp" alt="40 % de la population n'est pas complètement autonome dans ses usages numériques" h="8rem" />
  <Figure src="/images/inr/inclusion-permet.webp" alt="Cela permet de toucher une plus large partie de la population, de rendre les services plus ergonomiques et plus faciles d'utilisation, et d'optimiser le poids des pages" h="8rem" class="mt-4" />
</div>
</div>

<Source inr />

---

# Pourquoi faut-il changer ? · Levier politique

La pression réglementaire s'intensifie. Une démarche numérique responsable permet **d'anticiper la réglementation actuelle et celle à venir**.

<div class="nb-split nb-small">
<div>

**Réglementation internationale**

- **Convention de Bâle** : gestion des déchets dangereux européens au sein de l'Europe
- **Directive Ecodesign** (Europe) : affichage environnemental d'une partie des serveurs
- **Directive Batteries** (Europe) : prévoit des batteries changeables par l'utilisateur
- **Directive RoHS** (Europe) : limite les produits nocifs dans nos appareils électroniques

</div>
<div>

**Réglementation « locale »**

<div class="flex gap-4 items-center">
  <Figure src="/images/inr/iso-26000.webp" alt="Normes ISO 26000 (responsabilité sociétale) et ISO 14006" h="6rem" />
  <Figure src="/images/inr/loi-agec.webp" alt="Loi anti-gaspillage pour une économie circulaire (AGEC) et ses obligations d'information des consommateurs" h="9rem" />
</div>

🔗 [Loi REEN du 15 novembre 2021](https://www.legifrance.gouv.fr/jorf/id/JORFTEXT000044327272) : réduire l'empreinte environnementale du numérique

</div>
</div>

<Source inr />

---
layout: statement
---

# 4 · Le numérique responsable, késaco ?

---

# Le numérique responsable

La démarche du numérique responsable vise à **réduire l'empreinte écologique et sociale des technologies** de l'information et de la communication.

<div class="nb-split">
<Figure src="/images/inr/numerique-responsable-venn.webp" alt="Diagramme de Venn du numérique responsable : économique, social et environnemental ; au centre, durable" h="14rem" />
<div class="nb-small">

Le numérique responsable regroupe toutes les démarches qui visent à :

- **Créer de la valeur** économique, sociale et environnementale **grâce au numérique**
- **Réduire l'empreinte** économique, sociale et environnementale **du numérique**
- **Réduire grâce au numérique** l'empreinte économique, sociale et environnementale d'autres processus

</div>
</div>

<Source inr />

---

# Les axes stratégiques

<div class="nb-center">
  <Figure src="/images/inr/axes-strategiques.webp" alt="Les 5 axes : 1 limiter les impacts et la consommation ; 2 rendre accessible, inclusif et durable ; 3 rendre éthique et responsable ; 4 favoriser la résilience des organisations ; 5 permettre l'émergence de nouveaux comportements et valeurs" h="23rem" />
</div>

<Source inr />

---

# 1 · Limiter les impacts et la consommation

Optimiser les outils numériques pour limiter leurs impacts et consommations

<div class="nb-center">
  <Figure src="/images/inr/axe1-limiter-impacts.webp" alt="Prolonger la durée de vie des équipements ; avoir une conception responsable des services et des usages ; gérer correctement les ressources ; prendre en compte le cycle de vie des équipements et des logiciels ; favoriser le réemploi ou l'achat d'outils numériques recyclés et les achats responsables ; privilégier les sources d'énergies renouvelables" h="19rem" />
</div>

<Source inr />

---

# 2 · Rendre accessible, inclusif et durable

Offrir des services accessibles pour tous, inclusifs et durables

<div class="nb-grid-2 mt-4">
  <Figure src="/images/inr/axe2-applications-accessibles.webp" alt="Applications accessibles à tous : pour des personnes en situation de handicap ou d'illectronisme, avec des services numériques dimensionnés pour les personnes avec un bas débit ; pour tous, urbains, ruraux, jeunes et moins jeunes" h="8rem" />
  <Figure src="/images/inr/axe2-utiles.webp" alt="Utiles, utilisables, utilisées : des services utiles qui répondent à des besoins responsables ; si un service n'est pas utilisé, le fermer" h="8rem" />
</div>
<div class="nb-center mt-6">
  <Figure src="/images/inr/axe2-achats-responsables.webp" alt="Achats responsables de services éco-conçus, en associant l'utilisateur à la conception" h="6rem" />
</div>

<Source inr />

---

# 3 · Rendre éthique et responsable

Mettre en place un numérique éthique et responsable

<div class="nb-split" style="grid-template-columns: 3fr 1fr;">
<Figure src="/images/inr/axe3-ethique.webp" alt="Respecter les réglementations applicables dont celles relatives à la protection des données (RGPD) ; mettre en place une politique RSE ; raisonner l'usage des services pour limiter l'impact environnemental du numérique ; permettre une valorisation sociale avec un recrutement d'égalité homme-femme incluant toutes les diversités du public ; instaurer un dispositif d'éthique algorithmique" h="18rem" />
<div>

🔗 [CNIL · Éthique et intelligence artificielle](https://www.cnil.fr/fr/ethique-et-intelligence-artificielle)

</div>
</div>

<Source inr />

---

# 4 · Favoriser la résilience des organisations

Assurer la résilience des organisations (processus permettant de surmonter les épreuves)

<div class="nb-center">
  <Figure src="/images/inr/axe4-resilience.webp" alt="Respect des normes ; démarche collaborative de la conception ; innovation" h="19rem" />
</div>

<Source inr />

---

# 5 · Nouveaux comportements et valeurs

Permettre l'émergence de nouveaux comportements et valeurs

<div class="nb-center">
  <Figure src="/images/inr/axe5-comportements.webp" alt="Valorisation des initiatives internes ; mise en place d'indicateurs de performances ; rationalisation des procédures ; innovation sociale ; engagement et expertise" h="14rem" />
</div>

<Source inr />

---

# Le green for IT

Réduire l'empreinte environnementale du numérique en **évitant l'achat** et en **réduisant l'extraction** de minéraux / terres rares.

La règle des **5 R** est une recommandation de mode de vie écologique visant à minimiser l'impact de nos déchets :

<div class="nb-split nb-split-l mt-2">
<div>

- **Refuser** tous les produits à usage unique et privilégier les achats sans déchet comme le vrac
- **Réduire** la consommation de biens
- **Réutiliser** tout ce qui peut l'être
- **Recycler** tout ce qui ne peut pas être réutilisé
- **Réparer** tout ce qui peut l'être

</div>
<div class="flex flex-col items-start gap-3">
  <Sticker color="magenta" :rotate="-2">Refuser</Sticker>
  <Sticker color="lime" :rotate="2">Réduire</Sticker>
  <Sticker color="blue" :rotate="-1">Réutiliser</Sticker>
  <Sticker color="lavender" :rotate="3">Recycler</Sticker>
  <Sticker color="violet" :rotate="-3">Réparer</Sticker>
</div>
</div>

🔗 [Calculer son impact environnemental](https://nosgestesclimat.fr/)

<Source inr />

---

# Encore de nombreux éléments

- **IT for Green** : réduire grâce au numérique l'empreinte environnementale
- **Human for IT** : réduire grâce au numérique l'empreinte économique et sociale de notre économie et de nos modes de vie
- **IT for Human** : réduire grâce au numérique l'empreinte économique et sociale d'autres processus

<div class="nb-small mt-4">

- Analyse de Cycle de Vie
- Méthodologie ERC (Éviter, Réduire, Compenser)
- Numérique responsable et Objectifs de Développement Durable
- …

</div>

<Source inr />

---
layout: statement
---

# 5 · Comment agir dès maintenant ?

---

# Agir dès maintenant · le poste de travail

<div class="nb-split">
<Figure src="/images/inr/poste-de-travail-chiffres.webp" alt="4 milliards de PC dans le monde, dont 70 % dans les pays émergents ; durée moyenne d'utilisation divisée par 3 en 30 ans ; principale consommation d'énergie et de déchets électroniques : 10 kg de DEEE par employé et par an en France" h="13rem" />
<div class="nb-small">

**Fabrication d'1 ordinateur :**

- 373 litres de pétrole (production d'énergie)
- 1 500 litres d'eau
- 22 kg de produits chimiques

Produit **164 kg de déchets** dangereux pour l'environnement, dont 24 kg de produits toxiques

> Fabrication = partie la plus impactante de son cycle de vie

</div>
</div>

<Source inr />

---
clicks: 1
---

# Agir dès maintenant · le poste de travail

<div class="nb-split nb-split-l">
<Quiz
  question="Avec quelques bons gestes, quelle part de la consommation électrique des équipements informatiques pourrait être évitée ?"
  :options="['1/4', '1/3', '1/2', '1/5']"
  :answer="0"
/>
<Figure src="/images/inr/taux-consommation-utile.webp" alt="Taux de consommation utile ou inutile par équipement : copieur, PC fixe, imprimante, client léger, PC portable, téléphone IP" h="14rem" />
</div>

<Source inr />

---

# Agir dès maintenant · bonnes pratiques

<div class="nb-grid-2 nb-small">
<Card title="Ordinateurs" color="white">

- L'ordinateur le plus « vert » est celui qu'on ne fabrique pas : **allonger sa durée de vie**
- **Réduire** : privilégiez le label EPEAT ou TCO (ou à minima Energy Star)
- Utilisez les logiciels de power management qui étudient et minimisent les consommations énergétiques

</Card>
<Card title="Achats" color="white">

- **Éviter** : ne pas acheter ; renoncer à l'achat de périphériques si on en a déjà (clavier, souris…)
- Acheter le plus responsable possible en intégrant des critères environnementaux et sociaux (appels d'offres, équipements, services, marchés…)
- **Réduire** : matériel professionnel d'occasion reconditionné ; louer (économie de la fonctionnalité) ; DAS et principe de précaution ; indice de réparabilité ; labels

</Card>
</div>

<Source inr />

---

# Agir dès maintenant · les services numériques

<div class="nb-split">
<div>
  <Figure src="/images/inr/services-constats.webp" alt="3 constats clés concernant ses impacts : de plus en plus de services numériques qui répondent à des envies plus qu'à des besoins ; des services de plus en plus lourds : plus de vidéos, de pages… plus lourdes ; le phénomène d'obsolescence s'intensifie" h="8rem" />
  <Figure src="/images/inr/services-fonctionnalites-inutilisees.webp" alt="Environ la moitié des fonctionnalités logicielles demandées par les utilisateurs n'est jamais utilisée" h="6rem" class="mt-4" />
</div>
<Figure src="/images/inr/services-chiffres.webp" alt="25 % d'applications jamais utilisées ; 70 % des entreprises achètent des applications qui seront sous-utilisées ; 15 % des applications sous-utilisées n'apportent pas de valeur ; 5,8 % du budget alloué à des applications sous-utilisées ; 16 milliards : prix des applications inutiles ou peu utiles à l'échelle européenne ; 10 à 50 % de logiciels qui pourraient être supprimés sans nuire à l'utilité" h="17rem" />
</div>

<Source inr />

---

# CoRSeN

**Démarche de conception responsable des services numériques (CoRSeN)**

<div class="nb-split nb-small">
<div>

- S'appuie sur la norme **ISO 14062**
- Permet de réduire au maximum l'impact environnemental et social de ses produits et systèmes, en agissant **le plus en amont possible** dans la conception
- Intégration de bonnes pratiques et de référentiels

<Figure src="/images/inr/corsen-bonnes-pratiques.webp" alt="Favoriser l'accessibilité en utilisant le référentiel existant ; lutter contre l'illectronisme en déployant de bonnes pratiques" h="9rem" />

</div>
<Figure src="/images/inr/corsen-comment-faire.webp" alt="Comment faire ? 60 % des améliorations sont liées à la conception fonctionnelle et technique, 15 % au développement et 25 % à l'hébergement" h="17rem" />
</div>

<Source inr />

---

# Les services numériques · exemples

<div class="nb-grid-2">
<div>

**Choix d'1 algorithme différent pour optimisation**

<Figure src="/images/inr/exemple-algorithme.webp" alt="Avant / après : de 33 heures à 20 minutes de traitement, de plusieurs MWh à 700 kWh par traitement" h="9rem" />
<Figure src="/images/inr/exemple-resultat.webp" alt="Résultat : 100 fois plus rapide et 100 fois moins énergivore" h="4rem" class="mt-3" />

</div>
<div>

**Consultation trop longue lors d'une recherche de produit : 12 secondes**

<Figure src="/images/inr/exemple-recherche-produit.webp" alt="Avant / après : 3 fois moins de temps lors de la consultation, 3 fois moins de temps d'attente des clients, 3 fois moins de temps perdu par les vendeurs, 3 fois moins de serveurs sollicités" h="12rem" />

</div>
</div>

<Source inr />

---

# Conception Responsable des Services Numériques

<div class="nb-center">
  <Figure src="/images/inr/conception-responsable.webp" alt="La conception responsable des services numériques (CoRSeN) a des vertus pour l'organisation : elle réduit les impacts environnementaux de ses services, elle réduit les impacts sociaux, elle est reconnue comme bénéfique pour la réputation de l'entreprise, elle renforce l'engagement des salariés et la cohésion, elle occasionne une montée en compétence des personnels impliqués" h="22rem" />
</div>

<Source inr />

---

# Agir dès maintenant · autres exemples

<div class="nb-grid-2">
<Card title="🖨️ Système d'impression" color="white">

- **Éviter** : ¼ des impressions sont jetées durant les 5 minutes suivant l'impression
- **Réduire** : paramétrer le mode recto/verso, brouillon et noir et blanc par défaut ; utiliser des fonts éco-responsables (Times New Roman, Cambria, Arial…)

</Card>
<Card title="🗄️ Data center" color="white">

- **Éviter** : éteindre les éléments inactifs
- **Réduire** : activer les fonctions d'économie d'énergie des éléments actifs ; réduire les volumes de données

</Card>
</div>

<Source inr />

---

# 🔎 Audit éclair

<div class="nb-split">
<Card title="Par binôme · 15 min" color="lime">

1. Choisissez un site que vous utilisez tous les jours
2. Mesurez-le avec [EcoIndex](https://www.ecoindex.fr/), [GreenIT-Analysis](https://github.com/cnumr/GreenIT-Analysis) ou [Lighthouse](https://developer.chrome.com/docs/lighthouse)
3. Choisissez **3 critères du RGESN** qu'il ne respecte pas
4. Proposez une correction pour chacun

</Card>
<div class="nb-small">

**RGESN** : Référentiel Général d'Écoconception de Services Numériques, publié par l'Arcep, l'Arcom et l'ADEME.

Il couvre toute la vie d'un service : stratégie, spécifications, architecture, UX/UI, contenus, frontend, backend, hébergement, algorithmie.

🔗 [Le RGESN](https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/)

</div>
</div>

---
layout: statement
---

# 6 · Comment agir à mon niveau ?

---

# Comment agir à mon niveau ?

> « Certes, je ne suis qu'un. Mais je suis un. Je ne peux pas tout faire. Mais je peux faire quelque chose. Et le fait de ne pas pouvoir tout faire ne m'autorise pas à refuser de faire ce que je peux faire. »
> Edward Everett

<div class="nb-split mt-4">
  <Figure src="/images/inr/colibri.webp" alt="Comment arrêter l'incendie ? Un colibri transporte une goutte d'eau" h="8rem" />
  <Figure src="/images/inr/legende-colibri.webp" alt="Affiche de la légende du colibri : face à l'incendie de la forêt, le colibri apporte quelques gouttes d'eau. Je fais ma part." h="10rem" />
</div>

<Source href="https://www.greenit.fr/">GreenIT.fr</Source>

<!-- La légende du colibri : https://www.colibris-lemouvement.org/ -->

---

# Comment agir à mon niveau ?

<div class="nb-split nb-split-l">
<div class="nb-small">

- **Allonger la durée de vie** de nos appareils : en prendre soin ; n'installer que les mises à jour correctives indispensables (éviter l'obsolescence programmée)
- **Éteindre** notre **box** et **boîtier TV** : 1 box ADSL + boîtier TV allumés 24/24 = 150 à 300 kWh par an, l'équivalent de 5 à 10 ordinateurs 15 pouces utilisés 8 h/jour
- **Limiter l'usage du Cloud**, surtout en **4G** : le transport d'1 donnée génère 2 fois plus d'impacts environnementaux que son stockage ; stocker le plus de données en local ; la 4G a des répercussions 20 fois plus importantes qu'ADSL/fibre
- Regarder la télévision via la **TNT** : la vidéo en ligne représente 60 à 90 % du trafic internet d'un pays ; regarder 1 film en HD via sa box a le même impact que fabriquer 1 DVD ou Blu-Ray

</div>
<Figure src="/images/inr/bitmoji-pupitre.webp" alt="Avatar qui lève la main derrière un pupitre" bare h="15rem" />
</div>

<Source href="https://www.greenit.fr/">GreenIT.fr</Source>

---

# Comment agir à mon niveau ?

<div class="nb-split nb-split-l">
<div>

- Privilégier le **réemploi** des équipements d'occasion
- **Acheter moins** et **partager plus** : connexion internet, imprimante, tablette…
- **Réparer** ce qui peut l'être : crée de l'emploi, diminue la pollution
- **Changer d'électricité** : choisir un fournisseur distribuant de l'énergie renouvelable

</div>
<Figure src="/images/inr/bitmoji-pupitre.webp" alt="Avatar qui lève la main derrière un pupitre" bare h="15rem" />
</div>

<Source href="https://www.greenit.fr/">GreenIT.fr</Source>

---

# Les chiffres 2025

<div class="nb-split nb-split-r">
<Figure src="/images/inr/greenit-2025.webp" alt="En 2025, le numérique est très matériel : 6 équipements actifs par internaute. Si le numérique était un pays, il émettrait autant de gaz à effet de serre que 5,5 fois la France. Top 3 des indicateurs environnementaux : 1 utilisation des ressources minérales et métaux, 2 potentiel de réchauffement climatique, 3 utilisation des ressources fossiles. Le numérique représente 40 % du budget annuel soutenable d'un internaute pour rester en dessous de 1,5 °C de réchauffement." h="19rem" />
<div>
  <Figure src="/images/inr/greenit-2025-ia.webp" alt="L'IA représente déjà plus de 4 % des émissions de GES du numérique. Comment réduire nos impacts ? 1 utiliser moins d'équipements, 2 conserver les équipements plus longtemps, 3 arbitrer nos usages du numérique" h="9rem" />

🔗 [GreenIT · Impacts environnementaux du numérique dans le monde, 2025](https://greenit.eco/nos-etudes-et-essais/impacts-environnementaux-du-numerique-dans-le-monde-2025/)

</div>
</div>

<Source href="https://greenit.eco/nos-etudes-et-essais/impacts-environnementaux-du-numerique-dans-le-monde-2025/">GreenIT, étude 2025</Source>

---

# Pour aller plus loin

<div class="nb-split nb-split-l nb-small">
<div>

- [Rapports du GIEC](https://www.ipcc.ch/)
- [Institut du Numérique Responsable](https://institutnr.org/) · [Académie NR](https://academie-nr.org/)
- [Belgian Institute for Sustainable IT](https://isit-be.org/)
- [GreenIT.fr](https://www.greenit.fr/)
- [Colibris](https://www.colibris-lemouvement.org/)
- [Time for the Planet](https://www.time-planet.com/)
- [Guide des bonnes pratiques numérique responsable](https://ecoresponsable.numerique.gouv.fr/publications/bonnes-pratiques/)
- [RGESN](https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/)

</div>
<Figure src="/images/inr/guide-bonnes-pratiques.webp" alt="Couverture du guide Bonnes pratiques numérique responsable pour les organisations" h="16rem" />
</div>

<Source inr />

---

# Quelques livres

<div class="nb-grid-3 mt-2" style="grid-template-columns: repeat(4, 1fr);">
  <Figure src="/images/inr/livre-enfer-numerique.webp" alt="Couverture : L'enfer numérique, voyage au bout d'un like, Guillaume Pitron" caption="L'enfer numérique · G. Pitron" h="15rem" />
  <Figure src="/images/inr/livre-sobriete-numerique.webp" alt="Couverture : Sobriété numérique, les clés pour agir, Frédéric Bordage" caption="Sobriété numérique · F. Bordage" h="15rem" />
  <Figure src="/images/inr/livre-une-vie-sur-notre-planete.webp" alt="Couverture : Une vie sur notre planète, David Attenborough" caption="Une vie sur notre planète · D. Attenborough" h="15rem" />
  <Figure src="/images/inr/livre-petit-manuel-resistance.webp" alt="Couverture : Petit manuel de résistance contemporaine, Cyril Dion" caption="Petit manuel de résistance contemporaine · C. Dion" h="15rem" />
</div>

<Source inr />

---

# Pour se former

<div class="nb-split">
<Figure src="/images/inr/formation-ecoconception.webp" alt="Page de la formation d'initiation à l'écoconception de service numérique, avec sa vidéo" h="17rem" />
<div>

**Formation initiation à l'écoconception de service numérique**

Vidéo d'environ 2 h, en accès libre.

🔗 [ecoresponsable.numerique.gouv.fr/formations](https://ecoresponsable.numerique.gouv.fr/formations/)

</div>
</div>

<Source inr />

---

# Changement climatique

<div class="nb-center">
  <Figure src="/images/inr/dinos-comics.webp" alt="Bande dessinée en 4 cases, deux dinosaures regardent une météorite arriver. « Je n'arrive pas à croire que c'est la fin. » « Ça pourrait être pire. » « Comment ? » « On aurait pu nous dire comment l'éviter et nous n'aurions rien fait pour. »" h="23rem" />
</div>

<Source inr />

<!-- Bande dessinée : Dinos and Comics -->

---
layout: statement
---

# La sobriété est un choix de conception,<br>pas une contrainte tardive.

<div class="mt-8"><Sticker color="white">✍️ 1 engagement NR pour ma charte</Sticker></div>
