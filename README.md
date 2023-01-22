# Dockwell &middot; ![Github Repo Size](https://img.shields.io/github/repo-size/oslabs-beta/Dockwell) ![GitHub License](https://img.shields.io/github/license/oslabs-beta/Dockwell) ![GitHub Commit](https://img.shields.io/github/last-commit/oslabs-beta/Dockwell) ![GitHub Stars](https://img.shields.io/github/stars/oslabs-beta/Dockwell)

---

## About

---

Dockwell is an intuitive and comprehensive GUI that tracks, monitors, and displays all of a user's Docker containers. 

We made Dockwell so that developers can quickly visualize container metrics to assist in their debugging and development process.

With the needs of developers in mind, Dockwell uses Prometheus and cAdvisor to scrape real-time metrics from the host machine, all from its own containerized environment.

Dockwell is an open source project and we would love to hear your feedback!

## Table of Contents

Application usage/documentation

- [Features](#features)
- [Prerequisites](#prerequisites)

Installation guides

- [Installation](#installation)

Contributers and other info

- [Contributers](#contributers)
- [Made With](#made-with)
- [How to Contribute](#how-to-contribute)

## Features:

---

- Memory and CPU usage data are displayed graphically for each individual container. 
- Memory and CPU usage data for *all containers* are also displaed so that users can quickly compare metrics
<!-- Live reloading of metric data displayed by individual container or all containers at once, in simple to read charts. -->

- The right side of the interface displays all of a users active and inactive containers with the functionality to start, pause, unpause, and kill containers.

<!-- System metrics section which displays how much CPU and Memory Docker is currently using from the host machine, as well as by container. -->
- The left side of the interfece displays a breakdown of memory and CPU usage. 
  - A liguid guage shows the percent of each metric being used by all containers
  - A pie chart depicts the ratio metric usage by container
  
  
- All charts are dynamic and update every 1000ms
<!-- Logs section that allows a user to check and refresh the logs from each container's environment. -->

[↥Back to top](#table-of-contents)

## Prerequisites:

---

- The host computer running Dockwell must have:

  - A Docker  [Account](https://www.docker.com/ 'Download Docker')
  
  - Hopefully at least a few containers (idk?)

  [↥Back to top](#table-of-contents)

## Installation:

---

- prolly something like download from docker hub and docker compose up..... i frigging hope

[↥Back to top](#table-of-contents)

## Contributors

---

- Kyle Saunders[LinkedIn] | [Github]
- Sami Messai[LinkedIn] | [Github]
- Aalok Shah[LinkedIn] | [Github]
- Josh Paynter[LinkedIn] | [Github]

[↥Back to top](#table-of-contents)

## Made With


***
### FrontEnd
![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white)
### BackEnd
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
### Monitoring and Data Visualization
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)

[↥Back to top](#table-of-contents)
## How to Contribute

---

Contributions are always welcome!
Do whatever u want idgaf really! i know im fresh

[↥Back to top](#table-of-contents)
