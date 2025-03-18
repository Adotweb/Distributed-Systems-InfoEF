---
id: info.zwischenbericht
aliases: []
tags: []
---

# Zwischenbericht 

**Erledigt:**
- [x] Relay server (mit node) läuft auf heim server instance (gehört mir) (Alim) 
- [x] Einfaches App Interface (nur grundgerüst und "test-strecke") mit tauri (luis)

**In bearbeitung**
- [>] Kommunkitationsstandard (+- fertig) für kommunikation mit servern (host->relay und relay->client) 
        als auch ein rest relay für einfache zwecke (Alim)
- [>] Funkionales app-interface und ui (Luis)


**Noch zu erledigen**
- [ ] App backend, verbindung mit servern (Alim)
- [ ] REST implementierung für relay server (Alim)

- [ ] UI/UX für app-interface (interaktion mit backend von Alim) (Luis)
- [ ] Docker backend, "starte Service x/lade service x von github herunter" (Luis)

## Bisherige Bemerkungen: 
- Tauri gibt sich schwerer als erwartet
- Bisher nicht besonders viel Zeit Aufgewendet (andere Schulsachen zu erledigen) 
- Zusammenarbeit erschwert aufgrund unterschiedlicher Stundenpläne (wird unbedingt verbessert! via discord etc.)

## Bisher gelernt/erarbeitet
**Luis** 
- NPM und package manager für svelte (in Zusammenhang mit tauri)
- Cross compilation für native Desktop Apps (in Zusammenhang mit tauri)


**Alim**
- Tauri und Rust im bezug auf native apps
- Dokumentieren und Standardisierung für eigene Prozesse (innere Kommunikation zwischen hosts <-> relay <-> client)


## Bisheriger Zeitaufwand: 
| Luis | Alim |
| ---- | ---- | 
| Tauri dokumentation einlesen und projekstart 1.5 h | Websocket Relay server in node 1.5h |
| | Kommunkitationsstandard Dokumentation (unfertig) 0.5 h | 
| 1.5 h | 2 h |

## Pläne
| Luis | Alim |
| ---- | ---- | 
| UI/UX für desktop App 1.5 - 2 h | Online Adminpanel 0.5 H |
| UI/UX bugfixes/redo's 2 h | Backend für desktop App 1.5 - 2 h| 
| Docker/evt Network ui/ux 1.5 - 2 h | Backend für docker App 1.5 - 2 h|
| | online Connection panel (zeigt connections und öffentliche/verfügbare websites) 2 - 3 h | 
| evtl. bugfixes 0 - 3 h | evtl. bugfixes 0 - 3 h |
| lokale Netzwerk Funktion| lokale Netzwerk Funktion|
| ca. 7 h | ca. 7 h |

| KW | Luis | Alim |
| --- | --- | --- | 
| 12 | Einfacher Desktop App Prototyp | Fertiger Kommunkitationsstandard |
| 13 | Docker Implementierung in der App | Fertiger relay server (REST und Websocket möglicherweise UDP/TCP ) | 
| 14 | github-connection funktion (github webhooks und herunterladen/ausführen von Repos/Projekten) | rust backend für Desktop App (flüssig + sicher) |
| Frühlingsferien | bugfixes | bugfixes |
| 16 | UI/UX überarbeiten | UI/UX überarbeiten (relay server) |
| 17 | local network connection | local network connection |
| 18 | Feinschliff | Feinschliff |
| 19 |  Projektpräsentation| Projektpräsentation |



[Fotos, Code, etc.](https://github.com/Adotweb/Distributed-Systems-InfoEF)
