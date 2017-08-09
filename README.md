# Udacity-Ubuntu

IP address: 165.227.12.240
Accessible SSH port: 2200.
APP URL: vathox.com

Software installed: Apache2, posgreSQL

#Configurations made:

Updated all currently installed packages.
Changed the SSH port from 22 to 2200.
Configure the Uncomplicated Firewall (UFW) to allow only (port 2200), HTTP (port 80), and NTP (port 123).
Create a new user grader with sudo premission
Create an SSH key pair for grader using the ssh-keygen tool.
Configure the local timezone to UTC.
Install and configure Apache to serve a Python mod_wsgi application.
Install and configure PostgreSQL.
Install git.
Clone and setup your git project (here Catalog).
Use a custom domain with Digital Ocean.
Disable root remote login and enforce key-based authentication.
