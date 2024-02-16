FRENCH
Introduction
Il s'agit d'un script Python de porte dérobée conçu pour établir une connexion de shell inversé entre une machine cible (victime) et la machine de l'attaquant. La machine cible doit exécuter le script backdoor_client.py, en fournissant l'adresse IP de l'attaquant pour la connexion. De plus, cette porte dérobée implémente deux nouvelles commandes : dl pour le téléchargement de fichiers et capture pour la capture d'écrans.

Utilisation
Configuration de la Porte Dérobée
La victime doit exécuter le script backdoor_client.py.
Lorsque cela est demandé, la victime doit fournir l'adresse IP de l'attaquant.
Commandes Disponibles
dl [nom_fichier] : Télécharge le fichier spécifié depuis la machine de la victime.
Exemple : dl document_secret.txt
capture [nom_fichier] : Capture une capture d'écran du bureau de la victime et la sauvegarde en tant que fichier PNG avec le nom spécifié.
Exemple : capture bureau
Prérequis
Python 3.x
La bibliothèque PIL pour Python (pip install pillow)
Comment Exécuter
Machine de l'Attaquant
Exécutez le script backdoor_server.py.
Attendez les connexions entrantes de la victime.
Machine de la Victime
Exécutez le script backdoor_client.py.
Fournissez l'adresse IP de l'attaquant lorsque demandé.
Avertissement
Ce script est destiné à des fins éducatives et de test uniquement. L'utilisation non autorisée de ce script peut violer les lois applicables. L'auteur n'assume aucune responsabilité pour une utilisation abusive de ce script. Utilisez-le à vos propres risques.

Auteur
Diamondijah
ENGLISH

Introduction
This is a Python backdoor script designed to establish a reverse shell connection between a target machine (victim) and the attacker's machine. The target machine needs to execute the backdoor_client.py script, providing the attacker's IP address for the connection. Additionally, this backdoor implements two new commands: dl for file downloading and capture for screen capturing.

Usage
Setting Up the Backdoor
The victim needs to execute the backdoor_client.py script.
When prompted, the victim should provide the attacker's IP address.
Available Commands
dl [filename]: Downloads the specified file from the victim's machine.
Example: dl document_secret.txt
capture [filename]: Captures a screenshot of the victim's desktop and saves it as a PNG file with the specified name.
Example: capture desktop
Requirements
Python 3.x
The PIL library for Python (pip install pillow)
How to Run
Attacker's Machine
Run the backdoor_server.py script.
Wait for incoming connections from the victim.
Victim's Machine
Run the backdoor_client.py script.
Provide the attacker's IP address when prompted.
Warning
This script is intended for educational and testing purposes only. Unauthorized use of this script may violate applicable laws. The author assumes no responsibility for any misuse of this script. Use it at your own risk.

Author
Diamondijah

