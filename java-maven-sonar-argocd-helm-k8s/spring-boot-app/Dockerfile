# Use the official OpenJDK base image with Java 11
FROM adoptopenjdk/openjdk11:alpine-jre

# Set the working directory in the container
WORKDIR /app

# Copy the compiled JAR file from your local machine to the container
COPY target/your-spring-boot-app.jar app.jar

# Expose the port that your application uses
EXPOSE 9100

# Define the command to run your application
CMD ["java", "-jar", "app.jar"]




# You can change this base image to anything else
# But make sure to use the correct version of Java
#FROM adoptopenjdk/openjdk11:alpine-jre

# Simply the artifact path
#ARG artifact=target/spring-boot-web.jar

#WORKDIR /opt/app

#COPY ${artifact} app.jar

# This should not be changed
#ENTRYPOINT ["java","-jar","app.jar"]
