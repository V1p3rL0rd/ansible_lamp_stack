# Ansible LAMP stack deployment
This is a very simple Ansible playbook will help you to install and confiure LAMP stack 

The playbook contains a several tasks:

1) Update apt package index
2) Install Apache, MySQL, and PHP
3) Enable Apache modules
4) Create a self-signed SSL certificate
5) Configure Apache for SSL
6) Enable the new Apache configuration
7) Disable the default Apache configuration
8) Restart Apache to apply changes
9) Ensure MySQL root password is set
10) Remove anonymous MySQL users
11) Remove test database
12) Remove test database privileges
13) Reload privilege tables
14) Install phpMyAdmin (optional)
