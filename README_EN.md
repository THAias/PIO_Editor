# PIO ULB Editor
[Deutsche version](./README.md)
## CareRegio
The goal of the collaborative project CARE REGIO is to develop sustainable concepts for digitally supported care. Caregivers and family members providing care should be noticeably relieved, and those in need of care should be supported in their independence.

CARE REGIO is a collaborative project funded by the Bavarian State Ministry of Health and Care.

## DigiPÜB
The Technical University of Augsburg, in close collaboration with the Augsburg University Hospital, is analyzing data transmission within the context of the discharge and transition process. The focus is on the digitization of the nursing transition report, abbreviated as DigiPÜB.

## 1. Prerequisites
To start the project using the quickstart script, Docker is required.

With Docker, the project runs in so-called Docker containers.
A database, the backend, and the frontend are automatically started and can be accessed through the browser.
Docker must be installed on the computer.
- [Docker](https://www.docker.com/products/docker-desktop)
- Instructions
    - [Windows](https://docs.docker.com/docker-for-windows/install/#start-docker-for-windows)
    - [Linux](https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user)
    - [MacOS](https://docs.docker.com/docker-for-mac/install/#install-and-run-docker-desktop-on-mac)

After downloading the Docker Desktop application, please install and then start it. Afterward, you can proceed with [2. Quick Start](#2-quick-start).

## 2. Quick Start

The project can be easily started using the respective `docker-compose.yml` file which automatically downloade all relevanted container, an internet connection is required!

The `docker-compose.yml` can be executed with the command `docker compose up`

After that, the PIO ULB Editor can be reached in the browser with the following URL: http://localhost.


## Licensing
The PIO ULB Editor is licensed under the Apache License, Version 2.0.  
See [License](./LICENSE) for the full license text.
