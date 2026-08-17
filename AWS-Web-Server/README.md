# AWS Linux Web Server

## Project Overview

This project is my first hands-on cloud engineering project.

I deployed a simple HTML website on an Amazon EC2 instance running Ubuntu Linux and configured Apache2 as the web server.

The goal of this project was to learn the fundamentals of deploying and accessing a web server in the AWS cloud.

## Architecture

Internet
   |
   | HTTP :80
   v
AWS Security Group
   |
   v
Amazon EC2
Ubuntu Linux
   |
   v
Apache2
   |
   v
index.html
What I Did

1. Launched an Ubuntu EC2 instance on AWS.
2. Connected to the instance using SSH.
3. Updated the Ubuntu system.
4. Installed Apache2.
5. Configured the AWS Security Group to allow HTTP traffic on port 80.
6. Located Apache’s web directory at /var/www/html.
7. Created and edited an index.html file.
8. Started and verified the Apache web server.
9. Tested the website using the EC2 instance’s public IP address.
10. Troubleshot connectivity issues involving the EC2 instance, SSH, and port 80.

Website

The website is a simple HTML page introducing my Cloud Engineering Journey.

It displays:

* My name
* The project name
* The AWS technologies used
* The purpose of the project

What I Learned

Through this project I learned:

* How EC2 instances work
* How to connect to a Linux server using SSH
* Basic Linux server administration
* How Apache serves websites
* How AWS Security Groups control network traffic
* How HTTP traffic reaches an EC2 web server
* How to troubleshoot connectivity problems
* How to deploy a website to a cloud server