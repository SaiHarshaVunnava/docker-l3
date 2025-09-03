# Hands-On L3: Flask + Redis + Postgres (Docker Compose)

This repo contains a minimal multi-container app:
 **web**: Python Flask app
 **redis**: in-memory cache
 **postgres**: database (separate container run manually as per assignment)

## How to Run

```bash
# from the project folder
docker compose up
# open the app:
# http://localhost:8000
