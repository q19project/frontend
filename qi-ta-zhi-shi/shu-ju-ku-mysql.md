# 数据库-MySQL

### 新建用户

```sql
CREATE USER 'USERNAME'@'HOSTNAME' IDENTIFIED BY 'PASSWORD';
```

### 给用户赋予（grant）权限

```sql
GRANT ALL ON DATABASE.TABLE TO 'USERNAME'@'HOSTNAME';
```

