# Use the official Ubuntu base image
FROM ubuntu:latest

WORKDIR /app
COPY . /app

# Update and install some packages
RUN apt-get update && apt-get install -y python3 python3-pip
    

# Set the working directory


# Copy the current directory contents into the container at /app
COPY . /app
ENV NAME World
# Define the command to run the container
CMD ["python3","app.py"]
