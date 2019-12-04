FROM java:8
VOLUME /tmp
ADD out/artifacts/car-catalog.jar car-catalog.jar
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "/car-catalog.jar"]