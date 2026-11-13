# Domaine Family Servier

Maquettes du site de l’élevage Domaine Family Servier (bergers australiens, Aube), en quatre propositions d’identité.

| Proposition | Dossier |
| --- | --- |
| Lignée (Héritage et Vairon, avec arbre généalogique) | `lignee/` |
| Héritage | `heritage/` |
| Vairon | `vairon/` |
| Houlette | `houlette/` |

La page `index.html` à la racine présente les quatre propositions.

## Arbre généalogique

Dans `lignee/index.html`, les chiens sont décrits dans l’objet `CHIENS` (nom, robe, yeux, LOF, photo, père, mère) et les portées dans `PORTEES`. Remplir un champ suffit : l’arbre, les fiches et la version mobile se mettent à jour seuls.

## Lancer en local

```bash
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000

## Mettre en ligne avec GitHub Pages

Settings › Pages › Deploy from a branch › `main` / `root`.

Réalisé par SC Projet · https://scproject.tech/
