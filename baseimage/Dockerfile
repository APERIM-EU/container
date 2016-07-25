#################################################################
# Dockerfile
#
# Version:          1
# Software:         Centos Base
# Website:          http://icbi.at
# Tags:             centos
# Provides:         icbi
# Base Image:       centos/latest
# Build Cmd:        docker build -t centos:[localname] .
# Pull Cmd:         todo
# Run Cmd:          todo eg. docker run centos:[localname] tools
# Extra:            Base image to provide bioinformatic tools for 
# Extra:            academical use
#################################################################

# Set the base image to biodocker base image
FROM centos:latest

# update os, install prequisites and clean cache
RUN yum clean all && yum -y update
RUN yum install -y make cmake gcc gcc-c++

#Clean up
RUN rm -rf /tmp/* /var/tmp/* ~/.cache/*

################## BEGIN INSTALLATION ######################



##################### INSTALLATION END #####################


