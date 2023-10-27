## nacos 单机模式

# 初始化 MySQL

- 创建 MySQL Database 为 `MYSQL_SERVICE_DB_NAME` 配置的值：`nacos_devtest`
- 使用 `mysql-schema.sql` 脚本初始化 `nacos_devtest`
- 执行 `kubectl apply -f deployment.yaml`