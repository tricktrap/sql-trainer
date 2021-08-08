# SQL-Trainer

Quick and dirty playground for learning SQL.

### Setup

Grab a copy of the imdb_full database dump (see [https://relational.fit.cvut.cz/dataset/IMDb](https://relational.fit.cvut.cz/dataset/IMDb))
```
docker run mariadb mysqldump --databases imdb_full --host relational.fit.cvut.cz -u guest -p"relational" > data/imdb.sql
```

Start up MariaDB server on the local machine in a container
```
docker-compose up -d
```
