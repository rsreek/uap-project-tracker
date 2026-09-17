# UAP Project Tracker

Simple HTML/Flask/SQLite tracker for Cequence UAP customer deployments.

## Run with Docker

```bash
docker compose up -d --build
```

Open:

http://localhost:8080

## Stop

```bash
docker compose down
```

Project data is stored in `data/tracker.db`.

## GitHub

```bash
git init
git add .
git commit -m "Initial UAP project tracker"
git branch -M main
git remote add origin <YOUR_GITHUB_REPO_URL>
git push -u origin main
```
