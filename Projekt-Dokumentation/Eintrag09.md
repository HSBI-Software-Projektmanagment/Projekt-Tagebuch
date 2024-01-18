# **Eintrag 09**
**2024-01-17** | 17:30 - 20:00| (2,30h)

## **Anwesend**:

 * **Jan Albeck** (TL) Schriftführer
 * Wael Eskeif
 * Kirill Kuhn
 * Angelo Mavridis
 * Marlon Cadell
 * Daniel Borodin
 * Luca Eberhardt
 * Stephan Klassen

## **Abwesend**:
* keiner

## **Thema**: *Finale besprechung & Planung Abgabe*

### Ergebnisse

Präsentation:

* Projektentwurf zeigen
* Use Cases vorstellen (siehe unten)
* Live Demo Multiplayer:
    * Server anmachen
    * Client verbinden
    * Ein komplettes Rennen fahren (3 Runden)

* Code Vorstellung:
    * Server:
        * Server Code vorstellen
        * Netty Socket IO erklären
        * JSONHandler.java, Server.java, Road.java
        * Wo gab es Schwierigkeiten / Probleme
        * Wie hat man die Probleme gelöst
        * Was haben wir gelernt?
 
    * C++:
        * RayLib vorstellen
        * Singleplayer zeigen
        * Source Code zeigen
        * Wo gab es Probleme / Schwierigkeiten
        * Wie hat man / versucht diese Probleme gelöst
        * Was haben wir gelernt?
 
    * Java:
        * Singleplayer zeigen
        * Code vorstellen
        * Wo gab es Probleme / Schwierigkeiten
        * Wie hat man / versucht diese Probleme gelöst
        * Was haben wir gelernt?


* Use Cases:
    * Generell:
        * Start des Spiels
        * Menü öffnen
        * Spiel schließen
        * Highscore anzeigen
        * Singleplayer starten
        * Multiplayer starten (2 Spieler)
    * Singleplayer:
        * Rundenstart
        * Bewegung der Spielers
        * Kollision gegen NPC's
        * Kollision gegen Hinternisse
    * Multiplayer:
        * Rundenstart gleichzeitig bei 2 Spielern
        * Kollision gegen einander
        * Kollision gegen NPS's
        * Rennen beenden
        * Ergenis des Rennens anzeigen
        * Neuen Highscore Anzeigen


### Letzte probleme

Server:
* Gegnerposition etwas ungenau beim anderen Client

Java Client:
* Zeit nicht richtig angezeigt
    * behoben: zeiteinheit wurde falsch berechnet
* Gegner wird nicht angezeigt
    * behoben: falscher pfad zur Gegner Grafik

C++ Client:
* Verbindungsprobleme zum Server
* Doppelverbindung Socket io Problem, konnte von uns aber nicht umgangen werden


### Letztes meeting

** 18.01.24 **
- Abgabe Meeting