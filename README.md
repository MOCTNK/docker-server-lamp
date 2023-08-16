### Usage
```bash
$ cd docker/
$ docker-compose up -d 
```
App - http://localhost:8180/

### Stop
```bash
$ cd docker/
$ docker-compose down 
```

### DataBase MySQL

- `Host`: mysql
- `User`: root
- `Password`: 123

Use PhpMyAdmin - http://localhost:8181/

OR
```bash
$ cd docker/
$ docker-compose exec mysql bash
$ mysql -u root -p
```