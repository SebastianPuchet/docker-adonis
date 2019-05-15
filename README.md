# adonisjs-docker
A template for adonisjs api + mysql in docker

The docker-compose file use vars from the adonisjs `.env`

__Create `.env` file__

__Change host, db_connection in the `.env` file, create db_allow_empty_password and set it to `yes` (Setting this variable to yes is not recommended unless you really know what you are doing)__
```
HOST=0.0.0.0

DB_HOST=adonis-mysql
DB_CONNECTION=mysql
DB_ALLOW_EMPTY_PASSWORD=yes
```

## Start the environement :
```
docker-compose up -d
```

## Enter in the nodejs container :
```
docker exec -it appname /bin/bash
```
