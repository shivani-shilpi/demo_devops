
FROM ubuntu:latest


# Set the working diractry in the image

WORKDIR /app


# copy the file from host file system to the image file system
COPY . /app


# Install the nessary packages

RUN apt-get update


# Set envirnment variable
ENV NAME World


# run a command to start the application
FROM ruby:2.6.3
COPY app.rb .
CMD ["ruby", "app.rb"]
