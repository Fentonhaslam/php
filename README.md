# php

Initial start of using PHP. 

Initiated global usage of <strong>Composer</strong>

Created a composer.json file with a require key: 

``` 
{
    "require": {
        "laravel": "1.0.*"
    }
}
```
After run command 
```
php composer.phar install 
```
To install all the dependencies. 

##Create Project

Used command line : 
```
composer create-project --prefer-dist laravel/laravel blog
```

##Run locally 
```
php artisan serve
```
##Key set 
``` 
php artisan key:generate
```
##Testin framework
```
composer require --dev phpunit/phpunit ^7
```
ensuring that the composer.json file had this content: 
```
{
    "autoload": {
        "classmap": [
            "src/"
        ]
    },
    "require-dev": {
        "phpunit/phpunit": "^7"
    }
}
```
