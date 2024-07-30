# PIO ULB Editor
[English version](./README_EN.md)
## CareRegio
Ziel des Verbundprojekts CARE REGIO ist es, nachhaltige Konzepte für eine digital unterstützte Pflege zu entwickeln.  Pflegekräfte und pflegende Angehörige sollen spürbar entlastet sowie Pflegebedürftige in ihrer Selbständigkeit unterstützt werden.

CARE REGIO ist ein Verbundprojekt, das vom Bayerischen Staatsministerium für Gesundheit und Pflege gefördert wird.

## DigiPÜB
Die Technische Hochschule Augsburg analysiert in enger Zusammenarbeit mit dem Universitätsklinikum Augsburg die Datenübertragung im Rahmen des Entlass- und Überleitungsprozesses. Fokussiert wird hierbei die Digitalisierung des Pflegeüberleitungsberichtes, kurz DigiPÜB.

## 1. Voraussetzungen
Um das Projekt mithilfe des quickstart scripts zu starten wird Docker benötigt.

Mit Docker wird das Projekt in sogenannten Docker Containern ausgeführt.  
Eine Datenbank, das Backend sowie das Frontend werden automatisch hochgefahren und sind dann im Browser erreichbar.  
Hierfür muss Docker auf dem Rechner installiert sein.
- [Docker](https://www.docker.com/products/docker-desktop)
- Anleitungen
  - [Windows](https://docs.docker.com/docker-for-windows/install/#start-docker-for-windows)
  - [Linux](https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user)
  - [MacOS](https://docs.docker.com/docker-for-mac/install/#install-and-run-docker-desktop-on-mac)

Nach Herunterladen der Docker Desktop Anwendung bitte installieren und anschließend starten. Danach kann mit [2. Quick Start](#2-quick-start) weitergemacht werden.

## 2. Quick Start
Das Projekt kann mit hilfe einer `docker-compose.yml` datei gestartet werden, wodurch alle benötigten container automatisch heruntergeladen werden, dafür ist eine Internt verbindung nötig!

Mit dem Befehl `docker compose up` kann die `docker-compose.yml` ausgeführt werden.

Anschließend ist der PIO ULB Editor im Browser unter folgender URL erreichbar: http://localhost.


## Lizenzierung
Der PIO ULB Editor ist lizenziert mit Apache-Lizenz, Version 2.0.  
Siehe [License](./LICENSE) für den gesamten Lizenztext.