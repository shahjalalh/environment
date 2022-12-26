# An integrated environment.

Environment
- VS Code Container
- Docker
- Django
- Postgres & PgAdmin
- Node
- MongoDB(pending...)
- GraphQL(pending...)
- Redis(pending...)
- Elasticsearch, Logstash, and Kibana(ELK)(pending...)
- ...


db_dump source: https://www.postgresqltutorial.com/postgresql-getting-started/postgresql-sample-database/

```
$ docker-compose up --build
$ docker-compose down
```

Open in VSCode
> Run ```docker-compose up``` in terminal
> Attach to Running Container
> May need to adjust workspace ```/workspace```

Switch User in the container
```
$ su adi
```

Creating Virtual Env, activate and deactivate
```
$ python -m venv py3env
$ source py3env/bin/activate
```

Close in VSCode
> Close Remote Container