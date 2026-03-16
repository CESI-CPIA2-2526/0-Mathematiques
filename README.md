# Mathématiques - CCTLs Blancs et Fiches de Révision

- **Formation** : CPIA2 Informatique
- **Année universitaire** : 2025 / 2026
- **Établissement** : CESI

---

## Présentation

Ce dépôt regroupe l'ensemble des ressources pédagogiques produites pour les Contrôles de Connaissances et de Travaux en Loge (CCTLs) blancs de mathématiques de la promotion CPIA2 Info 2025/2026.

Les documents couvrent trois thèmes fondamentaux du programme :

- Fonctions de plusieurs variables
- Opérateurs vectoriels (gradient, divergence, rotationnel, laplacien)
- Équations différentielles ordinaires et intégrales doubles

Chaque thème dispose d'un sujet QCM, d'un corrigé détaillé et d'une fiche de révision synthétique.

---

## Structure du dépôt

```
.
├── sujets/                          Sujets des épreuves
│   ├── qcm-fonctions-plusieurs-variables-et-operateurs-vectoriels.tex/.pdf
│   ├── qcm-equadiff-integrales.tex/.pdf
│   └── qcm-unique.tex/.pdf          Épreuve de synthèse (35 pts, 1h)
│
├── corriges/                        Corrigés pédagogiques détaillés
│   ├── corrige-fonctions-plusieurs-variables-et-operateurs-vectoriels.tex/.pdf
│   ├── corrige-equadiff-integrales.tex/.pdf
│   └── corrige-qcm-unique.tex/.pdf
│
└── fiches-revision/                 Fiches de révision synthétiques
    ├── fiche-revision-fonctions-plusieurs-variables.tex/.pdf
    ├── fiche-revision-operateurs-vectoriels.tex/.pdf
    ├── fiche-revision-equadiff.tex/.pdf
    └── fiche-revision-integrales.tex/.pdf
```

---

## Contenu des épreuves

### Fonctions de plusieurs variables & Opérateurs vectoriels

| Thème | Notions abordées |
|---|---|
| Limites et continuité | Définition, méthode des chemins, non-existence |
| Différentielle et plan tangent | Différentielle totale, règle de la chaîne, Schwartz |
| Dérivées partielles | Dérivées d'ordre 1 et 2, théorème de Clairaut-Schwartz |
| EDP classiques | Équation des ondes, chaleur, Laplace |
| Extrema | Points critiques, discriminant hessien, classification |
| Opérateurs vectoriels | Gradient, divergence, rotationnel, laplacien |
| Applications géométriques | Vecteur normal, plan tangent à une surface implicite |

### Équations différentielles & Intégrales

| Thème | Notions abordées |
|---|---|
| EDO du 1er ordre | Linéaires homogènes et avec second membre, séparables |
| EDO du 2e ordre | Équation caractéristique, racines réelles/double/complexes |
| Intégrales doubles | Fubini, coordonnées polaires, changement de variables |

### Épreuve de synthèse (QCM unique)

Épreuve transversale de 30 questions (25 QCM + 5 questions de calcul) couvrant l'ensemble des thèmes ci-dessus. Durée : 1 heure. Barème : 1 pt par QCM, 2 pts par calcul, total 35 pts.

---

## Format des documents

Tous les documents sont rédigés en **LaTeX** et compilés en PDF.

### Structure des corrigés

Chaque corrigé suit une structure pédagogique uniforme :

- **Grille de correction rapide** : tableau récapitulatif de toutes les réponses
- **Justification par question** : énoncé rappelé, réponse correcte mise en évidence, analyse de chaque proposition
- **Boîtes méthodologiques** : rappels de cours et formules clés
- **Boîtes de calcul** : développement complet étape par étape
- **Boîtes pièges** : erreurs fréquentes et points de vigilance
- **Page de synthèse** : tableaux récapitulatifs des méthodes à retenir

### Compilation

Les fichiers `.tex` nécessitent une distribution LaTeX complète (MiKTeX ou TeX Live) avec les packages suivants : `amsmath`, `amssymb`, `geometry`, `enumitem`, `multicol`, `xcolor`, `mdframed`, `titlesec`, `fancyhdr`, `booktabs`, `microtype`.

```bash
pdflatex nom-du-fichier.tex
```

---

## Licence

Ces ressources sont destinées à un usage pédagogique interne à la promotion CPIA2 Info 2025/2026 du CESI.
Toute redistribution ou réutilisation hors de ce cadre doit faire l'objet d'une autorisation préalable.
