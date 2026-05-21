# Docker Start
<pr>


## Docker create/remove compose
```
docker compose up -d
docker compose down
```
## docker run/stop
```
docker compose start
docker compose stop
```
## Dump database
### Linux/wsl
```
docker exec -t <CONTAINER_NAME> pg_dump -U postgres <DATABASE_NAME> > dump.sql
```
### Windowns
```
docker exec -t <CONTAINER_NAME> pg_dump -U postgres <DATABASE_NAME> | Out-File dump.sql
```