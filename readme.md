Just a simple bash script that runs the following commands 

#!/bin/bash

# Update and upgrade packages
sudo apt update && sudo apt upgrade -y

# Install curl
sudo apt install curl -y

# Install Docker
curl -sSL https://get.docker.com/ | sh
