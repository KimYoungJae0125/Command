# MySQL

## Server
### 서버 시작
### Mac OS
```shell
$ mysql.server start
```
### 서버 종료
### Mac OS
```shell
$ mysql.server stop
```

### 상태 확인
### Mac OS
```shell
$ mysql.server status
```

### login
```shell
$ sudo mysql -u root -p
$ Password : <컴퓨터 비밀번호>
```

## Databases
### Database 확인
```shell
$ MariaDB [(none)] > show databases
```
```shell
+--------------------+
| Database           |
+--------------------+
| information_schema |
| mysql              |
| performance_schema |
| sys                |
| test               |
+--------------------+
5 rows in set (0.003 sec)
```
### Database 생성
```shell
$ MariaDB [(none)] > create database <databaseName>
```
```shell
Query OK, 1 row affected (0.001 sec)
```

### Database 사용
```shell
$ MariaDB [(none)] > use <databaseName>
```
```shell
Database changed

$ MariaDB [(databaseName)] >
```