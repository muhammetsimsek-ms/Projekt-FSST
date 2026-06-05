# RFID-Gesten-Fenstersteuerung

## Projektbeschreibung

Dieses Projekt wurde im Rahmen des FSST-Unterrichts entwickelt und demonstriert ein RFID-basiertes Zugangssystem mit Gestensteuerung auf einem Raspberry Pi 5.

Nach erfolgreicher Authentifizierung über einen RFID-Chip wird die Kamera aktiviert. Anschließend kann das Fenster mithilfe von Handgesten gesteuert werden. Der aktuelle Zustand des Fensters wird über einen NeoPixel-LED-Streifen visualisiert und zusätzlich in einer Weboberfläche angezeigt.

---

## Funktionen

* RFID-Zugriffskontrolle
* Benutzerverwaltung mit SQLite-Datenbank
* Gestenerkennung über Kamera
* Fenstersteuerung durch Handgesten
* NeoPixel-LED-Anzeige für Fensterzustände
* Webdashboard zur Überwachung und Steuerung
* Ereignisprotokollierung
* Health-Check für Systemkomponenten

---

## Verwendete Hardware

* Raspberry Pi 5
* Raspberry Pi Camera Module 3
* 2 × RC522 RFID-Reader
* RFID-Chips/Karten
* NeoPixel LED-Streifen
* Jumper-Kabel und Steckplatine

---

## Verwendete Software

* Python
* Flask
* SQLite
* SQLAlchemy
* OpenCV
* MediaPipe
* Picamera2
* HTML / CSS / JavaScript

---

## Funktionsablauf

1. Ein Benutzer hält seinen RFID-Chip an den Reader.
2. Das System überprüft die Berechtigung in der Datenbank.
3. Bei erfolgreicher Authentifizierung wird die Kamera aktiviert.
4. Die Kamera erkennt Handgesten des Benutzers.
5. Eine offene Hand öffnet das Fenster.
6. Eine Faust schließt das Fenster.
7. Der aktuelle Zustand wird über LEDs und das Webdashboard angezeigt.

---

## Webdashboard

Das Dashboard ermöglicht:

* Anzeige des aktuellen Fensterstatus
* Verwaltung von Benutzern
* Aktivieren und Deaktivieren von Benutzern
* Hinzufügen und Entfernen von Benutzern
* Anzeige der Ereignisprotokolle
* Manuelle Steuerung des Fensters
* Anzeige des Kamerabildes
* Überprüfung des Systemstatus

---

## Projektteam

### Muhammet Simsek

* Gestenerkennung
* Kamerafunktion


### Benjamin

* Raspberry-Pi-Einrichtung
* RFID-Testaufbau
* Hardwareintegration
* Systemtests
* RFID-Zugriffssteuerung
* Systemintegration

---

## Projektstatus

✅ Abgeschlossen


Dieses Repository dient der Dokumentation und Versionsverwaltung des Projekts.
