# Semester project - application for text communication in IRC style (Slack)

## Getting Started
1. Clone this repository:
```
https://github.com/VPWA-project/build.git
```

2. Build docker images:
```
docker-compose up
```

3. Run migrations and seeders:
```
docker exec -ti vpwa_backend node ace migration:fresh
docker exec vpwa_backend node ace db:seed
```