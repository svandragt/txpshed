# TXP Docker
A TextPattern Docker setup.

## Setup

- Install the latest version of TextPattern in the `src/` directory so that `src/css.php` exists. 
- Add your own database credentials to a .env file:
```
MYSQL_ROOT_PASSWORD=root-password
MYSQL_DATABASE=app
MYSQL_USER=app
MYSQL_PASSWORD=app-password
```
- Run `docker-compose up` and load up http://localhost:8080/textpattern/setup/
