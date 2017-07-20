# wordpress-nginx

A basic Docker starter kit for WordPress-based sites. With it you get:

* Nginx 1.4.6
* PHP 5.6
* [WP CLI](https://developer.wordpress.org/cli/commands/)

Plus some sensible configuration tweaks to support WordPress sites.

After booting up, the `wp.sh` script will automatically download the latest version of WordPress via the WP CLI tool.

Drop into a `docker-compose.yml` with a MySQL service, mount your themes/plugins/uploads folders and you're off to the races! 🏇
