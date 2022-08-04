WordPress Composer Template
====================

This is the template for downloading wordpress in Composer.

## Get started

```shell
wget https://raw.github.com/atomita/wordpress-composer-template/master/composer.json
wget https://raw.github.com/atomita/wordpress-composer-template/master/env-example -O .env
mkdir public
wget https://raw.github.com/atomita/wordpress-composer-template/master/public/index.php -O public/index.php
composer run-script update-repositories-for-wordpress
env COMPOSER_PROCESS_TIMEOUT=0 composer install
```
