WordPress Composer Template
====================

This is the template for downloading wordpress in Composer.

## Get started

```shell
wget https://raw.github.com/atomita/wordpress-composer-template/v1/composer.json
wget https://raw.github.com/atomita/wordpress-composer-template/v1/env-example -O .env
wget https://raw.github.com/atomita/wordpress-composer-template/v1/index.php
composer run-script update-repositories-for-wordpress
env COMPOSER_PROCESS_TIMEOUT=0 composer install
```
