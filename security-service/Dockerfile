FROM java:8-jre
MAINTAINER Murat Demir <murrat.demirr@gmail.com>

ADD ./target/security-service.jar /app/
CMD ["java", "-Xmx100m", "-jar", "/app/security-service.jar"]

EXPOSE 5000

