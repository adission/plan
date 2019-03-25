linux系统操作postgresql数据库：
```
登陆postgres系统：
1、su - postgres
2、psql

更改数据库的用户：
alter database database_name OWNER TO postgres;
```

更改postgres用户的密码

create user postgres with password '123456';
1
更改postgres用户权限

alter user postgres superuser createrole createdb replication;
列出所有数据库：
\l