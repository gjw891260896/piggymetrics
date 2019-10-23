FROM java:8-jre
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/account-service.jar /app/
CMD ["java", "-Xmx1000m", "-jar", "/app/account-service.jar"]

EXPOSE 6000
