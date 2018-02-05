# Linux server configuration project
by robotoART

## Objective of project

Setup a basic Linux Ubuntu distribution virtual machine on AWS Lightsail, update and secure it from the most common attack vectors. Also install and configure web and database servers on the virtual machine. Deploy the [Video Game Library App](https://github.com/robotoART/VideoGameLibraryApp.git), previously developed for **Build an Item Catalog project**.

## Linux App address & url
IP address: Not available at the moment.

Application URL: Not available at the moment.

## General steps
1 - Creae a AWS Lightsail acount and make a Linux Ubuntu distribution

 2 - Update all currently installed packages

 3 - Configure the local timezone to UTC

 4 - Create a new user named *grader* and grant this user sudo permissions.

 5 - Configure the key-based authentication for *grader* user

 6 - Enforce key-based authentication

 7 - Add port 2200 for login

 8 - Disable ssh login for *root* user

 9 - Configure the Uncomplicated Firewall (UFW)

 10 - Configure cron scripts to automatically manage package updates

 11 - Install Apache, and mod_wsgi

 12 - Install Git

 13 - Clone my Video Game Library Catalog app from Github

 14 - Install virtual environment, Flask and the project's dependencies

 15 - Configure and enable a new virtual host

 16 - Install and configure PostgreSQL

 18 - Update OAuth authorized JavaScript origins

 19 - Restart Apache to launch the app

 20 - Test & Debug App functionality and appearance

#### Sources used to help create this project include the Udacity forums, [iliketomatoes](https://github.com/iliketomatoes/linux_server_configuration), and [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps).
