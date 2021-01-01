# WP-Docker
This will create a MariaDB container while also creating a container for WordPress using docker-compose and .env

use .env to define the variables
### .env Variables
- CONTAINER_NAME the root name for the container _WP will be added to the end for the WordPress container and _DB will be added to the end for the database container
- DB_DATA_PATH the location where the database will be saved. The default is in the root folder in a folder named mysql
- MYSQL_ROOT_PASSWORD the root password you want for the database
- WP_DB_NAME the name you want for the database
- WP_DB_USER the username that will have access to the WP database (it will be defined in wp-config.php)
- WP_DB_PASSWORD the password for the database user (it will be defined in wp-config.php)
- WORDPRESS_TABLE_PREFIX the prefix you want to use to the tables in wordpress
- PHP_INI the location for your custom php.ini file. The default is in the root folder /config/php.conf.ini
- WP_HTML where you want all the HTML files of Wordpress to be saved. The default is in the root folder in a folder named wp-html
- HTTP_PORT the exposed port you want wordpress to run on
