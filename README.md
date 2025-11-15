# data_managment

## Structure du repository
data_management/
├── data/
│   ├── raw/              # Données brutes, non modifiées
│   └── processed/        # Données nettoyées/transformées
├── notebooks/            # Notebooks Jupyter d'analyse des données
├── requirements.txt      # Pour travailler sur les mêmes versions de librairies
├── .gitignore
└── README.md

## Installation

1. Cloner le dépôt
```bash
   git clone
   cd data_management
```

2. Créer et activer l'environnement virtuel
```bash
   python -m venv .venv
   source .venv/bin/activate  # Mac/Linux
   # ou
   .venv\Scripts\activate     # Windows
```

3. Installer les dépendances
```bash
   pip install -r requirements.txt
```

4. Lancer Jupyter
```bash
   jupyter notebook
```
