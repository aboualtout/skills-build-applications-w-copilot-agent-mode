
# OctoFit Tracker App

Die OctoFit Tracker App ist eine moderne Fitness- und Team-Tracking-Plattform. Sie bietet:

- Benutzer-Authentifizierung und Profile
- Aktivitäten-Logging und Fortschrittsverfolgung
- Team-Erstellung und Management
- Wettbewerbsfähige Leaderboards
- Personalisierte Workout-Vorschläge

Das Projekt besteht aus einem Django REST Backend (mit MongoDB) und einem React-Frontend mit Bootstrap-Design.

## Ausführung

### Backend starten
1. Python-Umgebung aktivieren:
	```bash
	source octofit-tracker/backend/venv/bin/activate
	```
2. Abhängigkeiten installieren:
	```bash
	pip install -r octofit-tracker/backend/requirements.txt
	```
3. Backend-Server starten:
	```bash
	python octofit-tracker/backend/manage.py runserver 0.0.0.0:8000
	```

### Frontend starten
1. In das Frontend-Verzeichnis gehen:
	```bash
	cd octofit-tracker/frontend
	```
2. Abhängigkeiten installieren:
	```bash
	npm install
	```
3. React-App starten:
	```bash
	npm start
	```

Das Frontend ist dann unter http://localhost:3000 erreichbar, das Backend unter http://localhost:8000.

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

