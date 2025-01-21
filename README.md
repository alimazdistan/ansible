Playbook to Setup Nginx and Deploy Barista Cafe Template
This Ansible playbook automates the process of setting up Nginx on a remote server, downloading the Barista Cafe template from Tooplate, extracting the files, and deploying the website.

Steps:
Install Required Packages: Installs necessary packages like Nginx, wget, and unzip.
Ensure Nginx Service is Running: Starts and enables Nginx to run on boot.
Download the Barista Cafe Template: Downloads the ZIP file of the template from the Tooplate website.
Unzip the Template: Extracts the downloaded ZIP file into a temporary directory.
Move Files to Nginx's Root Directory: Moves the extracted files to the /var/www/html/ directory, which is the default web root for Nginx.
Set File Permissions: Ensures the correct file permissions are set for the web files.
Restart Nginx Service: Restarts Nginx to apply the changes and serve the website.
This playbook is useful for quickly setting up a web server with a pre-configured template and can be adapted to different environments and templates.
