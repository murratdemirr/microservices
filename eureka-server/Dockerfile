FROM java:8-jre
MAINTAINER Murat Demir <murrat.demirr@gmail.com>

ADD ./target/eureka-server.jar /app/
CMD ["java", "-Xmx100m", "-jar", "/app/eureka-server.jar"]

EXPOSE 8761