Features

SSL/TLS Configuration ✅
MySQL Encryption ✅
Fix for Missing Top Menu ✅
HTTPS Enforcement ✅
Redis Encryption ✅

Overview

This repository contains the necessary configuration files to set up a robust and secure web application. We have taken special care to ensure that sensitive information like SSL/TLS certificates, MySQL, and Redis passwords are not exposed in the configuration files. Instead, placeholders have been used which you can replace with your actual credentials.

Configuration Instructions
Docker Compose File
The docker-compose.yml file is configured to set up the environment for the web application.

Steps to configure:

Replace the placeholder values (YOUR_DATABASE_NAME, YOUR_DATABASE_USER, YOUR_DATABASE_PASSWORD, etc.) with your actual database credentials and paths.
Ensure that the volume paths for data storage are correctly set according to your system's directory structure.
NGINX Configuration File
The NGINX configuration file (nginx.conf) is set up to handle web server requests and enforce HTTPS.

Steps to configure:

Change YOUR_SERVER_NAME to your actual server name.
Update the SSL certificate and key paths (/path/to/your/ssl_certificate.pem and /path/to/your/ssl_certificate_key.pem) to point to your SSL files.
Modify the paths for the static and media files (/path/to/static and /path/to/media) according to where they are stored in your system.
