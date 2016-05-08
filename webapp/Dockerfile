FROM ubuntu:14.04

# Set home/webapp dir as main directory
WORKDIR /home/webapp

# Add all host webapp code to image workdir
ADD . ./

# Expose workdir as volume to other containers
VOLUME /home/webapp
