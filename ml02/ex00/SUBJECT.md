# ml02 / ex00 — Sigmoïde stable

| Champ | Valeur |
| --- | --- |
| Fichier à rendre | `solution.py` (ou `report.md` si demandé) |
| Tests à rendre | `test_solution.py` |
| Python | 3.11+ |
| Dépendances | NumPy ; Pandas/Matplotlib pour données ; scikit-learn seulement si demandé |

## Objectif
`sigmoid(z: np.ndarray) -> np.ndarray`

Évite overflow pour valeurs extrêmes, retourne probabilités.

## Exemple de comportement
[-1000,0,1000] → [≈0,.5,≈1].

## Contraintes
- Respecter la signature ou, pour un rapport, le nom de fichier demandé.
- Vérifier dimensions, types et entrées dégénérées ; lever `ValueError` en cas d'argument invalide, sauf indication contraire.
- Ne pas modifier les entrées.
- Fixer une graine pour tout tirage aléatoire ; conserver la reproductibilité.
- Ne pas appeler directement un estimateur sklearn qui résout l'exercice, sauf comparaison explicitement demandée.
- Pour toute évaluation, séparer entraînement et test avant d'apprendre des paramètres de prétraitement.

## Travail à rendre
1. Implémentation sans corrigé fourni.
2. Au moins trois tests : cas nominal, cas limite, entrée invalide.
3. `NOTES.md` : expliquer le mécanisme mathématique en quelques phrases et commenter une observation expérimentale.

## Bonus
Tester une autre distribution ou un jeu de paramètres et expliquer les écarts.

## Autoévaluation
- [ ] Résultat conforme et tests reproductibles.
- [ ] Cas limites traités.
- [ ] Je peux expliquer le calcul et ses limites.
