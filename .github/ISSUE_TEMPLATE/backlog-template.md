---
name: Backlog Template
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

> Für die Erstellung eines Backlogs bitte die [Gherkin Syntax](https://cucumber.io/docs/gherkin/) verwenden, um das Verhalten abzubilden. Nutze dafür das folgende Template. Die Schritte sollten so angeleggt werden, dass eine externe Person nachvollziehen kann, wozu das Backlogitem mit dem beschrieben Verhalten gehört.

## Feature: [Featurename]

### Szenario: [kurzer Szenarioname]

* **Gegeben** ist, ...
* **Wenn** ...
* [**Oder** / **Und**] ...
* **Dann** ...
* [**Oder** / **Und**] ...

Optional noch eine Erklärung ergänzen.


---
im folgenden ein Beispiel und sollte gelöscht werden:

## Feature: Authentifizierung

### Szenario: Nutzer loggt sich ein

* **Gegeben** ist ein _unauthentifizierter Nutzer_
* **Wenn** der _unauthentifizierte Nutzer_ zur Loginseite navigiert
* **Und** in das _Login Formular_ seine Zugangsdaten einträgt
* **Und** seine _Credentials_ korrekt sind
* **Dann** wird der _Nutzer authentifiziert_
* **Und** ein _Sessiontoken_ wird gesetzt
* **Und** der _Nutzer_ erhält Zugriff auf seinen Bereich

### Szenario: Nutzer loggt sich aus

* **Gegeben** ist ein _authentifizierter Nutzer_
* **Wenn** der _authentifizierte Nutzer_ auf den Logout Button klickt
* **Oder** sein _Sessiontoken_ abläuft
* **Dann** wird der _authentifizierte Nutzer_ ausgeloggt
* **Und** er verliert Zugriff auf seinen Bereich
* **Und** der _Sessiontoken_ wird invalide