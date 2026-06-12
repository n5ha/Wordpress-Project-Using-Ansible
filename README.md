# WordPress Hosting Automation Using Ansible on AWS

## Project Overview

This project demonstrates the automated deployment and configuration of a WordPress website on an AWS EC2 instance running Amazon Linux using Ansible. The infrastructure includes Nginx, MariaDB, PHP, phpMyAdmin, SFTP access, SSL security, and WordPress CMS.

## Objectives

* Automate server configuration using Ansible
* Deploy a WordPress website on AWS EC2
* Configure Nginx as the web server
* Configure MariaDB as the database server
* Install and configure PHP 8+
* Enable secure SFTP access for website management
* Configure phpMyAdmin for database administration
* Secure the website using SSL certificate
* Publish and manage content using WordPress

## Technologies Used

* AWS EC2 (Amazon Linux)
* Ansible
* Nginx
* MariaDB 10.6
* PHP 8+
* WordPress
* phpMyAdmin
* SFTP / SSH
* SSL
* Git & GitHub

## Project Architecture

User Browser
↓
Nginx Web Server
↓
PHP-FPM
↓
WordPress Application
↓
MariaDB Database

## Directory Structure

```text
/home/bloguser/myblog/public
```

## Features Implemented

* Automated package installation using Ansible
* Website deployment under a custom user directory
* Secure SFTP access
* phpMyAdmin integration
* WordPress installation and configuration
* SSL certificate implementation
* Personal blog creation and publishing
* Service monitoring and verification

## Verification

The following components were successfully verified:

* Nginx Service
* PHP-FPM Service
* MariaDB Service
* WordPress Dashboard Access
* phpMyAdmin Access
* SFTP Connectivity
* HTTPS Access

## Learning Outcomes

This project provided practical experience in:

* Linux System Administration
* AWS Cloud Computing
* Infrastructure Automation with Ansible
* Web Server Management
* Database Administration
* Secure File Transfer
* SSL/TLS Security
* WordPress Deployment and Management
