FROM openjdk:8-jre-alpine

ENV SPRING_OUTPUT_ANSI_ENABLED=ALWAYS

ADD *.war /app.war

VOLUME /tmp
EXPOSE 6000
CMD java -Djava.security.egd=file:/dev/./urandom -jar /app.war
