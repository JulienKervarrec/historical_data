# Perimetre des donnees

Le depot publie trois instantanes CSV destines a des visualisations historiques du DEX.
non_mm_trades conserve les echanges dont au moins une contrepartie n est pas market maker.
liquidations isole les evenements de liquidation observes dans la periode couverte.
non_mm_ledger_updates decrit depots et retraits en excluant les market makers.
Le sigle mm suit ici une definition operationnelle propre au jeu de donnees.
Un market maker est une adresse depassant 100 millions USD de notionnel sur trente jours.
Cette convention doit etre citee avant toute comparaison avec une autre source.

Suite : [02 — Lire les colonnes](02-lire-les-colonnes.md).
