# MultiModelDemo


```bash
docker-compose -f docker-compose-mysql.yml up -d
```

```bash
docker-compose -f docker-compose-streamset.yml up -d
```

http://localhost:18630

```bash
docker cp data mysql:home/data
```
```bash
docker exec -it mysql bash

cd /home/data/
mysql
CREATE DATABASE demo;
use demo;

source killrmovies_mysql_dump.sql
```
