# 7 — Précision, unités et déduplication

Les prix, tailles et notionnels doivent rester dans une représentation décimale exacte jusqu’au calcul final.
Convertir trop tôt en flottant binaire peut modifier agrégats, seuils et comparaisons d’égalité.
Chaque colonne doit annoncer son unité, son échelle et la convention de signe.
La clé de déduplication combine les identifiants stables disponibles, plutôt qu’un seul horodatage.
Deux lignes identiques après arrondi ne sont pas nécessairement un doublon économique.
Les contrôles mesurent lignes rejetées, collisions de clés et perte maximale due à l’arrondi.
Un agrégat publié doit préciser la politique appliquée aux corrections et répétitions.

Suite : [alignement temporel](08-alignement-temporel.md).
