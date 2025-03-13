# Cyclistic Project

## Importation des données

Ce projet utilise un notebook d'importation des données pour télécharger et traiter les fichiers nécessaires au projet. Le notebook se trouve dans le dossier `notebooks/` et est nommé `Data_Import.ipynb`.

### Prérequis

1. **Assurez-vous que les dépendances sont installées** :
   - Vous aurez besoin des bibliothèques suivantes :
     - `requests`
     - `pandas`
     - `zipfile`
     - `io`
     
     Vous pouvez installer ces dépendances en exécutant la commande suivante :

     ```bash
     pip install -r requirements.txt
     ```

### Utilisation du notebook

1. **Exécuter le notebook** :
   Le notebook téléchargera automatiquement les fichiers nécessaires à partir du serveur AWS dédié. Ces fichiers sont utilisés pour l'analyse des données Divvy.

2. **Téléchargement des fichiers** :
   Le notebook télécharge les fichiers CSV nécessaires depuis les URLs suivantes sur AWS :

   - `https://divvy-tripdata.s3.amazonaws.com/`
   
   Les fichiers CSV sont extraits des archives ZIP et combinés dans un DataFrame pour l'analyse. Ce processus ne nécessite aucune action supplémentaire de votre part à part l'exécution du notebook.

3. **Lancer le notebook** :
   Après avoir installé les dépendances et exécuté le notebook, les données seront prêtes pour l'analyse.


## Dataset

Le fichier `combined_data.csv` peut être téléchargé depuis le lien suivant :

[Télécharger combined_data.csv](https://drive.google.com/file/d/1d8wwj_5DsvWXQuKLHF6MHl1UPcVhYc2N/view?usp=sharing)
