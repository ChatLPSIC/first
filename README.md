ChatLPSIC - Application de Communication Sécurisée

1. Description du projet
   
ChatLPSIC est une application de communication sécurisée client-serveur développée en Python, permettant à plusieurs clients de communiquer de manière privée et sécurisée. Grâce à un chiffrement hybride RSA et AES, les messages échangés sont protégés contre les accès non autorisés. L'application peut fonctionner en réseau local ou sur Internet, et garantit la confidentialité des informations échangées.


2. Installation
   
Pour installer et configurer le projet dans un environnement virtuel, suivez les étapes ci-dessous :

Clonez ce dépôt GitHub :
git clone https://github.com/ChatLPSIC/first.git

Accédez au répertoire du projet :
cd first

Créez un environnement virtuel dans le répertoire du projet :
python -m venv .venv

Activez l'environnement virtuel :
Sur Windows :
.venv\Scripts\activate

Sur Linux / macOS :
source .venv/bin/activate

Installez les dépendances à l'aide du fichier requirements.txt :
pip install -r requirements.txt

Exécutez le fichier main.py pour démarrer l'application :
python main.py

3. Utilisation
   
Vous pouvez démarrer l'application en lançant le serveur ou en vous connectant en tant que client. Voici les grandes étapes :

1. Configurer le serveur
Indiquez le pseudonyme, la description, et le port du serveur, et le nombre maximal de clients qui peuvent se connecter au serveur.
2. Se connecter au serveur
Renseignez le pseudonyme et la description du client et l'adresse IP et le port du serveur pour établir une connexion.
3. Discuter avec les autres clients
Une fois connecté, vous pouvez échanger des messages avec d'autres clients via une interface sécurisée, avec une option de chiffrement ou de non-chiffrement.


4. Documentation complémentaire
   
Pour une explication détaillée du projet, y compris des images illustrant l'interface et le fonctionnement interne, ainsi que des informations sur la structure des fichiers backend et comment chaque fichier fonctionne, consultez le fichier documentation.pdf inclus dans ce dépôt.

Le fichier PDF contient :

Un guide détaillé sur l'utilisation de l'application.
Des explications sur le chiffrement des messages et la gestion des connexions.
Des captures d'écran pour mieux comprendre l'interface utilisateur et les interactions.
Des explications sur le code de chaque fichier.

5. Contribuer
   
Si vous souhaitez contribuer à ce projet, veuillez suivre les étapes suivantes :

Forkez ce dépôt.
Créez une branche pour votre fonctionnalité :

git checkout -b feature-nom
Effectuez vos modifications et validez-les :

git commit -am 'Ajoute une fonctionnalité'
Poussez votre branche :

git push origin feature-nom
Soumettez une pull request.
