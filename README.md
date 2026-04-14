# BEER/ME
### *Brew it like you know it.*

> **B**rew **E**asily **E**very **R**ecipe, **M**onitor **E**verything

---

## Le problème

Il est 7h, le brassin commence.

*Où est la recette ? Est-ce que je l'ai imprimée hier ? On est à jour sur les dosages ? C'est combien de kilos de houblon pour le hopstand ?*

À chaque brassin, on se disperse entre un logiciel de création de recettes, un tableau Excel de reporting, une feuille imprimée pour la journée, un carnet pour le suivi de fermentation.

Résultat : perte d'information, manque de reproductibilité, et une recette qu'on ne maîtrise jamais vraiment.

---

## La solution

**BEER/ME** centralise tout ce qui se passe *après* la création de recette.
Une seule app, utilisable même avec des gants, sur mobile, tablette ou desktop.

---

## Public cible

Du homebrewer passionné à la brasserie artisanale — tous ceux qui veulent améliorer la qualité de leurs brassins et la reproductibilité de leurs recettes.

---

## Fonctionnalités

### 🟠 Mode Brassin
Après avoir importé ou saisi manuellement une recette, le brasseur suit sa journée en temps réel :
- Suivi des étapes et du timing
- Modification de la recette en cours (ajouts, suppressions ou remplacement d'ingrédients)
- Reporting des événements (prises de densité, surchauffe, problème de filtration...)

### 🌡️ Suivi de fermentation
Une fois la bière en fermenteur :
- Saisie des relevés de densité et température
- Courbe d'évolution générée automatiquement
- Comparaison avec les attentes de la recette

---

## Charte graphique

- Design épuré et professionnel
- Palette blanc/gris + orangé — rappel de la bière, sans en faire trop
- Boutons identifiables, lisibles, avec couleur d'accent claire

---

## Stack technique

| Couche          | Choix                          |
|-----------------|--------------------------------|
| Frontend        | React + TypeScript + Tailwind  |
| PWA             | Vite PWA plugin                |
| Backend         | Node.js + Express              |
| Base de données | PostgreSQL                     |
| Auth            | JWT                            |
| Dataviz         | Recharts                       |

---

*Conçu par un ancien brasseur, pour les brasseurs.*
