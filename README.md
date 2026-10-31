# Docker Luncher APP

DSM launcher for container web applications with a shared NAS application list and read-only live monitoring.

## Why I built this

I built this app because I could no longer add direct links to my Docker container web interfaces in Synology DSM’s Container Manager. Docker Luncher APP gives me a central place to collect and open those links.

## Changes since 1.4.1

- Very small and ultra small tiles.
- Additional list and icon views.
- Detail window when clicking an application icon.
- Collapsible system overview in the upper-right corner.
- View selection and collapsed state are saved in the browser.
- Network and disk information removed from application tiles.
- CPU, RAM and status remain available.

## Download 1.4.5

[Download SPK 1.4.5](https://github.com/nemesis122/Docker_APPS-Luncher/releases/download/v1.4.5/docker-apps-monitor_noarch-1.4.5-0.spk) · [Release notes](https://github.com/nemesis122/Docker_APPS-Luncher/releases/tag/v1.4.5) · [Application icon](https://github.com/nemesis122/Docker_APPS-Luncher/releases/download/v1.4.5/docker-apps-icon.png)

## Checksums

[SHA256SUMS-1.4.5.txt](https://github.com/nemesis122/Docker_APPS-Luncher/releases/download/v1.4.5/SHA256SUMS-1.4.5.txt) contains SHA256 checksums for the SPK, all attached demo screenshots and the application icon.

SPK SHA256:
```text
a95079f1b1528c9e0967bf5affa9dea229d9ec797423d1c512008aca0dad2401
```

## Requirements and installation

Requires **DSM 7.2-64570 or later**, File Station and appropriate permissions. Live container data additionally requires Container Manager and appropriate permissions.

1. [Download SPK 1.4.5](https://github.com/nemesis122/Docker_APPS-Luncher/releases/download/v1.4.5/docker-apps-monitor_noarch-1.4.5-0.spk).
2. In DSM, open Package Center → Manual Install and select the SPK.
3. Open Docker Apps. The shared application list is stored in `docker/Docker APPS`.

## Features

Container import, CPU/RAM monitoring, available temperature readings, network rates, volume usage bars, tile/list/icon views, adjustable tile sizes, light and dark themes, German and English, JSON import/export and an offline icon library.

The package requests no root installation privileges and does not control containers.

## Test status

Tested locally with simulated DSM responses. Full compatibility has not been verified on real NAS hardware.

## Demo screenshots

All screenshots contain simulated demonstration data only, with no real NAS or user data.

### List view — light

![Docker Apps 1.4.5 list view — simulated demo data](https://github.com/nemesis122/Docker_APPS-Luncher/releases/download/v1.4.5/docker-apps-1.4.5-list-light.png)

### Icon view — dark

![Docker Apps 1.4.5 icon view — simulated demo data](https://github.com/nemesis122/Docker_APPS-Luncher/releases/download/v1.4.5/docker-apps-1.4.5-icons-dark.png)

Icons: [selfh.st/icons](https://github.com/selfhst/icons), CC BY 4.0, plus attributed additional logos. Detailed credits are bundled in the package.
