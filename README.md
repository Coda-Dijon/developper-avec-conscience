# Développer avec conscience : éthique, open source et impact

Support de cours (6h) réalisé avec [Slidev](https://sli.dev), style neobrutal.

## Démarrer

```bash
npm install
npm run dev      # présentation sur http://localhost:3030
npm run build    # version statique dans dist/
npm run export   # export PDF (nécessite playwright-chromium)
```

## Structure

```
slides.md              # couverture, programme, objectifs + import des séquences
pages/                 # une page par séquence (00 à 06)
components/            # composants neobrutal réutilisables
layouts/section.vue    # slide d'ouverture de séquence
styles/index.css       # thème neobrutal (couleurs, bordures, ombres)
public/images/         # images optimisées en WebP (inr/, ethics/, tarot/)
docs/plan.md           # plan pédagogique détaillé
```

## Composants

| Composant | Usage |
|---|---|
| `<Card title="..." color="magenta" tilt="l">` | Boîte avec bordure et ombre portée |
| `<Sticker color="blue" :rotate="3">` | Étiquette inclinée |
| `<InrBox title="...">` | Encart « 🌱 Fil INR » présent dans chaque séquence |
| `<Quiz question="..." :options="[...]" :answer="1" source="..." />` | QCM, réponse révélée au clic (ajouter `clicks: 1` dans le frontmatter) |
| `<Figure src="/images/..." alt="..." caption="..." h="18rem" bare tilt="l" />` | Image encadrée. `alt` obligatoire. `bare` retire le cadre (illustrations détourées) |
| `<Source inr />` | Crédit Académie NR (CC BY-NC-ND 4.0) en bas de slide |
| `<Source href="https://...">Nom</Source>` | Crédit d'une autre source, avec lien |

Classes de mise en page : `nb-split` (2 colonnes), `nb-split-l` / `nb-split-r` (colonne gauche ou droite plus large), `nb-grid-2`, `nb-grid-3`, `nb-center`, `nb-small` (texte et tableaux plus petits).

Couleurs disponibles (palette Coda) : `navy`, `lime`, `magenta`, `violet`, `blue`, `lavender`, `white`.

## Palette et accessibilité

Thème **neobrutal sobre** inspiré de la palette Coda : fond blanc cassé, encre navy, cartes en teintes pastel et un seul accent vif, le lime Coda (`--nb-accent`), réservé aux traits sous les titres, au surlignage et à la bonne réponse des quiz.

Chaque couleur de fond est associée à une couleur de texte (`--nb-on-*`) qui respecte WCAG AA (≥ 4,5:1). Les composants appliquent ce couple automatiquement via les classes `nb-fill-*`.

| Nom | Fond | Texte | Contraste |
|---|---|---|---|
| `navy` | `#080331` | blanc | 19,7:1 |
| `violet` | `#2a1668` (violet profond) | blanc | 14,9:1 |
| `lime` | `#eef8b4` (teinte) | navy | 17,5:1 |
| `blue` | `#dfe4ff` (teinte) | navy | 15,6:1 |
| `lavender` | `#e7e2f6` (teinte) | navy | 15,6:1 |
| `magenta` | `#f8dcef` (teinte rose) | navy | 15,4:1 |
| `white` | `#ffffff` | navy | 19,7:1 |

L'accent lime pur `#ddf849` est invisible sur fond clair (1,1:1) : il n'est jamais utilisé seul, toujours cerné de navy ou posé sur du navy.

Autres règles :

- le quiz ne s'appuie pas sur la couleur seule (icône ✓, libellé « Bonne réponse » pour les lecteurs d'écran, mauvaises réponses barrées) ;
- chaque image a un texte alternatif (`alt` obligatoire dans `<Figure>`) ;
- les animations sont coupées si `prefers-reduced-motion` est activé.

## Slide de séquence

```md
---
layout: section
num: 3
color: lime
duration: 1h15
objective: Objectif 3
---

# Numérique responsable
```

## Code couleur des séquences

| Séquence | Couleur |
|---|---|
| 00 Ouverture | lavender |
| 01 Open source | blue |
| 02 Chartes | violet |
| 03 Numérique responsable | lime |
| 04 Impacts humains | magenta |
| 05 Posture | navy |
| 06 Clôture | lime |

## Images et licences

- `public/images/inr/` : visuels de l'Académie NR, sous licence **CC BY-NC-ND 4.0**. Ils sont repris sans modification (conversion WebP et redimensionnement uniquement) et la source est créditée sur chaque slide avec `<Source inr />`. Ne pas les recadrer ni les retoucher.
- `public/images/ethics/` : visuels du support « Developers ethics ».
- `public/images/tarot/` : cartes du [Tarot de la Tech](https://tarotcardsoftech.artefactgroup.com/) d'Artefact.
- `public/images/craftsman-*.webp` : infographie *The Software Craftsman* (Yoan Thirion).

Les images sont converties en WebP (1200 px max) pour limiter le poids du deck.
