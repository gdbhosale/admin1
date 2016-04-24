# Install AdminLTE in Laravel
```
composer create-project --prefer-dist laravel/laravel admin1
composer require "acacha/admin-lte-template-laravel:2.*"
adminlte-laravel --no-llum install
```
Done !!!
Do Database Configuration
Migrate to create tables using command
```
php artisan migrate
```