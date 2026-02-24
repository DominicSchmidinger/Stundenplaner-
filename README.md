StundenPlaner+ 📅🤖
StundenPlaner+ ist eine KI-gestützte Cloud-Lösung zur automatisierten Erstellung von Stundenplänen an Schulen. Das System löst den „Stundenplan-Wahnsinn“, indem es komplexe Abhängigkeiten von über 90 Klassen und 350 Lehrkräften effizient koordiniert.

🚀 Das Problem
Die manuelle Planung von Schulstunden ist fehleranfällig und führt oft zu „unmenschlichen“ Plänen mit extremen Freistunden oder suboptimaler Raumnutzung. Besonders die Koordination von Spezialräumen (EDV, Labore) stellt Verwaltungen vor große Herausforderungen.

✨ Kernfunktionen
KI-Generator: Erstellt automatisch optimierte, konfliktfreie Stundenpläne unter Berücksichtigung von „humanen“ Faktoren.

Sokrates-Integration: Nahtloser Import von Stammdaten (Lehrer, Schüler, Klassen) über eine XML/CSV-Schnittstelle.

Intelligente Raumverwaltung: Automatische Zuweisung von Fachräumen basierend auf Kapazität und Ausstattung.

Vertretungsmanagement: Schnelle Vorschläge für Supplierstunden bei kurzfristigen Ausfällen.

Cross-Platform GUI: Barrierefreies Dashboard für Administratoren und mobile Ansichten für den täglichen Abruf durch Lehrer und Schüler.

🛠 Tech Stack
Backend: Python / Node.js (KI-Logik & REST-API)

Frontend: React / Next.js (Responsive Web-App)

Datenbank: PostgreSQL / MongoDB (Sichere Datenhaltung nach DSGVO)

Infrastruktur: Docker & Cloud-Hosting

📋 Projektstruktur (PSP)
Das Projekt ist in 6 Hauptarbeitspakete unterteilt:

Analyse: Anforderungsdefinition & KI-Constraints.

KI-Engine: Entwicklung des Core-Scheduling-Algorithmus.

Integration: Bau der Sokrates-Schnittstelle.

Frontend: Implementierung der Web- & Mobile-Oberflächen.

QA: Umfangreiches Testing & Performance-Optimierung.

Rollout: Dokumentation und Release.

🔐 Sicherheit
Datenschutz hat höchste Priorität. Alle personenbezogenen Daten werden nach DSGVO-Standard verschlüsselt übertragen und gespeichert. Ein rollenbasiertes Zugriffskonzept (RBAC) stellt sicher, dass Nutzer nur die für sie relevanten Daten sehen.
