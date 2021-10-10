FROM  openjdk:11.0.2-jre-slim

# Copy files in
COPY . /app
WORKDIR /app

EXPOSE 8080

CMD ["java", "-jar", "customer-service-0.0.1-SNAPSHOT.jar"]

# docker build -t cs3219/customer-service:1.0.0 ./customer-service