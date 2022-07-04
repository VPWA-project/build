# Semester project - application for text communication in IRC style (Slack)

## Getting Started
1. Clone this repository:
```
https://github.com/VPWA-project/build.git
```

2. Configure ./backend/.env or rename ./backend/.env.example to ./backend/.env

3. Build docker images:
```
docker-compose up
```

4. Run migrations and seeders:
```
docker exec -ti vpwa_backend node ace migration:fresh
docker exec vpwa_backend node ace db:seed
```

5. Open [localhost](http://localhost:8080)
- admin account:
    - email: admin@gmail.com
    - password: password