Réponses aux questions bonus

Question 15 : Qu'est-ce qu'un conflit de merge ?
Un conflit de merge arrive quand deux branches modifient la même ligne du même fichier : Git ne sait pas laquelle garder. On le résout en ouvrant le fichier, en choisissant le bon contenu entre les marqueurs <<<<<<< et >>>>>>>, puis en faisant git add et git commit.

Question 24 : Pourquoi une Pull Request plutôt qu'un push direct ?
Une Pull Request permet à l'équipe de relire et discuter le code avant son intégration. Cela évite d'introduire des bugs directement dans la branche principale.
