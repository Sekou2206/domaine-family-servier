# Domaine Family Servier

Maquette du site de l’élevage Domaine Family Servier (bergers australiens, Aube), proposition Lignée avec l’arbre généalogique des chiens.

## Lancer en local

```bash
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000

## Arbre généalogique

Dans `index.html`, les chiens sont décrits dans l’objet `CHIENS` (nom, robe, yeux, LOF, photo, père, mère) et les portées dans `PORTEES`. Remplir un champ suffit : l’arbre, les fiches et la version mobile se mettent à jour seuls.

## Mettre en ligne avec GitHub Pages

Settings › Pages › Deploy from a branch › `main` / `root`.

Réalisé par SC Projet · https://scproject.tech/
