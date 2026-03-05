# Build Stage
FROM maven:3.9.9-eclipse-temurin-17

WORKDIR /app

# Copy project files
COPY . .

# Build the jar
RUN mvn clean package -DskipTests

# Run the application
CMD ["java","-jar","target/*.jar"]
