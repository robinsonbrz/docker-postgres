# docker-postgres


.env sample

```
DB_NAME=dbname
DB_USER=dbuser
DB_PASSWD=dbpassword
```


## Acessando o container
```bash
docker exec -it db_postgres_rob psql -U postgresrob -d postgres
```

## pelo host externo ao container
```bash
psql -h 127.0.0.1 -U postgresrob -d postgres
```