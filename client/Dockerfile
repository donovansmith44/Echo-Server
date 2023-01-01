#Use the openJDK 11 image as the base image
FROM openjdk:11

#Create a new app directory for app files.
RUN mkdir /app

#Copy app files from host machine to image filesystem
COPY app /app

#Set directory for executing future commands
WORKDIR /app

#run classes
CMD javac echoClient.java && java echoClient