# command
Command Line Development and Shelll Script and so on 

# Exercise: Command line development
This is an exercise in logging in to Linux (ubuntu) from Windows and developing using the command line.

# TeraTerm
https://github.com/TeraTermProject/teraterm/releases/tag/v5.5.1

## login
setp1
input IP address or doainname
select ssh as access method
step2

step3
input login ID and Password

## bash
ls: for look up directories and files
mkdir: make your working directory as original one.

# apt
if you are not an administrator
sudo apt update; sudo apt -y ugprade
else
apt update; apt -y ugprade


# docker
if you are not an administrator
sudo docker run -v /opt/gcc:/tmp/gcc -it gcc /bin/bash
else
docker run -v /opt/gcc:/tmp/gcc -it gcc /bin/bash

In the docker, you should do apt command again.

# gcc/g++
gcc --version
g++ --version

If you could cut and paste a source code as test.

cat > sample.cpp

g++ -o sample sample.cpp
