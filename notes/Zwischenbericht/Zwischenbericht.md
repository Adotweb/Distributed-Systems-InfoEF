---
id: info.zwischenbericht
aliases: []
tags: []
---

# Zwischenbericht

## Erledigt
- [x] Relay-Server (Node.js) läuft auf Heimserver-Instanz (Alim)
- [x] Einfaches App-Interface (Grundgerüst + "Test-Strecke") mit Tauri (Luis)

## In Bearbeitung
- [>] Kommunikationsstandard (ca. 80 % fertig) für:
  - Host → Relay
  - Relay → Client
  - REST-Relay für einfache Zwecke (Alim)
- [>] Funktionales App-Interface und UI (Luis)

## Noch zu erledigen
- [ ] App-Backend: Verbindung mit Servern (Alim)
- [ ] REST-Implementierung für Relay-Server (Alim)
- [ ] UI/UX für App-Interface (Interaktion mit Backend von Alim) (Luis)
- [ ] Docker-Backend: "Starte Service X / Lade Service X von GitHub herunter" (Luis)

## Bisherige Bemerkungen
- Tauri erweist sich als komplizierter als erwartet (vor allem bei der Kompilation unter Windows)
- Aufgrund schulischer Verpflichtungen bislang wenig Zeit investiert
- Zusammenarbeit erschwert durch unterschiedliche Stundenpläne (wird durch bessere Abstimmung via Discord optimiert)

## Bisher gelernt / erarbeitet

**Luis**
- Umgang mit NPM und Package-Management für Svelte (in Zusammenhang mit Tauri)
- Cross-Compilation für native Desktop-Apps (Tauri)

**Alim**
- Tauri und Rust im Bezug auf native Apps
- Dokumentation und Standardisierung für interne Prozesse (Kommunikation Host ↔ Relay ↔ Client)

Der bisherige Code ist hier zu finden und größtenteils fertig (Kommunikationsstandard zu ca. 80 %):
[GitHub Repository](https://github.com/Adotweb/connector_hub)

## Bisheriger Zeitaufwand

| Luis                                             | Alim                                                      |
| ------------------------------------------------ | --------------------------------------------------------- |
| Tauri-Dokumentation + Projektstart: 1.5 h        | WebSocket-Relay-Server in Node.js: 1.5 h                  |
|                                                  | Kommunikationsstandard-Dokumentation (unfertig): 0.5 h    |
| **Summe: 1.5 h**                                 | **Summe: 2 h**                                            |

## Pläne

| Luis                                                    | Alim                                                         |
| -------------------------------------------------------- | ------------------------------------------------------------ |
| UI/UX für Desktop-App: 1.5 - 2 h                         | Online-Adminpanel: 0.5 h                                     |
| UI/UX-Bugfixes / Redesigns: 2 h                          | Backend für Desktop-App: 1.5 - 2 h                           |
| Docker / ggf. Network-UI/UX: 1.5 - 2 h                   | Backend für Docker-App: 1.5 - 2 h                            |
| Eventuelle Bugfixes: 0 - 3 h                             | Online-Connection-Panel (zeigt Verbindungen & verfügbare Services): 2 - 3 h |
| Lokale Netzwerk-Funktion: 3 - 4 h                        | Lokale Netzwerk-Funktion: 3 - 4 h                            |
| **Gesamt: ca. 10 h**                                     | **Gesamt: ca. 10 h**                                         |

## Zeitplan

| KW               | Luis                                              | Alim                                                           |
| ---------------- | ------------------------------------------------- | -------------------------------------------------------------- |
| **12**           | Einfacher Desktop-App-Prototyp                    | Fertiger Kommunikationsstandard                                |
| **13**           | Docker-Integration in die App                     | Fertiger Relay-Server (REST + WebSocket, evtl. UDP/TCP)        |
| **14**           | GitHub-Connection (Webhooks + Download/Run Repos) | Rust-Backend für Desktop-App (performant & sicher)             |
| **Frühlingsferien** | Bugfixes                                          | Bugfixes                                                       |
| **16**           | UI/UX-Überarbeitung                               | UI/UX-Überarbeitung (Relay-Server)                             |
| **17**           | Lokale Netzwerk-Connection (Frontend-seitig)      | Lokale Netzwerk-Connection (Backend-seitig)                    |
| **18**           | Feinschliff                                       | Feinschliff                                                    |
| **19**           | Projektpräsentation                               | Projektpräsentation                                            |

Weitere Infos, Fotos & Code:  
[Projekt-Repository](https://github.com/Adotweb/Distributed-Systems-InfoEF)

## Endziel
Unser Ziel ist es, eine einfache Lösung bereitzustellen, um eigene Cloud-Dienste o. Ä. schnell und unkompliziert aufzusetzen.  
Beispiel: Lade unsere .exe herunter, öffne die App, wähle das GitHub-Repo aus, klicke auf den generierten Link – und fertig!


