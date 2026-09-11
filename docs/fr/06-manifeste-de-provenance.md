# 6 — Manifeste de provenance

Une analyse reproductible commence par un manifeste liant chaque fichier à sa source.
Il enregistre la plage temporelle, le type de données, la date d’acquisition et une empreinte du fichier.
Le numéro de bloc ou la séquence doit accompagner l’horodatage lorsque la source le permet.
Les paramètres de requête et la version du schéma évitent de comparer des extractions incompatibles.
Un fichier partiel reste exploitable si son incomplétude est déclarée et bornée.
Les transformations dérivées doivent conserver le lien vers les entrées brutes, jamais les remplacer silencieusement.
Ce manifeste permet de distinguer correction des données et changement de méthodologie.

Suite : [précision et déduplication](07-precision-et-deduplication.md).
