FROM java:openjdk-8-jre-alpine

# MAINTAINER指令允许你给将要制作的镜像设置作者信息
MAINTAINER troylc <troylc@163.com>

ADD springboot_contoller-1.0-SNAPSHOT.jar /app.jar

EXPOSE 8888

ENTRYPOINT ["java","-jar","/app.jar"]

