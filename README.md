<!--

author:   Sebastian Zug & Georg Jaeger
email:    sebastian.zug@informatik.tu-freiberg.de & georg.jaeger@informatik.tu-freiberg.de
version:  1.0.0
language: de
narrator: Deutsch Female

comment:  This is a very simple comment.
          Multiline is also okay.

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js
          https://felixhao28.github.io/JSCPP/dist/JSCPP.es5.min.js

link: https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css



-->

# Praktische Phase des Robotik-Projektes 2023

Die interaktive Ansicht dieses Kurses ist unter folgendem [Link](https://liascript.github.io/course/?https://raw.githubusercontent.com/ComputerScienceLecturesTUBAF/RobotikProjekt-Praxis/main/README.md) verfügbar.

## Rückblick auf das vergangene Jahr

_Das Ziel wird es sein den Roboter am Ende des Semesters auf einem Gehweg über das Campusgelände fahren zu lassen._

![previewer](./imgs/Husky03.jpeg)

Teams:
* **Sensorik**
* **Kamera**
* **Mapping**
* **Navigation**
* **Integration und Organisation**

> Herausforderungen: "Fehleranfälligkeit" des Roboters, fehlendes Aufgabenverständis, später Arbeitsbeginn

## Auf ein Neues!

![image](https://emanual.robotis.com/assets/images/platform/turtlebot3/autonomous_driving/autorace_rbiz_challenge_2017_robots_1.png)

+ Traffic Lights
+ Intersection
+ Construction
+ Parking
+ Level Crossing
+ Tunnel

!?[Szenario](https://www.youtube.com/watch?v=8K4GMbfXFXI&t=46s)

Vorgeschlagene Teamstruktur:

| Partner | Aufgaben |
|---------|--------|
|1 | Schildererkennung einschließlich Ampel und Schranke|
|2| Linienerkennung und dazwischen fahren, einparken|
| 3 | Pfadplanung um Hindernisse mit Laserscanner (Tunnel und Baustelle)|

## Organisatorisches

## In welchem Team bist du?

Eure erste Aufgabe besteht darin, euch für ein Team zu entscheiden! Findet euch den Aufgabenkomplexen entsprechend zu Teams zusammen und setzt Kommunikationswege auf.

Schickt bitte eine Mail an [Gero Licht](mailto:gero.licht@informatik.tu-freiberg.de?subject=[RobotikProjektSS21]) mit den Namen eurer Teammitglieder, eurem Teamname und eurem Teamleiter (+ seine Mailadresse).

## Erste Schritte

Abhängig von den individuellen Aufgaben solltet ihr in eurem Teams zunächst:

* Die Aufgabe(n) diskutieren
* Methodiken und Ansätze zur Bearbeitung der Aufgabe identifizieren
* Deren Funktionsweise verstehen und evaluieren, ob diese zur eurer Aufgabe passen
* Gitlab Repository aufsetzen [Link](https://gitlab.hrz.tu-chemnitz.de/)
* Chat einrichten [Matrix](https://matrix.tu-freiberg.de/)

## Ablaufplan

**Wöchentliche Meetings:**

| Meeting                  |
|:-------------------------|
| Montag 14:00 - 15:30     |
| Donnerstag 11:30 - 13:00 |

**Bei jedem Meeting wird ein Mitglied von jedem Team kurz die Fortschritte zusammenfassen:**

* Welche Ziele wurden für die Woche gesetzt?
* Welche Ziele wurden erreicht, welche nicht? Warum?
* Welche Ziele gibt es für die kommende Woche?

Jedes Team sollte diese Fortschritte, genannten Ziele und Probleme entsprechend dokumentieren. Hier bieten sich Wikis, Issues, Protokolle, ... an!

Daraufhin wird es die Möglichkeit geben über die aktuellen Probleme zu diskutieren, oder gegebenenfalls einen individuellen Termin zur Lösung schwierigerer Fragestellungen zu vereinbaren.
Zusätzlich wird jedes Team drei Vorträge halten.

**Vorträge**

* Exposé:

  * Motivation des Projektes
  * Stand der Technik
  * Zeitliche und inhaltliche Planung des Projektes (Meilensteinplanung)

* Zwischenstand:

  * Vorstellung der (angestrebten) Softwarestruktur
  * Stand der Implementierung
  * Wo steht ihr bezüglich des Plans? Sind Anpassungen notwendig?

* Abschlussvortrag:

  * Zusammenfassung des Projektes (zeitlich, inhaltlich, konzeptionell)

**Ablaufplan für die Vorträge**

| **Datum**             | **Vorträge**     |
|:----------------------|:-----------------|
| Ende April            | Exposé           |
| Ende Mai              | Zwischenstand  + Demo   |
| Letzte Semesterwoche  | Abschlussvortrag |

## Bewertungskriterien und ihre Gewichtung

**1. Vorträge**

Die Exposé-, Zwischenstands- und Verteidigungsvorträge werden mit 2/3 den Großteil der Bewertung ausmachen.
Hier geht es darum alle Aspekte des Projektes anschaulich und selbstkritisch Darzustellen.
Im Fokus stehen die eingesetzen Techniken und Konzepte, sowie Entscheidungsprozesse zu dokumentieren und zu begründen.

**2. Dokumentation**

Ebenfalls von großer Bedeutung bei Softwareprojekten ist die hinreichende Dokumentation der Software.
Dementsprechend fließt auch diese in die Bewertung mit ein.
Entscheidend ist hierbei jedoch, dass (neben den Vorträgen, die auch der Dokumentation dienen) eine Anleitung zur Nutzung der Software sowie für mögliche Weiterentwicklungen entsteht.

**3. Tooling**

Neben den dokumentativen Aufgaben kann der Einsatz der richtigen Tools dramatisch zum Erfolg/Misserfolg eines Projektes beitragen.
Dementsprechend sollten (soweit sinnvoll) Tools zur Automatisierung/Unterstützung des Entwicklungsprozesses eingesetzt werden.
Dokumentiert sowohl den Einsatz der Tools, als auch, wie hilfreich ihr diese Empfunden habt.

**4. Softwarearchitektur**

Letztlich steht auch die Softwarearchitektur als zentrale Komponent eines Softwareprojekts im Fokus des Semesters.
Hier soll vor allem eine konsistente, intuitive Struktur angestrebt werden.
*Hinweis: Eine Software, die sich schlecht dokumentieren lässt, ist vermutlich nicht intuitiv oder gar schlecht strukturiert!*
