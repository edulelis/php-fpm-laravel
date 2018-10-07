# PHP-FPM Docker image for Lumen

Docker image for a php-fpm container crafted to run Laravel based applications.

## Specifications:

* PHP 7.2
* OpenSSL PHP Extension
* PDO PHP Extension
* SOAP PHP Extension
* Mbstring PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension
* PCNTL PHP Extension
* ZIP PHP Extension
* MCRYPT PHP Extension
* GD PHP Extension
* BCMath PHP Extension
* Memcached
* Redis PHP Extension
* MongoDB PHP Extension
* PHP ini values for Laravel (see [`laravel.ini`](https://github.com/Cyber-Duck/php-fpm-laravel/blob/master/laravel.ini))
* xDebug (PHPStorm friendly, see [`xdebug.ini`](https://github.com/Cyber-Duck/php-fpm-laravel/blob/master/xdebug.ini))
* `t` alias created to run unit tests `vendor/bin/phpunit` with `docker-compose exec [service_name] t`
