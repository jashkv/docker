# Use an Ubuntu base image

FROM ubuntu:latest



RUN apt-get update



# Install the build-essential package (includes GCC)

RUN apt-get install -y build-essential



# Set the working directory

WORKDIR /app



# Copy the C source code to the container

COPY helloworld.c /app



# Compile the C source code

RUN gcc -o helloworld helloworld.c



# Run the program

CMD ["./helloworld"]

