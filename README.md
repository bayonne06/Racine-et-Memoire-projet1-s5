# Racine-et-Memoire-projet1-s5

## Participants

Le travail de chacun était commité et poussé sur sa branche personnelle, puis proposé via une Pull Request vers `main`.

## Protection de la branche `main`

Aucun push direct n'était autorisé. Tous les changements passaient par une Pull Request avec **au moins une review approuvée** avant de pouvoir être fusionnés.

## Gestion des conflits

### 1. Conflit dans `README.md`

Un conflit est survenu car deux versions du fichier contenaient des informations différentes. Nous l'avons résolu en conservant les deux contenus complémentaires.

### 2. Conflit dans `css/style.css`

Le conflit le plus important concernait le fichier CSS partagé. Plusieurs membres de l'équipe modifiaient `style.css` pour styliser des pages différentes. Git ne pouvait donc pas fusionner automatiquement ces modifications.

Après une résolution manuelle, certains sélecteurs généraux (`*`, `body`, `header`, etc.) étaient définis plusieurs fois et certains styles s'écrasaient silencieusement, sans que Git ne signale de nouveau conflit.

**Solution adoptée :** créer un fichier CSS dédié à chaque page afin d'éviter les conflits et de mieux organiser le projet.
