Bienvenue dans Nebula Terminal ! 🚀

Ce projet fonctionne sous Windows et Linux (ex : Kali).
Le script launch.py gère automatiquement l’installation dans un environnement virtuel (venv) et lance le terminal.

1. Ouvrir un terminal dans le projet

Windows :

Clique droit dans le dossier → "Ouvrir dans Windows Terminal / PowerShell ici"

Ou bien ouvre manuellement un terminal puis tape :

cd chemin\vers\le\dossier\nebula-terminal


Linux (Kali, Ubuntu, etc.) :

cd /chemin/vers/nebula-terminal

2. Lancer l’installation automatique

Exécute simplement :

python launch.py


Ce script va :

Créer un environnement virtuel (venv/).

Installer toutes les dépendances listées dans requirements.txt.

Lancer directement Nebula Terminal.

3. Lancer Nebula Terminal par la suite

Après la première installation, tu n’as plus besoin de réinstaller.
Il suffit de taper à chaque fois :

python launch.py

4. Si l’installation automatique échoue

En cas de problème avec launch.py, tu peux installer manuellement :

# Windows
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt

# Linux
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt


Puis lance ton projet :

python main.py

5. Aide

Tape help dans Nebula Terminal pour afficher toutes les commandes.

Vérifie que tu utilises bien Python 3.8+.