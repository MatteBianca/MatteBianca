# cantieri-app

[Italiano](#italiano) · [English](#english) · [Profilo](../README.md)

## Italiano

### Problema e contributo

Web-app interna per i cantieri: al posto del taccuino di carta, gli operai registrano ore, lavori, materiali e posizione da telefono o PC. L’amministrazione vede tutto in un unico posto.

**Tecnologie:** Node.js, Express, React, Vite, MySQL, JWT, Socket.io, Leaflet.

**Repository:** [MatteBianca/cantieri-app](https://github.com/MatteBianca/cantieri-app) (privato — codice sorgente senza dati aziendali).

### Funzionalità

- Cantieri: elenco, dettagli, note, scadenze
- Ore lavorate: inserimento, timer presenze, workflow di approvazione
- Magazzino: materiali e movimenti di stock
- QR e mappa: scansione QR e geolocalizzazione
- Ruoli: admin, project manager, operaio
- Chat interna e audit trail
- Budget e dashboard amministrativa
- PWA installabile e notifiche push (opzionali)

### Stack

| Layer | Tecnologie |
|-------|------------|
| Backend | Node.js, Express, MySQL, JWT, Socket.io |
| Frontend | React, Vite, React Router, Leaflet, Chart.js |
| Extra | PWA, Web Push, PDF/Excel export, upload file |

### Note

Progetto pensato per uso interno (impianti / cantieri). Nel repository non ci sono dati clienti, upload o backup.

---

## English

### Problem and contribution

Internal web app for construction sites: instead of paper notebooks, field workers log hours, tasks, materials and location from phone or PC. Administration sees everything in one place.

**Technologies:** Node.js, Express, React, Vite, MySQL, JWT, Socket.io, Leaflet.

**Repository:** [MatteBianca/cantieri-app](https://github.com/MatteBianca/cantieri-app) (private — source code only, no business data).

### Features

- Sites: list, details, notes, deadlines
- Worked hours: entry, attendance timer, approval workflow
- Warehouse: materials and stock movements
- QR and map: QR scan and site geolocation
- Roles: admin, project manager, worker
- Internal chat and audit trail
- Budget and admin dashboard
- Installable PWA and optional push notifications

### Stack

| Layer | Technologies |
|-------|--------------|
| Backend | Node.js, Express, MySQL, JWT, Socket.io |
| Frontend | React, Vite, React Router, Leaflet, Chart.js |
| Extra | PWA, Web Push, PDF/Excel export, file uploads |

### Notes

Built for internal company use (electrical / construction work). The repository contains source code only — no client data, uploads or backups.
