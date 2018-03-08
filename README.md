# docker-helper 常用的docker命令

## 说明
  ${} 表示占位符，实际使用中按照用户需求进行配置

## 常用docker启动容器命令
  启动mysql： docker run --name mysql-ishangchi -p 3306:3306 -v /data/docker/mysql-ishangchi:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=dev77621 -d mysql --character-set-server=utf8mb4 --collation-server=utf8mb4_unicode_ci
