# TP RAG — Altéa Services

Notebook pédagogique pour préparer et indexer la documentation fictive d’Altéa Services.

## Contenu du dépôt

- `notebooks/14-TP-RAG.ipynb` : étapes de collecte, nettoyage, découpage et indexation.
- `data/docs/` : corpus fourni pour le TP, classé par service.
- `requirements.txt` : dépendances Python utilisées par le projet.

La base ChromaDB `base_vectorielle/` est générée localement par le notebook et n’est pas publiée.
Le fichier `.env` est également exclu afin de ne pas versionner de secrets.

## Installation et lancement

Depuis la racine du dépôt, créez un environnement virtuel, installez les dépendances, puis ouvrez le notebook dans VS Code ou Jupyter :

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

Exécutez les cellules dans l’ordre. La partie B de l’étape 4 crée la base vectorielle locale et lance trois recherches de démonstration.