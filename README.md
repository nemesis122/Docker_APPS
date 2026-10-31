# Docker Luncher APP

DSM launcher for container web applications with a shared NAS app list and read-only live monitoring.

## Why I built this / Warum ich diese App entwickelt habe

I built this app because I could no longer add direct links to my Docker container web interfaces in Synology DSM’s Container Manager. Docker Luncher APP gives me a central place to collect and open those links.

Ich habe diese App entwickelt, weil ich im Container Manager von Synology DSM keine direkten Links zu den Weboberflächen meiner Docker-Container mehr anlegen konnte. Mit Docker Luncher APP kann ich diese Links wieder zentral sammeln und öffnen.

## Änderungen seit 1.4.1

- Sehr kleine und ultra kleine Kacheln.
- Zusätzliche Listen- und Symbolansicht.
- Detailfenster beim Anklicken eines Symbols.
- Einklappbare Systemübersicht oben rechts.
- Ansicht und Klappzustand werden im Browser gespeichert.
- Netzwerk-/Disk-Angaben aus den App-Kacheln entfernt.
- CPU, RAM und Status bleiben verfügbar.

## Download 1.4.5

[Download SPK 1.4.5](https://github.com/nemesis122/Docker_APPS-Luncher/releases/download/v1.4.5/docker-apps-monitor_noarch-1.4.5-0.spk) · [Release 1.4.5](https://github.com/nemesis122/Docker_APPS-Luncher/releases/tag/v1.4.5)

![Docker Apps 1.4.5 – Symbolansicht, simulierte Demodaten](https://github.com/nemesis122/Docker_APPS-Luncher/releases/download/v1.4.5/docker-apps-1.4.5-icons-dark.png)

![Docker Apps 1.4.5 – Listenansicht, simulierte Demodaten](https://github.com/nemesis122/Docker_APPS-Luncher/releases/download/v1.4.5/docker-apps-1.4.5-list-light.png)

[SHA256 checksums / Prüfsummen](https://github.com/nemesis122/Docker_APPS-Luncher/releases/download/v1.4.5/SHA256SUMS-1.4.5.txt) · [App icon](https://github.com/nemesis122/Docker_APPS-Luncher/releases/download/v1.4.5/docker-apps-icon.png)

SPK SHA256: `a95079f1b1528c9e0967bf5affa9dea229d9ec797423d1c512008aca0dad2401`

The screenshot shows version 1.4.5 and contains fictional demonstration data only.

Features: container import, CPU/RAM monitoring, temperature, network rates, volume usage bars, tile/list/icon views, adjustable tiles, light/dark themes, German/English, JSON import/export and an offline icon library.

Shared app list: `docker/Docker APPS`. Requires DSM 7.2-64570 or later, File Station and appropriate permissions. Live container data additionally requires Container Manager permissions.

## Installation

1. Download the SPK 1.4.5 above.
2. In DSM, open Package Center → Manual Install and select the SPK.
3. Open Docker Apps.

## Teststatus / Test status

Lokal mit simulierten DSM-Antworten geprüft. Keine vollständige Kompatibilitätsprüfung auf echter NAS-Hardware.

Tested locally with simulated DSM responses; no full compatibility verification on real NAS hardware.

The package requests no root installation privileges and does not control containers.

Icons: [selfh.st/icons](https://github.com/selfhst/icons) (CC BY 4.0), plus attributed additional logos. Detailed credits are bundled in the package.
