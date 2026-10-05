# Planning des repas

Page web autonome pour planifier les repas de la famille : 7 jours, midi et soir, avec une liste de plats à glisser-déposer.

## Fonctionnalités

- Grille lundi–dimanche, midi et soir, jusqu'à 2 plats par repas
- Liste de plats par ordre alphabétique, avec recherche
- Navigation de semaine en semaine, bouton « Reprendre repas S-1 »
- Thème clair par défaut, interrupteur clair / sombre
- Utilisable au toucher sur téléphone (toucher un plat, puis un créneau)

## Utilisation

Ouvrir `index.html` dans un navigateur. Aucune installation, aucun serveur.

Hors de Claude, le planning est enregistré dans le navigateur (`localStorage`), semaine par semaine. Il n'est donc pas partagé entre appareils. La version publiée comme artifact Claude partage le planning entre ses utilisateurs.

## Modifier la liste des plats

Les plats sont définis dans le tableau `DISHES` du script de `index.html` (nom + ligne « Légumes »). La liste s'affiche automatiquement par ordre alphabétique.
