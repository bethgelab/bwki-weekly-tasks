#bwki-weekly-tasks is now renamed to Aufgabenpool

**Aufgabenpool** 

How to implement a new task to the taskpool of ki-kurs.org ?!
1. Create a feature branch from master branch (clone)
2. Upload the challenge as Aufgabe-number.ipynb and the solution Loesung_number.ipynb
3. Set up a PR set one of the SEs as a reviewer
4. Go to https://mybinder.org
5. Put in: Githubrepo: https://github.com/bethgelab/bwki-weekly-tasks.git head: master path to notebook: Aufgabe-(number from above).ipynb
6. Copy Binder Link for solution as well as for task.
7. Go to the repo of the courseplatform
8. **Create a feature branch from development_2 !!! **
9. Go to --> courseplatform/frontend/src/tasks.json
10. Copy the last task and replace elements by your infos. Thats how it should look like: 
  {
    "title":"Schriftfarbenvorhersager",
    "difficulty": 2,
    "category": "Algorithmen",
    "objective": "Umsetzung eines ML-Projekts mit einem vereinfachten neuronalen Netz",
    "description": "Diese Aufgabe wurde von einem Teilnehmer am BWKI gestellt. Danke Christoph! In dieser Aufgabe bearbeitet ihr ein Machine Learning Projekt von Anfang bis Ende. Das heißt, ihr programmiert zunächst ein Tool zum Datensammeln und erstellt euch so einen Datensatz. Im Anschluss implementiert ihr ein vereinfachtes neuronales Netz, trainiert dieses und am Ende wertet ihr die Vorhersagen aus.",
    "notebook": "https://mybinder.org/v2/gh/bethgelab/bwki-weekly-tasks/master?filepath=%2FSchueleraufgaben%2FSchriftfarbenwahl_Aufgabe%2Faufgabe_schriftfarben_vorhersage.ipynb",
    "solution": "https://mybinder.org/v2/gh/bethgelab/bwki-weekly-tasks/master?filepath=%2FSchueleraufgaben%2FSchriftfarbenwahl_Aufgabe%2Floesung_schriftfarben_vorhersage.ipynb",
    "studenttask": true
  }]

11. Push your changes to your feature branch

12. Set up a PR and set one of the SEs as a reviewer, they will review and deploy the changes.

Cheers 
Caro
