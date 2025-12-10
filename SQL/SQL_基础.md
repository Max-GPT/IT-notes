## MySQL
SQL = Structured Query Language  结构化查询语句


A5M2 (エーゴエムツー)

### 注释
`-- SQL注释`

### 数据类型
`datetime` 时间不会根据时区变更

`timestamp` 时区信息

`char` 固定长度

`varchar` 可变长度


### 把 MySQL 注册成 Windows 的系统服务
```
cd C:\Program Files\MySQL\MySQL Server 8.0\bin

mysqld --install mysql
```

启动 MySQL：
```
net start mysql
```
停止 MySQL：
```
net stop mysql
```
查看服务状态：
```
sc query mysql
```