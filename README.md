# Angular Aufbau · Teilnehmerunterlagen

Unterlagen zur Schulung **„Angular Aufbau“** (23.–25.11.2026) mit Angular 22.

- **[Angular_Aufbau_Handbuch_4.0.pdf](Angular_Aufbau_Handbuch_4.0.pdf):** das Handbuch zur Schulung
- **[Angular_Aufbau_Startprojekt.zip](Angular_Aufbau_Startprojekt.zip):** das CRM-Projekt zu Beginn, mit einer Login-Seite ohne Logik
- **[Angular_Aufbau_Endprojekt.zip](Angular_Aufbau_Endprojekt.zip):** das CRM-Projekt am Ende – Standalone-Feature-Architektur mit Lazy Loading, Unit-Tests mit Vitest und ng-mocks, NgRx SignalStore für Kunden und Anmeldung, Signal Forms für das Kundenformular, Login mit Reactive Forms, funktionale Guards und E2E-Tests mit Playwright

## Projekt starten

ZIP entpacken, dann in zwei Terminals:

```bash
# Terminal 1 – Backend
cd angular-aufbau/backend
npm install
npm start          # http://localhost:3001/customers
```

```bash
# Terminal 2 – Frontend
cd angular-aufbau/frontend
npm install
npm start          # http://localhost:4200
```

Voraussetzung: Node.js 22.22 oder 24.15 oder neuer. Weitere Befehle und den Aufbau des Projekts beschreibt die `README.md` im entpackten Ordner.
