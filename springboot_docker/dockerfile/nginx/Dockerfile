# 设置docker镜像来源nginx
FROM nginx

# MAINTAINER指令允许你给将要制作的镜像设置作者信息
MAINTAINER troylc <troylc@163.com>

#拷贝配置到nginx程序配置目录
COPY nginx.conf /etc/nginx/nginx.conf
COPY default.conf /etc/nginx/conf.d/default.conf

RUN mkdir -p /etc/nginx/logs
RUN echo "Asia/shanghai" > /etc/timezonedo

#EXPOSE指令用来告诉Docker这个容器在运行时会监听哪些端口 80
EXPOSE 80
