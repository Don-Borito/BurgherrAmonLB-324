# LB 324

## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.
### Automatisierte Code-Tests und -Formatierung

Um `pre-commit`in diesem Repository für automatiesierte  Code-Tests und -Formatierung zu verwenden, müssen folgende Schritte befolgt werden:

1. `pre-commit` installieren falls es auf dem System noch nicht vorhanden ist.  
   Kontrolle ob vorhanden: `pre-commit --version`  
   installation: `pip install pre-commit`
   
2. `pre-commit` im Repository initialisieren: `pre-commit install`
   
Nun wird der Code beim Commiten automatisch formatiert und beim Pushen jedes mal kontrolliert.
Wenn von `pre-commit` Fehler gemeldet werden, müssen diese korrigiert werden, damit der Commit oder Push durchgeführt werden kann. `pre-commit` kann auch manuell gestartet werden, um die Formatierung und Tests zu erzwingen.  
Manuell starten: `pre-commit run --all-files`

## Aufgabe 4
Link zur Applikation [hier](https://burgherramonlb324.azurewebsites.net)

Inhalt der `.env` Datei in Azure eintragen.

1. Bei der Web App unter Configuration -> Application settings -> New Application setting
   ![Screenshot 2023-10-27 002958](https://github.com/Don-Borito/BurgherrAmonLB-324/assets/89085704/ed36f41b-0bc2-4639-97f7-475943cad16d)
2. Name: PASSWORD; Value: "geheimesPasswort"
   ![Screenshot 2023-10-27 002842](https://github.com/Don-Borito/BurgherrAmonLB-324/assets/89085704/9b0ad941-5320-488b-89d3-ebcea8c091b3)

