# Application Questions-Réponses sur des fichiers PDF

Ce chatbot permet de poser des questions sur des documents PDF. Il extrait le texte des fichiers PDF, le divise en morceaux plus petits appelés "chunks", crée un index de recherche à partir des embeddings des mots, et génère des réponses aux questions posées par les utilisateurs en utilisant un modèle de conversation.

## Fonctionnalités

- Importation de fichiers PDF
- Extraction du texte à partir des fichiers PDF
- Découpage du texte en chunks
- Création d'un index de recherche à partir des embeddings des mots
- Génération de réponses aux questions posées par les utilisateurs

## Installation

1. Cloner le dépôt GitHub du programme de Questions-Réponses pour les fichiers PDF.
2. Installer les dépendances en exécutant la commande suivante :
   ````
   pip install -r requirements.txt
   ````
3. Créer un compte sur le site de OpenAI et obtenir une clé d'API.
4. Vous pouvez utiiser l'API de huggingface.co pour une solution gratuite. Il suffit de créer un compte et de copier la clé d'API dans le fichier .env (Faut modifier le code de app.py)
## Utilisation

1. Exécuter le programme en utilisant la commande suivante :
   ````
   streamlit run main.py
   ````
2. Ouvrir l'application dans le navigateur à l'adresse indiquée dans la console.
3. Cliquer sur le bouton "Uploader un fichier PDF" pour sélectionner un fichier PDF à traiter.
4. Poser une question dans le champ de texte et cliquer sur le bouton "Poser la question" pour obtenir une réponse générée par le modèle de conversation.

## Exigences du système

- Python 3.9 ou version supérieure
- Connexion Internet pour télécharger les dépendances

## Contributions

Les contributions à ce programme sont les bienvenues. Pour signaler un problème ou proposer une amélioration, veuillez ouvrir une issue sur le dépôt GitHub du programme.


## Remarque

Ce programme utilise une version spécifique du modèle de langage GPT-3.5 de OpenAI. Pour plus d'informations sur les limitations et les conditions d'utilisation du modèle, veuillez vous référer à la documentation officielle de OpenAI.
