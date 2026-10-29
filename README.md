# ExempleSitedeCours

Site de base du département, fait avec [Quarto](https://quarto.org) et publié sur GitHub Pages.

## Structure

| Fichier / dossier          | Rôle                                         |
|----------------------------|----------------------------------------------|
| `_quarto.yml`              | Configuration du site (titre, menu)          |
| `index.qmd`                | Page d'accueil                               |
| `calendrier.qmd`           | Calendrier (un tableau à modifier)           |
| `documents.qmd`            | Liste des documents                          |
| `documents/`               | Les fichiers PDF                             |
| `.github/workflows/`       | Publication automatique                      |

## Modifier le site

- **Ajouter une date** : dans `calendrier.qmd`, copier une ligne du tableau et la modifier.
- **Ajouter un PDF** : déposer le fichier dans `documents/`, puis ajouter une ligne
  `- [Titre](documents/fichier.pdf)` dans `documents.qmd`.

Tout peut se faire directement dans l'interface de GitHub (bouton « Add file » ou crayon).
Chaque modification poussée sur `main` republie le site en 1 à 2 minutes.

## Première mise en ligne (une seule fois)

Dans le dépôt : **Settings → Pages → Build and deployment → Source : GitHub Actions**.

## Voir le site en local (optionnel)

```bash
quarto preview
```
