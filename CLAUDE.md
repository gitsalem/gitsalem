# gitsalem — profil GitHub

## Projet

README du profil GitHub public (github.com/gitsalem).

## Contenu

- `header.svg` — bannière SALEM uppercase, monochrome noir/blanc
- `README.md` — badges monochrome (fond #000000, icônes #ffffff), catalogue de builds

## DA

Monochrome — noir pur `#000000`, blanc `#ffffff`.

## Format des badges (toujours respecter)

```md
![Nom](https://img.shields.io/badge/Nom-000000?style=flat-square&logo=LOGO&logoColor=ffffff)
```

- **CONTACT** : badge cliquable `[![Nom](badge)](url)`
- **SKILLSETS** : badge non-cliquable `![Nom](badge)`
- **BUILDS** : badge cliquable `[![nom-du-site](badge)](url)` — lien seul, pas de stack

## Règle AUTOMATIQUE

À la fin de chaque session de travail sur n'importe quel projet :
1. Mettre à jour `README.md` — ajouter les nouveaux skills dans SKILLSETS, ajouter le projet dans BUILDS si c'est un nouveau build live
2. Mettre à jour ce fichier CLAUDE.md en conséquence
3. Commit + push sur gitsalem/gitsalem
