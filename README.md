# About Images
This project includes Dockerfile and related config files for building.

# The Images List
1. `base-alpine-php-fpm56:latest`

# Images Description
* Image name: `base-alpine-php-fpm56`
* Image Tag: `latest`

# Major Featrues:
* php cli 
    * version:

     ```
     $ php -v
     PHP 5.6.40 (cli) (built: Jan 31 2019 01:25:07)
     Copyright (c) 1997-2016 The PHP Group
     Zend Engine v2.6.0, Copyright (c) 1998-2016 Zend Technologies

     ```
    * pecl extensions:

     ```
       `gearman`/`redis`/`yaml`/`pdo_mysql`

     ```
* php-fpm
    * version:

     ```
     $ php-fpm5 -v
     PHP 5.6.40 (fpm-fcgi) (built: Jan 17 2019 00:00:50)
     Copyright (c) 1997-2016 The PHP Group
     Zend Engine v2.6.0, Copyright (c) 1998-2016 Zend Technologies
        with Zend OPcache v7.0.6-dev, Copyright (c) 1999-2016, by Zend Technologies

     ```
* nginx
    * version:

     ```
     $ nginx -v
     nginx version: nginx/1.14.2

     ```
# Usage
1. clone this project.
2. starting build

    ```
    $ cd base-alpine-php-fpm56
    $ make build    

    ``` 

