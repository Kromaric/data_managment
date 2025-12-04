# data_managment

## Structure du repository
```
data_management/
├── data/
│   ├── raw/              # Données brutes, non modifiées
│   └── processed/        # Données nettoyées/transformées
├── notebooks/            # Notebooks Jupyter d'analyse des données
├── requirements.txt      # Pour travailler sur les mêmes versions de librairies
├── .gitignore
└── README.md
```

## Statut de l'analyse des données
- [x] Catalogue_Produit.csv
- [x] Client_Master.csv
- [x] Marketplace_Import_Mars2025.csv
- [x] Ventes_Q1_2025.csv
- [x] Croiser les données entre les 4 tables pour identifier les problèmes de connexion

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
