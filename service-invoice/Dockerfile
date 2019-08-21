FROM openjdk:11.0.2-jre-slim
COPY target/service-invoice.jar .
EXPOSE 8080
CMD /usr/bin/java -Xmx400m -Xms400m  -XX:TieredStopAtLevel=1 -noverify -jar service-invoice.jar
