# userinformation_server
Stellt einen node.js HTTP/HTTPS Server als Schnittstelle zu diversen Sprachassistenen (Amazon Alexa, Google,..)

#Beschreibung

Stellt einen node.js mit express.js HTTP/HTTPS Server. Dieser Server dient als Schnittstelle zum Sprachinterface und kann anhand GET/PUTund UPDATE Daten an den Server senden oder abfragen. 

Die Daten werden in Controllern bearbeitet und an eine mongoDB weitergesendet. 

#Anleitung zur Benutzung

1. Auf dem Rechner muss node.js installiert sein. 

-> https://nodejs.org/en/

2. Über den befehl node <script_path> wird der Server gestartet. 

3. In einem Beigelegten Shellscript ist es möglich den Server bei jedem start automatisch zu starten. 

