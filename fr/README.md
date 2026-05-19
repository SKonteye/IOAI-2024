# Parcours francais IOAI 2024

Cette arborescence `fr/` est la version francaise miroir des contenus humains du depot. L'objectif est qu'un eleve francophone puisse suivre les taches et les solutions avec le meme niveau de comprehension que dans la version anglaise.

## Etat de la traduction

Les enonces et les notebooks de solution disponibles pour l'epreuve sur site ont ete traduits, et leur structure (nombre de cellules, ordre des types de cellules, logique de code) a ete verifiee cellule par cellule contre les originaux. Les jeux de donnees, images et autres ressources binaires ne sont pas dupliques : ils restent dans les dossiers d'origine sous `On-Site-Round/` et sont reutilises par les notebooks francais via des chemins relatifs corriges, aussi bien pour les images (`figs/`) que pour les donnees (`training_set/`, `validation_set/`, `test_set/`). Chaque chemin reference a ete resolu depuis le dossier du notebook francais pour confirmer qu'il pointe vers un fichier reel. L'execution complete bout en bout n'a pas pu etre relancee dans cet environnement (torch/pandas non disponibles), donc les liens ci-dessous correspondent a une verification structurelle et de chemins, pas a une re-execution.

| Tache | Description | Enonce francais | Solution francaise |
|---|---|---|---|
| Help BOBAI | Adapter un classifieur existant a 5 classes pour reconnaitre 7 classes, sans modifier le modele deploye et en travaillant sur des embeddings pre-calcules. | [Notebook](On-Site-Round/Help_BOBAI/Help_BOBAI.ipynb) | [Solution](On-Site-Round/Help_BOBAI/Solution/Help_BOBAI_Solution.ipynb) |
| Lost in a Hyperspace | Concevoir des caracteristiques efficaces pour predire plusieurs proprietes d'hypercubes lumineux avec une regression lineaire sous fortes contraintes. | [Notebook](On-Site-Round/Lost_in_Hyperspace/Lost_in_Hyperspace.ipynb) | [Solution](On-Site-Round/Lost_in_Hyperspace/Solution/Lost_in_Hyperspace_Solution.ipynb) |
| The Madarian Cow Mystery | Resoudre une enquete de classification et d'analyse de donnees autour du mystere de la vache madarienne. | [Notebook](On-Site-Round/Madarian_Cow/Madarian_Cow.ipynb) | [Solution](On-Site-Round/Madarian_Cow/Solution/Madarian_Cow_Solution.ipynb) |

## Regle de fidelite

Les notebooks francais conservent la meme structure, le meme ordre de cellules, le meme code executable, les memes donnees et les memes sorties attendues que la version originale. Seules les cellules Markdown, les commentaires et les instructions destinees aux lecteurs ont ete traduits en francais, puis verifies contre les notebooks sources.
