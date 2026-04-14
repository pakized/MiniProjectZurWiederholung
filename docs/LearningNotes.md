\## Zusammenfassung – aktueller Stand



\### Server

Der Server ist ein ASP.NET Core Web API Backend.

Während der Entwicklung läuft er lokal auf dem eigenen Rechner (`localhost`).



In einer Produktionsumgebung würde derselbe Server-Code auf einer Cloud-

Plattform betrieben werden.



\---



\### Cloud

Cloud bedeutet, dass virtuelle Server gemietet werden, die auf echten,

physischen Rechnern in weltweit verteilten Rechenzentren laufen.



\---



\### Projekt-Setup

Das Backend-Projekt wurde mit dem .NET CLI erstellt (`dotnet new webapi`).

Zum Starten des Servers wird `dotnet run` verwendet.

Der Server läuft dauerhaft, bis er manuell mit `Ctrl + C` beendet wird.



\---



\### Swagger

Swagger wird als Test-Interface im Browser verwendet.

Es ersetzt einen separaten Test-Client und ermöglicht:

\- das Anzeigen von API-Endpunkten

\- das direkte Testen von Requests



\---



\### API-Endpunkte

Ein API-Endpunkt ist eine Adresse, über die ein Client eine Aktion beim Server

anfragt oder ausführt.



Ein Endpunkt besteht aus:

\- einer HTTP-Methode (GET, POST, PUT, DELETE)

\- einem Pfad (z. B. `/api/health`)



\---



\### Controller

Ein erster Controller (`HealthController`) wurde angelegt.

Er stellt den Endpunkt `GET /api/health` bereit, der über Swagger sichtbar ist.


\---





### Git

Die Projektänderungen werden mit einem klassischen Git-Workflow versioniert.

Typischer Ablauf:

1. Zum Projekt-Root wechseln
2. Aktuellen Status prüfen (`git status`)
3. Änderungen zum Commit hinzufügen
   - alle Dateien: `git add .`
   - einzelne Datei: `git add docs/LEARNING_NOTES.md`
4. Commit mit einer aussagekräftigen Message erstellen  
   (`git commit -m "docs: add learning notes for core backend concepts"`)
5. Optional: Remote-Repositories prüfen (`git remote -v`)
6. Änderungen in das Remote-Repository pushen (`git push`)


