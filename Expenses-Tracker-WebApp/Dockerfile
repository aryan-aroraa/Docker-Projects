# stage 1 - build the JAR
FROM maven:3.8.3-eclipse-temurin-17 AS builder
WORKDIR /app

COPY . .

RUN mvn clean install -DskipTests=true

# stage 2 - execute JAR file from above stage
FROM eclipse-temurin:17-alpine

WORKDIR /app

COPY --from=builder /app/target/*.jar /app/expenseapp.jar

CMD ["java", "-jar", "expenseapp.jar"]

