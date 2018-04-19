# M300_LB2
## Service Beschreibung:
Wordpress installation mit Docker. Den Container haben wir mit dem Befehl docker-compose gestartet
## Installation (was passiert):
Über das Vagrantfile wird die Virtuelle Maschine installiert. In der Vagrant shell wird das Skript "script.sh" ausgeführt.

Das Skript erstellt den Benutzer: admintbz mit dem Passwort: admintbz

Das Skript erstellt die Datenbank und den Datenbankbenutzer.
## Zugriff
Der Zugriff erfolgt über den Webbrowser auf die URL: http://localhost:8888
## Testen
Das Wordpress sollte auf der Hostmaschine über folgende URL aufgerufen werden: http://localhost:8888 Die Setup Konfiguration von Wordpress soll erscheinen.
