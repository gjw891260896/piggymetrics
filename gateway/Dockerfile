FROM java:8-jre
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/gateway.jar /app/
CMD ["java", "-Xmx1000m", "-jar", "/app/gateway.jar"]

EXPOSE 4000
