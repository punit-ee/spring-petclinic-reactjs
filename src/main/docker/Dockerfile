FROM openjdk:alpine

WORKDIR /home/dev/code

COPY petclinic.jar .

# To reduce Tomcat startup time we added a system property pointing to "/dev/urandom" as a source of entropy.
ENTRYPOINT ["java", "-jar", "petclinic.jar"]
