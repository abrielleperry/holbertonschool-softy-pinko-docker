# Use the latest Ubuntu
FROM ubuntu:latest

# Update the APT package list
RUN apt-get update

# Upgrade currently installed software through APT and install the 'echo' command
RUN apt-get upgrade -y && apt-get install -y echo

# Set the default command to echo "Hello, World!"
CMD ["echo", "Hello, World!"]
