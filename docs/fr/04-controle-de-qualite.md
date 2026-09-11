# Controle de qualite

Commencer par conserver les fichiers bruts et calculer une empreinte avant transformation.
Verifier unicite des lignes, ordre temporel, valeurs negatives et coherence px fois sz avec ntl.
Comparer les bornes temporelles des trois fichiers avant de croiser trades et liquidations.
Documenter fuseau horaire, precision decimale et politique d arrondi dans chaque analyse.
Les montants notionnels ne doivent pas etre additionnes a des flux de ledger sans definition commune.
Un echantillon manuel aide a reperer inversions de signe ou confusion base et quote.
Les resultats derives doivent rester reproductibles depuis les CSV sources immuables.

Suite : [05 — Limites et verification](05-limites-et-verification.md).
