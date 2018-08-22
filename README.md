# lumen-serve
Command php artisan serve for lumen framework

# Installation
1. `composer require devgowa/lumen-serve`
2. Register service provider in `boostrap\app.php` with `$app->register(Devgowa\LumenServe\CommandServeServiceProvider::class)`
3. Run `php artisan serve`

# Disclaimer
Just copied from [laravel/framework](https://github.com/laravel/framework) by [@taylorotwell](https://github.com/taylorotwell)
