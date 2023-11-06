# Use the latest Ubuntu
FROM ubuntu:latest

# Update the APT package list
RUN apt-get update

# Upgrade currently installed software through APT and install the 'echo' command
RUN apt-get upgrade -y

# Install Python3 and Flask
RUN apt-get install -y python3 python3-pip
RUN pip3 install Flask
RUN pip3 install flask-cors

# Set working directory
WORKDIR /app

# Copy current directory contents
COPY ./api.py /app/api.py

# Run python3 and api
CMD [ "python3", "api.py" ]