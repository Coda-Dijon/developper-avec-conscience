---
layout: section
num: 4
color: magenta
duration: 1h05
objective: Objectif 3
---

# Impacts humains du code

Accessibilité, dette technique, biais

---

# « C'est juste technique » : une illusion dangereuse

<div class="nb-split">
<div>

Un choix technique :

- n'est **jamais neutre**
- **privilégie** certains usages
- **pénalise** certains publics
- **consomme** certaines ressources

</div>
<Card title="Exemples" color="white">

- Single Page Application lourde vs site statique
- Framework surdimensionné
- Fonctionnalité « nice to have »

</Card>
</div>

> Le/la dév est un·e **décideur·euse indirect·e**. Performance ≠ éthique : un logiciel peut être très performant, mais inutilement complexe, énergivore ou surdimensionné.

---

# 🔄 3 stations tournantes

<div class="nb-grid-3 mt-6">
  <Card title="1 · Accessibilité" color="blue" tilt="l">Qui est exclu par votre code ?</Card>
  <Card title="2 · Dette technique" color="lime">Livrer vite mais mal ?</Card>
  <Card title="3 · Biais" color="magenta" tilt="r">Peut-on expliquer la décision ?</Card>
</div>

<div class="mt-6 nb-small">10 minutes par station. Chaque groupe laisse une trace écrite pour le groupe suivant.</div>

---

# Station 1 · Accessibilité

<div class="nb-split">
<div>

```html
<img src="banner.jpg">
```

vs

```html
<img src="banner.jpg"
     alt="Promotion d'un vélo électrique">
```

**Qui est exclu dans le premier cas ?** Quel impact social ? Quel impact environnemental indirect ?

</div>
<div class="nb-small">

L'accessibilité concerne :

- les handicaps **visuels, moteurs, cognitifs**
- les **personnes âgées**
- les **usages mobiles**
- les **connexions dégradées**

**Les références**

- [RGAA](https://accessibilite.numerique.gouv.fr/) : le référentiel français, obligatoire pour les services publics
- [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) : le standard international du W3C
- [European Accessibility Act](https://commission.europa.eu/strategy-and-policy/policies/justice-and-fundamental-rights/disability/union-equality-strategy-rights-persons-disabilities-2021-2030/european-accessibility-act_en) : s'applique aussi au privé depuis juin 2025

</div>
</div>

---

# Accessibilité et Green IT : même combat

<div class="nb-split">
<div>

Un site accessible est souvent :

- plus **simple**
- plus **léger**
- plus **rapide**
- plus **durable**

</div>
<div>
<Card title="Accessibilité = inclusion" color="blue" />
<Card title="Simplicité = moins de données" color="lime" class="mt-4" />
<Card title="Sobriété = durabilité" color="lavender" class="mt-4" />
</div>
</div>

> Un bon code est souvent **plus humain ET plus écologique**.

---

# Station 2 · Dette technique

<div class="nb-split">
<div>

**Définition** : des choix rapides, au détriment de la qualité, qui **reportent les coûts sur l'avenir**.

La métaphore vient de **Ward Cunningham** (1992) : comme une dette financière, elle génère des **intérêts** tant qu'on ne la rembourse pas.

🔗 [The WyCash Portfolio Management System](http://c2.com/doc/oopsla92.html)

</div>
<Card title="Pourquoi c'est un problème éthique" color="lime">

C'est un **transfert de charge** :

- vers les **collègues** et futurs mainteneurs
- vers l'**entreprise**
- vers l'**environnement** : plus de ressources consommées, des systèmes fragiles qu'on jette et qu'on refait

</Card>
</div>

---

# Dette technique : une dette morale ?

<Card title="💬 À débattre" color="white">

Est-il éthique de **livrer vite mais mal**, en sachant que **quelqu'un d'autre devra corriger** ?

</Card>

<div class="nb-grid-3 mt-6">
  <Card title="Consciente" color="lime">On sait qu'on s'endette, et pourquoi</Card>
  <Card title="Documentée" color="blue">Elle est visible : ADR, ticket, commentaire</Card>
  <Card title="Remboursée" color="lavender">Un plan existe pour la résorber</Card>
</div>

> La dette technique est parfois nécessaire, jamais anodine. Sinon → **transfert de charge injuste**.

---

# Station 3 · Biais algorithmiques

<div class="nb-split">
<div>

```php
if ($score > 70) {
  $user["profil"] = "premium";
}
```

- **Pourquoi 70 ?**
- **Qui a décidé ?**
- **Qui est exclu ?**
- **Peut-on expliquer la décision ?**

</div>
<div class="nb-small">

Les biais peuvent venir :

- des **données**
- des **règles métier**
- des **seuils**
- des **simplifications**

Le/la dév implémente souvent ces biais **sans les questionner**.

> Un algorithme doit pouvoir être **expliqué**.

</div>
</div>

---

# Quand le code discrimine

<div class="nb-grid-3 nb-small">
  <Card title="COMPAS · 2016" color="magenta">Un logiciel d'évaluation du risque de récidive, utilisé par des tribunaux américains, surestime ce risque pour les prévenus noirs. <a href="https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing">ProPublica ↗</a></Card>
  <Card title="Amazon · 2018" color="lime">Un outil de tri de CV, entraîné sur 10 ans de recrutements majoritairement masculins, pénalise les candidatures féminines. Il est abandonné. <a href="https://www.reuters.com/article/us-amazon-com-jobs-automation-insight-idUSKCN1MK08G">Reuters ↗</a></Card>
  <Card title="CAF · 2023" color="blue">L'algorithme de notation des allocataires cible davantage les contrôles sur les plus précaires. <a href="https://www.laquadrature.net/">La Quadrature du Net ↗</a></Card>
</div>

<div class="mt-6">

> Les biais ne sont pas des bugs rares : ce sont des **choix de conception** non questionnés.

</div>

---

# 🃏 Le Tarot de la Tech

<div class="nb-split nb-split-r">
<Figure src="/images/tarot/intro.webp" alt="Le Tarot de la Tech par Artefact : un outil pour aider les créateurs et créatrices à considérer l'impact de la technologie, avec des questions sur les conséquences imprévues et les opportunités de changement positif" h="16rem" />
<div class="nb-small">

Créé par l'agence **Artefact** pour anticiper les **conséquences imprévues** d'un produit, et les opportunités qu'il offre.

12 cartes, 12 angles : chacune pose des questions qui dérangent.

🔗 [tarotcardsoftech.artefactgroup.com](https://tarotcardsoftech.artefactgroup.com/)

</div>
</div>

<Source href="https://tarotcardsoftech.artefactgroup.com/">Artefact · The Tarot Cards of Tech</Source>

---

# 🃏 Étude de cas

<Card title="Situation" color="magenta">

Une entreprise souhaite ajouter : **autoplay vidéo**, **tracking détaillé**, **animations complexes**, **IA de recommandation**.

</Card>

<div class="nb-split mt-4">
<Figure src="/images/tarot/mere-nature.webp" alt="Carte Mère Nature : si l'environnement était votre client, comment votre produit changerait-il ? Quel retour l'environnement vous ferait-il sur votre produit ? Quels sont les comportements les plus polluants et les moins durables auxquels amène votre produit ?" caption="Carte imposée" h="12rem" />
<div class="nb-small">

1. Chaque groupe prend **Mère Nature** + tire **2 cartes au hasard**
2. Identifiez les impacts **environnementaux, sociaux, éthiques**
3. Proposez des **alternatives responsables**
4. **Justifiez** vos choix

⏱ 30 min

</div>
</div>

<Source href="https://tarotcardsoftech.artefactgroup.com/">Artefact · The Tarot Cards of Tech</Source>

---

# 🃏 Les cartes

<div class="nb-grid-3" style="grid-template-columns: repeat(4, 1fr); gap: 1rem;">
  <Figure src="/images/tarot/oublies.webp" alt="Carte Les Oublié·es : quand vous pensez à votre base d'utilisateurs, qui est exclu ?" h="7rem" />
  <Figure src="/images/tarot/sirene.webp" alt="Carte La Sirène : à quoi ressemblerait un usage excessif de votre produit ?" h="7rem" />
  <Figure src="/images/tarot/grand-mechant-loup.webp" alt="Carte Le Grand Méchant Loup : que pourrait faire une personne malintentionnée avec votre produit ?" h="7rem" />
  <Figure src="/images/tarot/gros-succes.webp" alt="Carte Le Gros Succès : que se passerait-il si 100 millions de personnes utilisaient votre produit ?" h="7rem" />
  <Figure src="/images/tarot/traitre.webp" alt="Carte Le Traître : qu'est-ce qui pourrait amener les gens à perdre confiance en votre produit ?" h="7rem" />
  <Figure src="/images/tarot/catalyseur.webp" alt="Carte Le Catalyseur : comment les habitudes culturelles pourraient-elles changer l'usage de votre produit ?" h="7rem" />
  <Figure src="/images/tarot/chien-guide.webp" alt="Carte Le Chien Guide : si votre produit était dédié à améliorer la vie d'une population sous-représentée ?" h="7rem" />
  <Figure src="/images/tarot/star-de-la-radio.webp" alt="Carte La Star de la Radio : qui ou qu'est-ce qui disparaîtrait si votre produit était un succès ?" h="7rem" />
</div>

<Source href="https://tarotcardsoftech.artefactgroup.com/">Artefact · The Tarot Cards of Tech</Source>

---

# Des propositions responsables

<div class="nb-grid-3 nb-small">
  <Card title="Environnement" color="lime">Données, serveurs, bande passante</Card>
  <Card title="Social" color="blue">Exclusion, attention captée</Card>
  <Card title="Éthique" color="magenta">Surveillance, manipulation</Card>
</div>

<div class="nb-grid-2 mt-6">
<Card title="Exemples d'alternatives" color="white">

- autoplay **désactivé par défaut**
- tracking **minimal et explicite**
- animations **sobres** (et `prefers-reduced-motion`)
- recommandation **explicable**

</Card>
<Card title="C'est exactement ce qu'on attend d'un·e dév responsable" color="lavender">

Identifier · Proposer · **Justifier**

</Card>
</div>

---

# Grille d'évaluation

Avant d'implémenter, posez-vous 7 questions :

<div class="nb-grid-2 mt-2">

1. Est-ce **utile** ?
2. **Qui** l'utilise ?
3. Qui est **exclu** ?
4. Est-ce **maintenable** ?

<div>

5. Est-ce **accessible** ?
6. Quel **impact environnemental** ?
7. Peut-on faire **plus simple** ?

</div>
</div>

<InrBox>

S'inspirer du [RGESN](https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/), de l'ADEME et de l'[Institut du Numérique Responsable](https://institutnr.org/).

</InrBox>
