## Docker-Postgres

Simple Docker project that runs Postgres database.

### How to run it?

First get this project on your local machine:

```
$ git clone https://github.com/wkrzywiec/docker-postgres.git
```

Next, in destination folder type following commands:

```
$ docker build -t test-postgres .
```

and then to run the container:

```
$ docker run -p 5432:5432 test-postgres
```

You should be able to connect to the database with following connectors:

- Host:       **localhost**
- Port:       **5432**
- Database:   **testdb**
- User:       **postgres**
- Password:   **postgres**