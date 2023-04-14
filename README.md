# clamav-mirror-docker-vpn

The project runs dockerized database mirror for the Clam Antivirus.


## About the project
---

Uses the following micro service applications:

-   App clamav-mirror
-   App wireguard-client


## Pre-deployment preparation

---

Before deploying the project, install Docker, Docker Compose latest versions.


## Installation

---

**Important!!!**


For installation:
To install, run:

1. Do a git clone.

2. Create an .env file and fill with variables:

```bash
cp ./.env_template ./.env

```

3. Copy conf wireguard-client.

4. Run the project 

Production

```bash
docker-compose -f docker-compose.yaml up -d

```

5. After a couple of minutes, the service will start.


### Source code authors

---
Python script clamav-mirror-docker:
[Clamav python]( https://github.com/chmey/docker-clamav-mirror)