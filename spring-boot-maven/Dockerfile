FROM maven:3.6.3-jdk-11
EXPOSE 8080
COPY /app/src /app/src
COPY /app/pom.xml /app
WORKDIR /app
ENTRYPOINT ["mvn","spring-boot:run"]

# sudo docker run -v "$HOME"/.m2:/root/.m2 -p 8080:8080 <image_id>
