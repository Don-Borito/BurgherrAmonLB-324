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
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
