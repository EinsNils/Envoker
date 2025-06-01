
# 🧙‍♂️ Envoker

**Envoker** ist dein magischer Desktop-Assistent für DevOps – eine Electron-basierte Anwendung, mit der du lokale Entwicklungsumgebungen einfach aufsetzen und verwalten kannst.  
Ob Docker, Kubernetes, Datenbanken oder Migrationstools – _Envoker_ macht dein Setup schnell, übersichtlich und klickbar.

---

## 🚀 Features

- 🐳 **Docker Wizard**
  - Templates für Compose-Projekte (PostgreSQL, Redis, RabbitMQ, uvm.)
  - Start/Stopp über UI
  - .env-Datei Editor

- 📦 **DB Installer & Migrationstools**
  - Lokales Setup für PostgreSQL, MySQL, MongoDB
  - Flyway-Support (Migrationsdateien erstellen & ausführen)
  - SQL-Migrationen versionieren

- ☸️ **Kubernetes Shortcuts**
  - Minikube, Kind oder K3s lokal starten/stoppen
  - Clusterstatus anzeigen
  - Helm-Charts deployen
  - Ingress + TLS (mkcert) per Klick einrichten

- 🔐 **Security Setup**
  - TLS-Zertifikate generieren (self-signed oder mkcert)
  - Zugriffsschutz für lokale Services via Traefik

- 🧩 **Snippet- & Template-Verwaltung**
  - Eigene Compose/K8s-Templates speichern
  - Shell/Bash-Snippets speichern + ausführen

- 🖥️ **Terminal-Ausgabe in der UI**
  - Ausgabe von `docker`, `kubectl`, `flyway` & Co. in der App anzeigen

---

## 🛠️ Technologie-Stack

- **Plattform:** Electron
- **Frontend:**  React 
- **Integration:** Shell Commands, Config-Dateien, System-Kommandos

---

## 📦 Installation (Entwicklung)

---
