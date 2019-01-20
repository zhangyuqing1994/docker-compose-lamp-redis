# docker-compose-lamp-redis
该项目为 docker-compose管理  docker 容器引擎，该环境是lamp ， 共有三个容器 分别是：httpd-php，mysqld，redis ，通过 dockerfile 在 centos6.5 基础上 安装服务 并 build 生成 镜像，然后通过 docker-compose 管理 镜像 生成容器 做一些容器层的管理和配置相关工作 
