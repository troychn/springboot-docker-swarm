# 设置docker镜像来源mysql
FROM mysql

# MAINTAINER指令允许你给将要制作的镜像设置作者信息
MAINTAINER troylc <troylc@163.com>

# 拷贝当前目录下的device.sql,exceute-sql.sh,docker-entrypoint.sh到根目录下
COPY city-db.sql /docker-entrypoint-initdb.d/city-db.sql
COPY city-data.sql /docker-entrypoint-initdb.d/city-data.sql
COPY my.cnf /etc/mysql/my.cnf

#修改.sh文件的权限

RUN echo "Asia/shanghai" > /etc/timezone


EXPOSE 3306

