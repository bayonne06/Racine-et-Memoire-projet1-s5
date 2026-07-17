# Racine-et-Memoire-projet1-s5
Racines &amp; Mémoire est une association fictive dédiée à la préservation et à la transmission du patrimoine culturel congolais : traditions orales, musique, artisanat ancestral et langues locales. Sa mission est de sensibiliser les jeunes générations à la richesse de ce patrimoine et de le documenter avant qu'il ne se perde.

# participants:
Goma Ketsia (lead)--- branche actions;
Mavoungou Bayonne Précieux (repo admin) --- branche contacts-et-don;
Owala Brichelvie Jeannelle --- branche acceuil;
Elenga Messi Soleil --- branche EVENEMENT;
Bazoungoula Bonheur Amour Parfait --- footer;

Le travail de chacun était commité et poussé sur sa branche personnelle, puis proposé via une Pull Request vers  main.

# protection de la pbranche main
Aucun push direct n'est , tout changement  sont  passer par une Pull Request avec **au moins une review approuvée** avant de pouvoir merger.

# Gestion des conflit

1- Dans le fichier README.md:
Un conflit est survenu car deux versions du fichier contenaient des informations différentes. Nous l'avons resolu en conservant les deux contenus complémentaires.

2- Dans 'css/style.css:

Le conflit le plus important : Les membres  de l'équipe modifiaient le même fichier CSS partagé pour styliser des pages différentes. Du coup,  Git ne pouvait pas fusionner automatiquement, On a fallu le resoudre manuellement et une fois le conflit résolu manuellement, certains styles ( les sélecteurs comme *, body, header) se redéclaraient et s'écrasaient silencieusement entre les pages, sans que Git ne signale de problème.
Pour resoudre ce probleme : un fichier CSS dédié par page.

