# metabase/Dockerfile
FROM openjdk:11-jre-slim
WORKDIR /app
COPY metabase.jar .
EXPOSE 3000
CMD ["java", "-jar", "metabase.jar"]
