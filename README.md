# 常用的docker命令

## 说明
  ${} 表示占位符，实际使用中按照用户需求进行配置
  
## 网站资源
  https://hub.docker.com/ 官方镜像仓库，能在这里找到很多有用的镜像及具体的使用方式
  https://docs.docker.com/ docker 文档中心，docker入门及熟悉api的好地方
  
## 常用docker启动容器命令
  启动mysql： docker run --name ${pwd} -p 3306:3306 -v ${dir}:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=${pwd} -d mysql --character-set-server=utf8mb4 --collation-server=utf8mb4_unicode_ci
