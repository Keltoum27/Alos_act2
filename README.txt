start_api.bat

.bat est l'extension d'un fichier de commandes MS-DOS. Réaliser un tel fichier permet de concevoir des scripts qui seront interprétés par le "shell" ou interpréteur de commandes (command.com ou cmd.exe) pour notamment exécuter des fichiers

contenue de fichie start_api.bat
cd /d %~dp0
json-server --watch db.json
pause