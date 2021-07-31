# Database

## Create user

```mysql
CREATE USER learn IDENTIFIED BY 'learn';
GRANT ALL ON learn_node_login_api.* TO learn;
```

## Create database

```mysql
CREATE DATABASE learn_node_login_api DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;
```

## Drop database

```mysql
DROP DATABASE learn_node_login_api;
```

## Drop user

```mysql
DROP USER learn;
```