## Setup

```shell
npm init
npm install mysql2 sequelize
```

## Setup Database

```shell
mysql -u root
```

```mysql
create database ztest;
create user zuser identified by 'zpass';
grant all privileges on ztest to zuser;
```


