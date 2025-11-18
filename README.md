# 📚 Buchverwaltungssystem – Java OOP Projekt

Ein Java-basiertes Buchverwaltungssystem mit klarer Schichtenarchitektur (DAO – Service – UI) und Unit-Tests.  
Das Projekt wurde entwickelt, um Konzepte wie objektorientierte Programmierung, Datenzugriffsschichten, Service-Logik und testgetriebene Entwicklung zu demonstrieren.

---

## 🚀 Features

- Bücher **erstellen**, **anzeigen**, **aktualisieren** und **löschen** (CRUD)
- Konsolenmenü (UI) zur Bedienung
- Daten werden über eine DAO-Schicht verarbeitet
- Service-Layer mit Validierung und Geschäftslogik
- Unit-Tests für DAO, Service und UI
- Saubere Architektur in getrennten Paketen



## 🧱 Projektarchitektur

Das Projekt folgt einer klaren Schichtenstruktur:

src/
├── dao/ # Interfaces für Datenzugriff
├── impl/ # Implementierungen (z. B. Datei oder Fake-DB)
├── pojo/ # POJO Klassen (z. B. Buch)
├── service/ # Business-Logik
├── verbindung/ # Datenbank-/Dateiverbindungen
├── ui/ # Konsolen-UI
├── test/ # JUnit Tests
└── main/ # Einstiegspunkt der Anwendung


---

## 🛠️ Verwendete Technologien

- Java (OOP)
- DAO/Service Architektur
- JUnit 5 für Tests
- Optional: Datei- oder Datenbankspeicherung

---

## ▶️ Anwendung starten

### **Kompilieren und Starten**
Im Projektordner:

```bash
cd src/main
javac Main.java
java Main

Tests ausführen

Das Projekt enthält Unit-Tests:

DAO-Tests

Service-Tests

UI-Tests

Verbindungs-Tests

Beispiel-Buchobjekt
Buch buch = new Buch(
    1,
    "Der Alchimist",
    "Paulo Coelho",
    1988,
    "978-0061122415"
);
Was ich mit diesem Projekt gelernt habe

saubere objektorientierte Java-Programmierung

Arbeiten mit Interfaces (DAO-Muster)

Trennung von Logik & Datenzugriff (Service Layer)

Fehlerbehandlung & Validierung

Testgetriebene Entwicklung mit JUnit

Konsolenanwendungen strukturieren


Mögliche Erweiterungen

Migration zu Spring Boot

REST-API statt Konsolen-UI

MySQL oder PostgreSQL als echte Datenbank

Frontend mit React oder HTML

Docker-Deployment

GUI (JavaFX oder Web-Frontend)

Dieses Projekt kann frei verwendet und erweitert werden.
