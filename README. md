# Laboratoire Docker - Création d'un environnement de développement Python

## Objectif

Dans cet exercice, vous allez créer un environnement de développement Python en utilisant Docker. 
Vous allez créer un Dockerfile basé sur Alpine, configurer Python, ajouter un fichier `.bashrc`, et utiliser 
Docker Compose pour partager un répertoire de travail avec votre machine hôte. 
Vous allez également exécuter un script Python qui utilise une compréhension de liste.

Afin d'avoir une structure de répertoire propre, les scripts Python doivent être placés dans un répertoire `code` à la racine du projet.

## Étapes

1. **Dockerfile**  
   Créez un fichier `Dockerfile` qui :
   - Part de l'image `alpine`
   - Installe Python
   - Installe bash
   - Installe pip
   - Démarer un shell bash par défaut
   - Copie un fichier `.bashrc` dans le conteneur dans le répertoire `/root`
   - Définit le répertoire de travail par défaut à `/code`

2. **Fichier `.bashrc`**  
   Vous trouverez le fichier `.bashrc` fourni. Copiez-le dans votre répertoire de travail pour qu'il soit intégré à l'image Docker lors de la construction.

3. **Volume partagé**  
   Vous devez monter un volume local dans le conteneur, sur le répertoire `/code`. Ce volume contiendra un fichier Python fourni qui s'exécutera dans l'environnement Docker.

4. **Script Python**  
   Un fichier Python appelé `main.py` doit être fourni, et il doit contenir un script simple utilisant une compréhension de liste.

5. **docker-compose.yml**  
   Créez un fichier `docker-compose.yml` qui permet de :
   - Monter le répertoire local dans le conteneur sur `/code`
   - Démarrer le conteneur en mode interactif
   - Exécuter la commande `bash`
   - Démarrer dans le répertoire de travail `/code`
   - Nommer le conteneur `dev-python`
   - Nommer l'image `img-python`

6. **Exécution**  
   Démarrer le conteneur en arrière-plan ou non

7. **Se connecter au conteneur en mode interactif**
   Connectez-vous au conteneur en mode interactif grâce à la commande `bash`

8. **Exécution du script Python**
    Exécutez le script Python fourni

9. **Nettoyage**
    Arrêtez le conteneur
