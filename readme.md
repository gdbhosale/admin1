# Install AdminLTE in Laravel
Create Project admin1
```
composer create-project --prefer-dist laravel/laravel admin1
```

Import adminlte-laravel
```
composer require "acacha/admin-lte-template-laravel:2.*"
```

Install adminlte-laravel
```
adminlte-laravel --no-llum install
```

Do Database Configuration in .env (ready database file in database/laravel_admin1.sql)

Migrate to create tables using command

```
php artisan migrate
```

Done !!!