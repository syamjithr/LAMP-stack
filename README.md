# Ansible role to install lamp stack on ubuntu

This ansible role will install lamp stack on ubuntu server

## Role activites

 - Installing apache,php,mysql-server.
 - Creating virtualhost.
 - Creating Documentroot for the virtualhost.
 - Reset mysql root password.
 - Removing Removing anonymous users.
 - Creating additional database and user for the wordpress project.

## Features

- Fully configurable and compatible with AWS
- Can be used to create a standalone LAMP stack or deploy applications over the current LAMP stack
 
## Role variables

- httpd_owner: 
- httpd_group: 
- httpd_port: 
- httpd_domain: 
- mysql_root: 
- mysql_user: 
- mysql_password: 
- mysql_database: 
- php_modules: [ 'php-curl', 'php-gd', 'php-mbstring', 'php-xml', 'php-xmlrpc', 'php-soap', 'php-intl', 'php-zip' ]
