ChatLPSIC - Application de Communication Sécurisée
1. Description du projet
ChatLPSIC est une application de communication sécurisée client-serveur développée en Python, permettant à plusieurs clients de communiquer de manière privée et sécurisée. Grâce à un chiffrement hybride RSA et AES, les messages échangés sont protégés contre les accès non autorisés. L'application peut fonctionner en réseau local ou sur Internet, et garantit la confidentialité des informations échangées.

2. Installation
Il existe deux façons d'installer et de configurer le projet. Choisissez la méthode qui vous convient le mieux :

Méthode 1 : Installation avec les dépendances
Clonez ce dépôt GitHub :
git clone https://github.com/ChatLPSIC/first.git

Installez les dépendances à l'aide du fichier requirements.txt :
pip install -r requirements.txt

Exécutez le fichier main.py pour démarrer l'application.

Méthode 2 : Installation avec environnement virtuel préconfiguré
Décompressez les fichiers .venv.zip et chatlpsic_1.zip fournis dans le projet.
Placez les dossiers .venv, .idea, et def dans un même répertoire.
Ouvrez le projet avec un éditeur de code (par exemple, PyCharm).
Exécutez le fichier main.py directement pour voir le rendu du projet, sans besoin d'installer les dépendances manuellement.


3. Utilisation
Vous pouvez démarrer l'application en lançant le serveur ou en vous connectant en tant que client. Voici les grandes étapes :

1. Configurer le serveur
Indiquez le pseudonyme, la description, et le port du serveur.
2. Se connecter au serveur
Renseignez le pseudonyme du client et l'adresse IP du serveur pour établir une connexion.
3. Discuter avec les autres clients
Une fois connecté, vous pouvez échanger des messages avec d'autres clients via une interface sécurisée, avec une option de chiffrement ou de non-chiffrement.
4. Documentation complémentaire
Pour une explication détaillée du projet, y compris des images illustrant l'interface et le fonctionnement interne, ainsi que des informations sur la structure des fichiers backend et comment chaque fichier fonctionne, consultez le fichier documentation.pdf inclus dans ce dépôt.

Le fichier PDF contient :

Un guide détaillé sur l'utilisation de l'application.
Des diagrammes expliquant la structure du code.
Des explications sur le chiffrement des messages et la gestion des connexions.
Des captures d'écran pour mieux comprendre l'interface utilisateur et les interactions.
5. Contribuer
Si vous souhaitez contribuer à ce projet, veuillez suivre les étapes suivantes :

Forkez ce dépôt.
Créez une branche pour votre fonctionnalité :
bash
Copier le code
git checkout -b feature-nom
Effectuez vos modifications et validez-les :
bash
Copier le code
git commit -am 'Ajoute une fonctionnalité'
Poussez votre branche :
bash
Copier le code
git push origin feature-nom
Soumettez une pull request.
