# MySQL Docker Template

1) Create `.env` file with this content

````
MYSQL_ROOT_PASSWORD=
MYSQL_ROOT_HOST=
MYSQL_LOG_CONSOLE=1
MYSQL_DATABASE=sakila
MYSQL_USER=dba
MYSQL_PASSWORD=123
````

2. Start

````
$ docker-compose up -d
$ docker logs --follow mysql.treeipe.com
````

3. Access

````
$ docker exec -it mysql.treeipe.com mysql -udba -p123
````