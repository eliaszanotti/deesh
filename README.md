# Deesh

Deesh est un script simple qui vous permet de télécharger des playlists Deezer au format MP3 en utilisant Deezloader Remix (Deemix).

## Installation

1. Assurez-vous d'avoir [Python](https://www.python.org/downloads/) installé sur votre système.
2. Clonez ce dépôt sur votre machine :
   ```bash
   git clone https://github.com/eliaszanotti/deesh.git
   ```
4. Téléchargez la dernière version de Deemix avec 
   ```bash
   pip install deemix
   ```
## Utilisation

1. Lancez le script `deesh` :
	Ici playlist name correspond au nom de la playlist que vous voulez télécharger dans database.sh
   ```bash
   chmod +x deesh
   ./deesh <playlist_name>
   ```