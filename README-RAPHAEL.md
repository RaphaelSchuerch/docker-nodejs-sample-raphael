# Abschlussprojekt KW 44
## **Klonen des Repositories**
  - Gehe bei dem Repository das du kopieren willst, auf den Dropdownpfeil bei **CODE**. Dort steht dann die Adresse des Repository. Die Adresse sollte etwa so aussehen: **git@github.com:_Username_/_Repository-Name_.git**
    - Kopiere den Code
  - **Öffne GIT BASH**
    - Gib folgendes ein: _git clone_ (Repository Adresse)
- **ACHTUNG WICHTIG**
  - Schau nach ob du im richtigen Pfad bist.
## **Installation der notwendigen Pakete**
  - Die Pakete werden **autmoatisch** im Docker-Container heruntergeladen, sobald man ihn startet. **Alle** Pakete spielen eine Wichtige Rolle beim _Aufsetzen_ und _laufen lassens_ der Node.js Datei. Folgende Dateien werden Benötigt
    - **express** wird für das erstellen von _Webservern_ und das handling der _HTTP_  requests gebraucht
    - **pg und sqlite3** sind da, um mit _PostgreSQL_ und _SQLite_  Datenbanken zu connecten
    - **uuid** generiert einzigartige _ID's_
    - **wait-port** stellt sicher das _Dienste_ verfügbar sind, bevor die Anwendung versucht sie zu verwenden
## **Docker Konfigurieren und Installieren**
  - [Docker-Desktop](https://www.docker.com/products/docker-desktop/) downloaden
  - Und dann nach Wunsch Konfigurieren
## **Starten der Applikation in einem Docker-Container**
  - Auf Docker-Desktop beim gewünschten Container auf der _Start-Pfeil_ rechts drücken.