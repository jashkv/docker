#Docker file simple syntax 

#base image for creating our first container
FROM ubuntu:latest  

#this is the currect working directory
WORKDIR /app

#here we are copying all files from currect working(.) to continer (/app)
COPY . /app

#downloading dependency for runnig program
RUN apt-get update && apt-get install -y python3 python3-pip

#setting environment verible
ENV NAME hello-world 

#command to run real application or program
CMD [ "python3", "app.py" ]