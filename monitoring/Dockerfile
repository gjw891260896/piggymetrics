FROM java:8-jre
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/monitoring.jar /app/
CMD ["java", "-Xmx1000m", "-jar", "/app/monitoring.jar"]

EXPOSE 8080
