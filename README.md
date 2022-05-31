# Einleitung allgemein
Einleitung allgemein (Erklärungen zum ganzen M300-Projekt)

# Inhaltsverszeichnis
  - Cheat Sheet Commands Docker
  ![image](https://user-images.githubusercontent.com/105726204/171164469-3bd715a5-5ab3-432f-a36b-ab5b08932531.png)

## Installation von Container und Verbindung mit MySQL Workbench
Für die Verbindung auf das MySQL braucht man eigentlich nicht mehr als 2 Befehle:


docker run -d --name mysql-container -e TZ=UTC -p 30306:3306 -e MYSQL_ROOT_PASSWORD=My:S3cr3t/ ubuntu/mysql:8.0-22.04_beta

Mit diesem Befehl kann ich den SQL-Container starten und gleich einen root-User und Passwort bestimmen. 

Mit: -p 30306:3306 gebe ich die Ports frei für die Verbindung von aussen. 
-e steht dafür für environment, Variabeln welche für die Config bereits definiert sind. 

Danach können wir überprüfen ob das ubuntu/mysql läuft:
![image](https://user-images.githubusercontent.com/105726204/171174155-49c7ca97-a764-4bb8-9f03-bf61bb3ae337.png)

Wenn wir dies sichergestellt haben können wir nun die Connection über das MySQL Workbench starten:
![image](https://user-images.githubusercontent.com/105726204/171174449-18488f9c-ed9c-43c8-a2e0-a22a39af0fe0.png)

![image](https://user-images.githubusercontent.com/105726204/171174593-34ccb1e0-a0ad-4aa6-95cb-48adf34a1f28.png)

Danach können wir uns mit dem gesetzten root Passwort anmelden. 
In unserem Fall: My:S3cr3t/

Wenn die Verbindung besteht können wir unter Schmemas ein neues Schema erstellen und dies m300 nennen. 

Wir gehen zurück auf den Client und Verbinden uns aufs Repository und schauen ob die DB existiert:

![image](https://user-images.githubusercontent.com/105726204/171175929-037b7b45-8bd0-4e79-a28c-328c22ac08b4.png)


## 10-Toolumgebungen 
Einträge (eigene Erkenntnisse während dem Bearbeiten dieses Kapitels)

## 20-Infrastruktur
Einträge (eigene Erkenntnisse während dem Bearbeiten dieses Kapitels)

## 35-Sicherheit 1
Einträge (eigene Erkenntnisse während dem Bearbeiten dieses Kapitels)

## 30-Container
Einträge (eigene Erkenntnisse während dem Bearbeiten dieses Kapitels)

## 35-Sicherheit 2
Einträge (eigene Erkenntnisse während dem Bearbeiten dieses Kapitels)

## 40-Container-Orchestrierung
Einträge (eigene Erkenntnisse während dem Bearbeiten dieses Kapitels)

## 50-Add-ons 
Einträge (eigene Erkenntnisse während dem Bearbeiten dieses Kapitels)

## 60-Reflexion
Lernprozess festgehalten (Form frei wählbar)
Hallo

- - -
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/ch/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/ch/88x31.png" /></a><br />Dieses Werk ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/ch/">Creative Commons Namensnennung - Nicht-kommerziell - Weitergabe unter gleichen Bedingungen 3.0 Schweiz Lizenz</a>

- - -
