# TXP Docker
A TextPattern Docker setup.

## Setup

- Install the latest version of TextPattern in the `src/` directory so that `src/css.php` exists. 
- Add your own database credentials to a `.env` file:
  
```
MYSQL_USER=app
MYSQL_PASSWORD=app-password
MYSQL_DATABASE=app

# Not required for install
MYSQL_ROOT_PASSWORD=root-password

```
- Run `docker-compose up` and load up http://localhost:8080/textpattern/setup/. Changet the database host to the docker container name, for example `txpshed_mysql_1`.
