---
layout: section
num: 1
color: blue
duration: 55 min
objective: Objectif 1
---

# Open source et licences

Valeurs, licences, responsabilité collective

---
layout: statement
---

# Open source = gratuit ?

<Sticker color="lime">Vrai ou faux ?</Sticker>

---

# Un peu d'histoire

<div class="nb-small">

| Année | Événement |
|---|---|
| 1983 | Richard Stallman lance le projet **GNU** : un système d'exploitation entièrement libre |
| 1985 | Création de la **Free Software Foundation** (FSF) |
| 1989 | Première version de la **GNU GPL**, la licence copyleft de référence |
| 1991 | Linus Torvalds publie le noyau **Linux** (passé sous GPL en 1992) |
| 1998 | Le terme **« open source »** est adopté, création de l'**Open Source Initiative** (OSI) |
| 2004 | **Apache 2.0**, licence permissive avec clause de brevets |
| 2007 | **GPLv3** et **AGPLv3** |
| 2019 | Mouvement **Ethical Source** et Hippocratic License |

</div>

<Source href="https://www.gnu.org/philosophy/free-sw.fr.html">GNU · Qu'est-ce que le logiciel libre ?</Source>

---

# Logiciel libre ou open source ?

<div class="nb-grid-2">
<Card title="Logiciel libre · FSF" color="violet">

Une **philosophie** : 4 libertés fondamentales pour l'utilisateur

0. **Exécuter** le programme, pour tous les usages
1. **Étudier** son fonctionnement et le **modifier**
2. **Redistribuer** des copies
3. **Distribuer** des versions modifiées

*« Free as in freedom, not as in free beer »*

</Card>
<Card title="Open source · OSI" color="blue">

Une **méthode de développement** : une définition en 10 critères (Open Source Definition)

- Redistribution libre
- Code source accessible
- Travaux dérivés autorisés
- **Pas de discrimination** envers des personnes ou des **domaines d'activité**
- …

</Card>
</div>

<Source href="https://opensource.org/osd">Open Source Initiative · The Open Source Definition</Source>

<!-- En pratique, les licences sont presque toutes les mêmes. La différence est dans le discours : la liberté de l'utilisateur d'un côté, l'efficacité du développement ouvert de l'autre. -->

---

# Open source ≠ gratuit

<div class="nb-split">
<div>

| Freeware | Open source |
|---|---|
| Code fermé | Code ouvert |
| Gratuit à l'usage | Gratuit ou payant |
| Peu de libertés | Libertés garanties |
| Dépendance à l'éditeur | Indépendance possible |

</div>
<div>

Un logiciel peut être :

- **gratuit mais propriétaire** : Adobe Acrobat Reader, WhatsApp, la plupart des apps mobiles
- **open source mais payant** : support, hébergement, services, version entreprise (Red Hat, GitLab, WordPress.com…)

</div>
</div>

---

# Les valeurs fondatrices

<div class="nb-grid-2 mt-4 nb-small">
  <Card title="🔍 Transparence" color="blue">Le code est lisible, les décisions sont visibles, les comportements cachés sont limités. Enjeu : confiance et <strong>auditabilité</strong> (sécurité, RGPD, Green IT).</Card>
  <Card title="🤝 Intelligence collective" color="lime">Contributions multiples, relecture par les pairs, amélioration continue. Plus de regards : moins de bugs, moins de dérives.</Card>
  <Card title="🛡️ Autonomie et résilience" color="lavender">Pas de dépendance totale à un éditeur, auto-hébergement possible, continuité même si un acteur disparaît. Une dimension <strong>politique</strong> du numérique.</Card>
  <Card title="📚 Bien commun" color="magenta">Le code se transmet, on apprend en le lisant, le savoir se capitalise. Mutualiser plutôt que reproduire inutilement.</Card>
</div>

---

# Pourquoi une licence ?

<div class="nb-split nb-split-l">
<div>

Une licence définit :

- ce que vous avez **le droit** de faire
- ce que vous **devez** faire
- ce que vous **n'avez pas le droit** de faire

</div>
<Card title="⚠️ Pas de licence ?" color="magenta">

Par défaut, le **droit d'auteur** s'applique : **tous droits réservés**.

Un dépôt public sans fichier `LICENSE` est visible… mais **juridiquement inutilisable**.

</Card>
</div>

> Lire une licence est un acte professionnel. Ignorer une licence est une faute éthique et juridique.

<Source href="https://choosealicense.com/no-permission/">choosealicense.com · No License</Source>

---

# Le spectre des licences

<div class="nb-spectrum mt-6">
  <div class="nb-fill-lime"><strong>Domaine public</strong><span>CC0, Unlicense</span></div>
  <div class="nb-fill-blue"><strong>Permissives</strong><span>MIT, BSD, Apache 2.0</span></div>
  <div class="nb-fill-lavender"><strong>Copyleft faible</strong><span>LGPL, MPL 2.0</span></div>
  <div class="nb-fill-violet"><strong>Copyleft fort</strong><span>GPL</span></div>
  <div class="nb-fill-magenta"><strong>Copyleft réseau</strong><span>AGPL</span></div>
  <div class="nb-fill-navy"><strong>Propriétaire</strong><span>tous droits réservés</span></div>
</div>

<div class="nb-spectrum-axis">
  <span>← Liberté maximale pour qui réutilise</span>
  <span>Protection maximale du bien commun →</span>
</div>

<div class="nb-split nb-split-l mt-6" style="align-items: start;">
<Card title="📖 Copyleft : définition" color="white" class="nb-copyleft">

Mécanisme qui **utilise le droit d'auteur pour garantir la liberté** du logiciel : qui redistribue le logiciel, modifié ou non, doit le faire **sous la même licence** et **avec son code source**. Jeu de mots sur *copyright* : « tous droits réservés » devient « tous droits renversés ».

</Card>
<div class="nb-small">

Hors du spectre open source : les licences **« source available »** (BSL, SSPL, Elastic License) montrent le code mais restreignent son usage commercial.

🔗 [GNU · Qu'est-ce que le copyleft ?](https://www.gnu.org/licenses/copyleft.fr.html)

</div>
</div>

<style>
.nb-spectrum {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  border: var(--nb-border);
  box-shadow: var(--nb-shadow);
}
.nb-copyleft p { font-size: 0.9rem !important; line-height: 1.45; }
.nb-spectrum > div {
  padding: 0.6rem 0.6rem;
  display: flex;
  flex-direction: column;
  gap: 0.3rem;
  font-size: 0.95rem;
}
.nb-spectrum > div + div { border-left: var(--nb-border); }
.nb-spectrum strong { background: none; color: inherit; font-family: 'Archivo Black', sans-serif; font-weight: 400; }
.nb-spectrum span { font-size: 0.8rem; }
.nb-spectrum-axis { display: flex; justify-content: space-between; margin-top: 0.8rem; font-weight: 700; font-size: 0.9rem; }
</style>

---

# MIT · « Faites ce que vous voulez »

<div class="nb-split">
<div class="nb-small">

**Vous pouvez** : usage personnel et commercial, modification, redistribution, intégration dans un logiciel propriétaire.

**Vous devez** : conserver la mention de copyright et le texte de la licence.

**Garantie** : aucune. Le logiciel est fourni « tel quel ».

Utilisée par : React, Vue.js, Node.js, jQuery, Rails…

</div>
<div>
<Card title="Avantages" color="lime">Liberté maximale, diffusion large, adoption facile en entreprise</Card>
<Card title="Limites" color="magenta" class="mt-4">Pas d'obligation de contribuer en retour, risque d'appropriation privée</Card>
</div>
</div>

> Choix éthique : **liberté individuelle** > bien commun

<Source href="https://choosealicense.com/licenses/mit/">choosealicense.com · MIT</Source>

---

# Apache 2.0 · MIT + brevets

<div class="nb-split nb-small">
<div>

Même philosophie permissive que MIT, avec en plus :

- une **licence explicite sur les brevets** : les contributeurs vous accordent l'usage de leurs brevets liés au code
- une **clause de riposte** : si vous attaquez en justice pour brevet, vous perdez cette licence
- l'obligation de **signaler les fichiers modifiés** et de conserver le fichier `NOTICE`

Utilisée par : Kubernetes, Android (AOSP), TypeScript, Kafka…

</div>
<Card title="Pourquoi c'est important ?" color="blue">

Une entreprise qui publie du code sous MIT pourrait, en théorie, poursuivre ensuite ses utilisateurs pour violation de brevet.

Apache 2.0 ferme cette porte : c'est la licence permissive préférée des grandes entreprises.

</Card>
</div>

<Source href="https://choosealicense.com/licenses/apache-2.0/">choosealicense.com · Apache 2.0</Source>

---

# GPL · « Faites, mais partagez »

<div class="nb-split nb-small">
<div>

**Copyleft fort** : si vous **distribuez** un logiciel qui intègre du code GPL, l'ensemble doit être distribué **sous GPL**, avec son code source.

**Vous devez** : fournir le code source, partager vos modifications, conserver la licence.

**Protège** : le code ne peut pas être refermé. Chaque amélioration revient au bien commun.

Utilisée par : le noyau Linux (GPLv2), Git, WordPress, GIMP…

</div>
<div>
<Card title="Avantage · limite" color="lime">

- ✅ Protège le bien commun
- ⚠️ Moins attractive pour les entreprises qui ne veulent pas ouvrir leur code

</Card>
<Card title="🕳️ La faille SaaS" color="magenta" class="mt-4">Un service web n'est pas « distribué » : on peut modifier du code GPL côté serveur sans rien publier.</Card>
</div>
</div>

<Source href="https://choosealicense.com/licenses/gpl-3.0/">choosealicense.com · GPLv3</Source>

---

# Copyleft faible et copyleft réseau

<div class="nb-grid-2 nb-small">
<Card title="LGPL · MPL 2.0 · copyleft faible" color="lavender">

Le copyleft s'arrête **à la bibliothèque** (LGPL) ou **au fichier** (MPL).

Un logiciel propriétaire peut **utiliser** la bibliothèque. Les **modifications de la bibliothèque** elle-même doivent être partagées.

Utilisée par : Firefox (MPL 2.0), glibc et Qt (LGPL).

</Card>
<Card title="AGPL · copyleft réseau" color="magenta">

Ferme la faille SaaS : **offrir le logiciel via le réseau** équivaut à le distribuer.

Les utilisateurs du service doivent pouvoir obtenir **le code source**, modifications comprises.

Utilisée par : Mastodon, Nextcloud, Grafana.

</Card>
</div>

<Source href="https://choosealicense.com/licenses/">choosealicense.com · comparatif des licences</Source>

---

# Comparatif

<div class="nb-small">

| | Usage commercial | Modifier | Intégrer dans du propriétaire | Partager ses modifs | Brevets |
|---|---|---|---|---|---|
| **MIT** | ✅ | ✅ | ✅ | ❌ non requis | ⚪ implicite |
| **Apache 2.0** | ✅ | ✅ | ✅ | ❌ non requis | ✅ explicite |
| **LGPL / MPL** | ✅ | ✅ | ✅ en l'utilisant | ✅ pour la lib / le fichier | ✅ (v3 / 2.0) |
| **GPLv3** | ✅ | ✅ | ❌ | ✅ si distribué | ✅ explicite |
| **AGPLv3** | ✅ | ✅ | ❌ | ✅ même en SaaS | ✅ explicite |

</div>

<div class="mt-3 nb-small">

Il n'existe pas de « meilleure » licence universelle : il existe un **contexte**, des **valeurs** et des **objectifs**.

</div>

<Source href="https://www.tldrlegal.com/">tldrlegal.com · les licences en langage clair</Source>

---

# La compatibilité : un sens unique

<div class="nb-split">
<div>

On peut intégrer du code **plus permissif** dans un projet **plus protecteur**, pas l'inverse.

- Code **MIT** → dans un projet **GPL** : ✅
- Code **Apache 2.0** → dans un projet **GPLv3** : ✅ (mais pas en GPLv2)
- Code **GPL** → dans un projet **MIT** : ❌ l'ensemble devient GPL
- Code **GPL** → dans un logiciel propriétaire distribué : ❌

</div>
<Card title="💡 En pratique" color="lime">

Avant d'ajouter une dépendance, **vérifiez sa licence**.

Utilisez les identifiants [SPDX](https://spdx.org/licenses/) (`MIT`, `GPL-3.0-or-later`…) dans vos `package.json`, `pom.xml` ou `pyproject.toml`, et un outil d'analyse de licences dans votre CI.

</Card>
</div>

---

# Et pour le contenu ? Creative Commons

<div class="nb-split nb-split-l">
<div class="nb-small">

Les licences **Creative Commons** s'appliquent aux textes, images, vidéos, cours. Elles combinent 4 briques :

- **BY** · Attribution : citer l'auteur
- **SA** · Partage à l'identique : même licence pour les dérivés
- **NC** · Pas d'utilisation commerciale
- **ND** · Pas de modification

Creative Commons **déconseille** ses licences pour le code : utilisez une licence logicielle.

</div>
<Card title="🪞 Cas pratique : ce cours" color="blue">

La séquence 3 reprend le contenu de l'Académie NR, sous licence **CC BY-NC-ND 4.0**.

- **BY** : la source est citée sur chaque slide
- **ND** : textes et visuels repris sans modification
- **NC** : ce cours est-il un usage commercial ? **Débattons-en.**

</Card>
</div>

<Source href="https://creativecommons.org/licenses/by-nc-nd/4.0/deed.fr">Creative Commons · BY-NC-ND 4.0</Source>

---

# Quand une licence change

<div class="nb-small">

| Projet | Changement | Réaction de la communauté |
|---|---|---|
| **Elasticsearch** (2021) | Apache 2.0 → SSPL / Elastic License | Fork **OpenSearch** (AWS) |
| **Terraform** (2023) | MPL 2.0 → BSL | Fork **[OpenTofu](https://opentofu.org/)** (Linux Foundation) |
| **Redis** (2024) | BSD → RSAL / SSPL | Fork **[Valkey](https://valkey.io/)** (Linux Foundation) |

</div>

<div class="nb-grid-2 mt-4">
  <Card title="Leur argument" color="white">Des géants du cloud revendent notre travail en service managé sans contribuer.</Card>
  <Card title="La critique" color="white">Les contributeurs ont donné leur code sous une licence ouverte : le refermer rompt le contrat moral.</Card>
</div>

<div class="mt-3 nb-small">

Elastic (2024) et Redis (2025) ont depuis **ajouté l'AGPL** à leurs options de licence.

</div>

---

# Responsable de ses dépendances

<div class="nb-grid-2 nb-small">
  <Card title="2016 · left-pad" color="lime">Azer Koçulu retire de npm un paquet de 11 lignes. Des milliers de builds cassent, dont React et Babel. <a href="https://en.wikipedia.org/wiki/Npm_left-pad_incident">↗</a></Card>
  <Card title="2021 · Log4Shell" color="magenta">Faille critique dans Log4j, bibliothèque Java maintenue par quelques bénévoles, présente dans des millions de systèmes. <a href="https://nvd.nist.gov/vuln/detail/CVE-2021-44228">↗</a></Card>
  <Card title="2022 · colors.js / faker.js" color="lavender">Le mainteneur sabote ses propres paquets pour protester contre l'usage gratuit par les grandes entreprises.</Card>
  <Card title="2024 · xz-utils" color="blue">Une porte dérobée est introduite après des années de manipulation d'un mainteneur seul et épuisé. Découverte par hasard. <a href="https://nvd.nist.gov/vuln/detail/CVE-2024-3094">↗</a></Card>
</div>

<div class="mt-3 nb-small">

Qui maintient ce dont vous dépendez ? 🔗 [xkcd 2347 · Dependency](https://xkcd.com/2347/)

</div>

---

# 🔍 Chasse aux licences

<div class="nb-split">
<Card title="Consigne · 10 min" color="blue">

1. Choisissez un projet sur GitHub que vous utilisez
2. Trouvez le fichier `LICENSE`
3. Permissive ou copyleft ?
4. Puis-je l'utiliser en entreprise ? Le modifier ? Le vendre ?
5. Ce choix vous semble-t-il éthique ?

</Card>
<div class="nb-small">

**Outils**

- [choosealicense.com](https://choosealicense.com/) : choisir et comprendre une licence
- [tldrlegal.com](https://www.tldrlegal.com/) : les licences résumées en langage clair
- [spdx.org/licenses](https://spdx.org/licenses/) : la liste officielle des identifiants

**Bonus** : combien de licences différentes dans le `node_modules` de votre projet ?

</div>
</div>

---

# ⚖️ Dilemme

> Vous développez une librairie PHP très performante. Une grande entreprise veut l'utiliser **sans contribuer**.

<div class="nb-grid-2 mt-6">
  <Card title="MIT ?" color="lime">Liberté individuelle, adoption maximale</Card>
  <Card title="GPL ? AGPL ?" color="magenta">Bien commun, réciprocité obligatoire</Card>
</div>

<div class="mt-6 nb-small">

**Quel est l'impact à long terme ? Qui protège qui ?** Il n'y a pas de bonne réponse universelle, seulement des choix argumentés.

</div>

---

# Contribuer, ce n'est pas que coder

<div class="nb-split">
<div>

Démarche classique : **fork → clone → modification → commit → pull request**

Mais on peut aussi contribuer par :

- 📝 la **documentation**
- 🌍 la **traduction**
- 🧪 les **tests** et les rapports de bugs
- 🗂️ le **tri des issues**
- 📣 la **diffusion**
- 💶 le **financement** (GitHub Sponsors, Open Collective)

</div>
<Card title="Responsabilités du contributeur" color="blue">

- respecter la licence
- respecter la communauté et son code de conduite
- documenter ses choix
- ne pas introduire volontairement de dette technique
- penser à la maintenabilité

</Card>
</div>

---

# À retenir

<div class="nb-grid-2 nb-small">
<div>

- L'open source est un **choix éthique**
- **Gratuit ≠ open source**
- Les licences sont des **contrats moraux et juridiques**
- Contribuer, c'est aussi **respecter**
- Le/la dév est **responsable de ses dépendances**

</div>
<InrBox>

- **Mutualiser** plutôt que reproduire inutilement
- **Résilience** des organisations (axe 4 du NR)
- **Réutiliser** : un des 5R

</InrBox>
</div>

<div class="mt-8"><Sticker color="white">✍️ 1 engagement pour ma charte</Sticker></div>
