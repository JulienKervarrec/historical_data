# 8 — Alignement temporel et reproductibilité

Les flux de trades, carnets, financements et blocs n’avancent pas toujours au même rythme.
Une jointure temporelle doit annoncer sa direction, sa tolérance et le traitement des valeurs absentes.
Utiliser une donnée future pour expliquer un événement passé crée un biais d’anticipation.
Les changements de jour, fuseaux et fenêtres de financement exigent une convention UTC unique.
Un contrôle de couverture compare première et dernière séquence, trous observés et volume attendu.
Les résultats dérivés doivent embarquer paramètres, version du code et empreintes du manifeste source.
Ce parcours est documentaire : aucune nouvelle installation, requête réseau ou exécution de tests.
Les schémas et hypothèses peuvent être confrontés aux outils et exemples du dépôt source.
