# Todo React-Applikation mit Sqlite-Testdatenbank

- Diese Web-Applikation verwaltet ToDo-Items. 
- Die Daten werden in einer SQLite Datenbank innerhalb des Containers gespeichert.
- Das Frontend wurde mit dem ReactJS-Framework realisiert.
- Es verwendet Port 3000.
- Weil die API das Datenbankfile in /etc erstellt muss sie root-Berechtigungen haben. (In devcontainer.json die letzte Zeile mit  **"remoteUser": "root"** aktivieren.)

Installiere die Abhängikeiten mit:  
**npm install**

Starte die Applikation mit:     
**npm run dev**

Um Debugging zu ermöglichen, kann das lauch.json ohne weitere Änderungen verwendet werden.