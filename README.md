# Ansible demo project

Complete step-by-step documentation: [Google Docs Link](https://docs.google.com/document/d/1Aj8F6UzCGEH8UpkRSsvWXZRpzQ9DgYo7zL3WxyGRUg4/edit?usp=sharing)

Install Ansible first and complete the user configuration (ssh access and sudo privileges).

Add IP and alias to the /etc/hosts file. Example: "13.233.208.97 client" (for easy remembrance).

Go to https://api.wordpress.org/secret-key/1.1/salt/ to generate WordPress auth keys and salt keys. Copy and paste into the wp-config.php file in this repo before running the playbook.

Test instructions:
1. Install the necessary packages, which include MySQL 10.6, PHP version 8 or higher, and Nginx on your Linux server.
2. Create a user's home directory under the '/home' directory. You should set the root directory for the website to be '/home/username/websitename/public.'
3. Configure SFTP (Secure File Transfer Protocol) access for the user to ensure secure file management.
4. Configure phpmyadmin access for the user to ensure secure database management.
4. Install a free SSL certificate to enable secure HTTPS access to your website.
5. Once the website is hosted, proceed to the WordPress dashboard to make necessary configurations and customizations.
6. Write a personal blog post about yourself using the WordPress content management system.

Please share the following credentials after you finish the test.

Credentials:

SFTP Credentials:
- Host: sftp://project.adnansal.im
- Username: project
- Password: project

phpMyAdmin Credentials:
- URL: https://project.adnansal.im/phpmyadmin
- Username: root
- Password: Ansible#1

- WordPress Credentials:
- WordPress Admin URL: https://project.adnansal.im/wp-admin
- Username: admin
- Password: admin

Please ensure that you document each step of the process and any configurations made. You may be asked to provide a brief report detailing the steps you took to complete this task.
