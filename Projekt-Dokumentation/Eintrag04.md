# **Eintrag 04**
**2023-11-13** | 16:00 - 17:30 | (1,30h)

## **Anwesend**:

 * **Jan Albeck** (TL) Schriftführer
 * Daniel Borodin
 * Kirill Kuhn
 * Stephan Klassen
 * Marlon Cadell
 * Angelo Mavridis
 * Wael Eskeif
 * Luca Eberhardt

## **Thema**: *Projektplanung und besprechen von Randbedinungen*

### Ergebnisse

Projekt Planung:
* Ein zentraler Server
  * Client Server Verbindung: Mit Port Adapter System
  * Client sollen Singleplayer möglich sein

  * Server:
    * Hauptspiel läuft auf dem Server
    * Objektposition wird auf dem Server gespeichert und an die Clients weitergegeben
    * Spiele Logik wird auf dem Server berechnet
  * Clients:
    * Clients geben die Spieler inputs an den Server
    * Clients geben das Hauptspiel grafisch wieder
    * Clients mit der “Raylib” Bibliothek erstellen (optional)
* Erstmal nur eine Lobby pro Server
  * Eigenes Auto z.B. Rot
  * Alle Gegner Autos z.B. Blau
* Spielende:
  * Erster fährt über die Ziellinie
  * Danach Zeitlimit für die anderen Spieler z.B. 20 Sekunden
  * Gewinner despawnen
  * Endscreen während des Zeitlimits
  * Wenn alle spieler durch sind, vor ende des Zeitlimits wird das Spiel früher beendet
* Spielstart:
  * Startzähler von 5 bis 0, dann start
  * Erstmal nur 2 Spieler

Paketinhalt:
* Client sendet:
  * Spieler Eingaben
* Server sendet:
  * Fahrzeugpositionen


Optional Ideen:
* Highscore
* Lobby, start wenn alle bereit sind
* Zuschauermodus
* Start mit Ampel
* Bis zu 4 oder 8 Spieler
* Grafikeinstellungen


### Nächstes meeting

**2023-11-17 | 13:30 **
- Wöchentliches Meeting