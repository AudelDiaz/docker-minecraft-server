FROM openjdk:19-jdk-slim-buster
WORKDIR /usr/src/minecraft
COPY server.jar eula.txt ./
CMD  java -Xmx1024M -Xms1024M -jar server.jar nogui 