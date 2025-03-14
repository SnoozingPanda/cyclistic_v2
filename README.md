# Cyclistic

### Contexte
Cyclistic est une entreprise de partage de vélos à Chicago, qui a élargi son offre pour inclure une flotte de 5 824 vélos géolocalisés, stationnés à 692 emplacements à travers la ville. Les vélos peuvent être déverrouillés à une station et retournés à n'importe quelle autre station du réseau à tout moment.

Il existe deux types d'utilisateurs :

+ Cyclistes occasionnels : Ceux qui achètent des passes pour une seule course ou pour une journée complète.
Membres : Ceux qui achètent un abonnement annuel.
+ Le directeur marketing souhaite augmenter le nombre d'abonnements annuels et comprendre les différences d'utilisation entre ces deux types de cyclistes.

### Objectifs
L'objectif de ce projet est de répondre à plusieurs questions clés pour aider à formuler une stratégie marketing efficace pour augmenter les abonnements annuels :

+ Comment les membres annuels et les cyclistes occasionnels utilisent-ils les vélos Cyclistic différemment ?
+ Pourquoi les cyclistes occasionnels achèteraient-ils des abonnements annuels ?
+ Comment Cyclistic peut-il utiliser les médias numériques pour influencer les cyclistes occasionnels à devenir membres ?
+ Où recommanderiez-vous à Cyclistic d'implémenter de nouvelles stations pour rendre le service plus disponible ?

Les réponses à ces questions permettront à l'équipe de marketing de développer des recommandations basées sur des données concrètes et des visualisations professionnelles.

## Importation des données
Ce projet utilise un notebook Jupyter pour télécharger et traiter les fichiers nécessaires à l'analyse des données. Le notebook se trouve dans le dossier notebooks/ et est nommé Data_Import.ipynb.

### Prérequis
Avant de commencer, vous devez vous assurer que les dépendances suivantes sont installées sur votre machine :

+ Python 3.x.

+ Jupyter Notebook.

+ Dépendances Python : Installez les bibliothèques nécessaires avec la commande suivante :

bash
pip install -r requirements.txt

Le fichier requirements.txt contient les bibliothèques suivantes :

+ requests : Pour télécharger les fichiers depuis le serveur AWS.
+ pandas : Pour le traitement des données.
+ zipfile : Pour extraire les fichiers ZIP.
+ io : Pour la gestion des flux de données.


## Utilisation du notebook
### Exécution du notebook :
Ouvrez le fichier Data_Import.ipynb dans votre environnement Jupyter et exécutez-le. Le notebook téléchargera automatiquement les fichiers nécessaires à partir du serveur AWS dédié.

### Téléchargement et extraction des fichiers :
Le notebook télécharge les fichiers CSV nécessaires depuis les URLs suivantes :

https://divvy-tripdata.s3.amazonaws.com/

Ces fichiers sont extraits des archives ZIP et combinés dans un seul DataFrame pour l'analyse.

### Préparation des données :
Une fois le notebook exécuté, les données seront prêtes pour l'analyse. Il n'est pas nécessaire de réaliser d'étapes supplémentaires après l'exécution du notebook.

# Dataset
Si vous souhaitez éviter le processus de téléchargement et d'extraction des données, vous pouvez télécharger directement le fichier combined_data.csv résultant de cette opération à cette adresse:
https://drive.google.com/file/d/1d8wwj_5DsvWXQuKLHF6MHl1UPcVhYc2N/view?usp=drive_link