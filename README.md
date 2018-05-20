# lumen-serve
Command php artisan serve for lumen framework

# Installation
	1. `composer require devgowa/lumen-serve`
	2. Add `\Devgowa\LumenServe\Command\ServeCommand::class` to `$commands` array in `app/Console/Kernel.php`
	3. Run `php artisan serve`

# Disclaimer
Just copied from [laravel/framework](https://github.com/laravel/framework) by [@taylorotwell](https://github.com/taylorotwell)