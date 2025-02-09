dockerfile
CopyEdit
# Base Image
FROM ubuntu:20.04

# Maintainer Information
MAINTAINER Paulo ptanicala23@kgi.edu

# Install Dependencies
RUN apt-get update && \
    apt-get install -y python3 python3-pip && \
    pip3 install numpy pandas matplotlib && \
    apt-get clean

# Add Your Project Script
ADD Scripts/your_script.py /usr/local/bin/

# Make Script Executable
RUN chmod +x /usr/local/bin/your_script.py

