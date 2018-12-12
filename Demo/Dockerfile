FROM openjdk:8-jre
MAINTAINER Sri Sainath J.O. <srisainath@gmail.com>
VOLUME /tmp
ADD target/demo-0.0.1-SNAPSHOT.jar sreenu-docker-app.jar
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /sreenu-docker-app.jar" ]