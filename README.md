# DXT-Wordpress
This will create a mariadb container while also creating a container for WordPress using docker-compose and .env

use .env to define the variables
### Variables
- CONTAINER_DB_NAME the name for the database container
- DB_CONF_PATH where you want /etc/mysql/conf.d to be saved
- DB_DATA_PATH where you want /var/lib/mysql to be saved
- MYSQL_ROOT_PASSWORD the root password you want for the database container
- WP_CORE where you want all the core files of Wordpress to be saved
- WP_DB the name you want for the database
- WP_USER the username that will have access and will be defined in wp-config.php
- WP_PASSWORD the password for WP_USER
- DB_PORT the external port you want to use for mariadb 3306
- CONTAINER_WP_NAME the name for the WordPress container
- WORDPRESS_TABLE_PREFIX the prefix you want to use to the tables in wordpress
- HTTP_PORT the external port for 80
- DOMAINS the name for the external domain
- LETSENCRYPT_EMAIL the email address for your SSL cert
