---
layout: section
num: 0
color: lavender
duration: 20 min
---

# Ouverture

Le code n'est jamais neutre

---

# Breaking News

<div class="nb-split">
<Figure src="/images/ethics/breaking-news-template.webp" alt="Modèle de une Breaking News : imaginez que vous travaillez pour l'entreprise la plus éthique du monde, que vous venez de livrer un produit révolutionnaire, que vous faites la une de toutes les chaînes et êtes salués de toutes parts. Something went viral online." h="15rem" tilt="l" />
<Card title="Consigne · 8 min" color="lime">

Par groupe, imaginez la **une d'un journal** qui annonce le succès spectaculaire de votre produit :

- **Titre** : le succès en une phrase
- **Sous-titres** : de quoi parle l'histoire
- **Citations** : témoignages d'utilisateurs, de clients…
- **Image** : ce qui illustre le succès

</Card>
</div>

<!--
Source : Developers ethics, slide 3.
Garder les unes : elles seront retournées en séquence 5 avec la carte « Le Scandale » du Tarot de la Tech.
-->

---

# Le/la dév n'est plus un·e simple exécutant·e

<div class="nb-grid-2">
<Card title="Hier" color="white">

Le/la dév était perçu·e comme :

- un·e **technicien·ne**
- chargé·e d'**implémenter des spécifications**
- sans responsabilité directe sur les usages finaux

</Card>
<Card title="Aujourd'hui" color="lime">

Les logiciels :

- **structurent** nos interactions sociales
- **influencent** nos comportements
- **consomment** des ressources matérielles et énergétiques
- peuvent **exclure, surveiller, manipuler** ou **émanciper**

</Card>
</div>

> Chaque ligne de code est un choix technique, mais aussi **éthique, social et environnemental**.

---

# Éthique ou morale ?

<div class="nb-split">
<div>
<Card title="Morale" color="white">Ensemble de règles personnelles ou culturelles : ce que je crois être bien ou mal</Card>
<Card title="Éthique" color="violet" class="mt-4">Réflexion collective sur les conséquences de nos actes dans un contexte donné</Card>
</div>
<Figure src="/images/ethics/definition-ethics.webp" alt="Définition du mot ethics dans un dictionnaire anglais : moral principles that govern a person's behaviour or the conducting of an activity" h="12rem" />
</div>

> En développement, l'éthique c'est se demander **« devrais-je le faire ? »**, pas seulement « puis-je le faire ? »

---

# L'éthique du/de la dév

<div class="nb-split">
<div>

La capacité à **anticiper, comprendre et assumer** les impacts de ses choix techniques sur :

- les **utilisateurs**
- la **société**
- l'**environnement**
- ses **collègues** et futurs mainteneurs

</div>
<Card title="Cela inclut" color="lime">

- le choix des technologies
- l'architecture
- la qualité du code
- l'accessibilité
- la performance
- la durabilité

</Card>
</div>

---

# Ce code est-il neutre ?

<div class="nb-split">
<div>

```js
const users = [
  { name: "Alice", age: 17 },
  { name: "Bob", age: 22 },
  { name: "Charlie", age: 15 }
];

users.forEach(user => {
  if (user.age >= 18) {
    console.log(`${user.name} peut accéder au service`);
  }
});
```

</div>
<div class="nb-small">

**Questions à se poser**

1. Ce code fonctionne-t-il ?
2. Est-il neutre ?
3. Quels choix implicites sont faits ?
4. Quels impacts possibles ?

</div>
</div>

<!--
Source : coda p. 33-42.
Fonctionne ? Oui. Neutre ? Non. Choix implicites : seuil arbitraire (18 ans), pas de message pour les exclus, pas d'explication.
Impacts : exclusion, incompréhension, frustration, discrimination indirecte.
-->

---

# Même un `if`…

<div class="nb-grid-3 mt-6">
  <Card title="traduit une règle" color="lime" tilt="l">Seuil arbitraire : 18 ans</Card>
  <Card title="crée une frontière" color="magenta">Aucun message pour les exclus</Card>
  <Card title="a un impact humain" color="blue" tilt="r">Exclusion, frustration, discrimination indirecte</Card>
</div>

<div class="nb-split mt-6">

> L'éthique commence dans les détails.

```js
if (user.age < 18) {
  showMessage("Service réservé aux majeurs");
}
```

</div>

<!-- Bonnes pratiques : expliquer la règle, prévoir une alternative, rendre la décision compréhensible. -->

---

# 4 dimensions d'impact

<div class="nb-grid-2 mt-4">
  <Card title="Environnement" color="lavender">Surconsommation serveur, obsolescence matérielle, bande passante inutile</Card>
  <Card title="Social" color="magenta">Exclusion des personnes en situation de handicap, fracture numérique</Card>
  <Card title="Éthique" color="violet">Biais algorithmiques, surveillance, manipulation de l'attention</Card>
  <Card title="Professionnel" color="white">Dette technique, dépendance à des solutions propriétaires</Card>
</div>

<InrBox>Le numérique n'est pas immatériel : chaque fonctionnalité inutile a un coût environnemental.</InrBox>
