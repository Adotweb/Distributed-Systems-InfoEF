# Sprint 1 



## Benötigte Konzepte
| Theorie | Software | Hardware |
|---|---|---|
| Netzwerke, DNS, Firewalls umgehen | CF Tunnels, Docker, GitHub Hooks, Bash/powershell | Evt. Raspberry pi, Linux/Windows Software | 


## Erste Spring Versionierung

### Erste lauffähige version
Einzelner Client ansteuerbar via CF tunnels und "hot reloadable" server Architektur mit bash/pwsh Skripten. 

### Docker Funktionalität
Client mit containerisiertem (Dockerized) service, so dass system variabeln nicht einzeln eingegeben werden müssen

### Automatisierung mit GitHub hooks
Client erweitern so dass er auf das pushen auf GitHub reagiert, nützliches interface über eine art admin seite exposen, so dass man mit klicken server deployen kann.

### Mehrere services
Kubernetes, bash scripts o.ä.

### Mehrere clients
System zum Loadbalancing, client interner kommunikationschannel
