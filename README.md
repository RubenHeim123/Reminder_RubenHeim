Reminder Website - Cloud-Computing - DHBW Stuttgart - Ruben Heim

Zu Beginn starten Sie eine Befehlszeile und geben Sie den untenstehenden Command/Befehl ein um alle benötigten Services zu starten. Nach erfolgreichem Start finden Sie die Reminder-Website unter http://localhost:5000

git clone https://github.com/Szenesucht/Reminder_RubenHeim.git && cd ./Reminder_RubenHeim/CloudComputing && docker build . && docker-compose up -d

Nach der Ausführung des Befehls kann die Website unter http://localhost:5000 ausprobiert werden.

Nach einem Neustart benötigt lediglich das docker-compose einen Neustart mit:
cd ./Reminder_RubenHeim/CloudComputing && docker-compose up -d
damit alle Daten wiederhergestellt werden können
