# WordPress - Composer template

Use .env file from .env.example and fill in data for Database connection and WP_ENV, WP_HOME vars

run `composer install` it will install latest version of Wordpress and plugins described in composer.json

Use https://wpackagist.org to plugins installation. All 3rd Party plugins is in Git Ignore, so if you use custom plugin
then add it to gitignore exception.

All work should be done in root 'wp-content' folder and this folder will be placed in git.
