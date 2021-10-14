# BotMan Tinker

Backup original package BotMan Tinker by Marcel Pociot

* Laravel 7 compatible


## Installation

Run `composer require botman/tinker` to install the composer dependencies.

Then in your `config/app.php` add

```php
BotMan\Tinker\TinkerServiceProvider::class,
```

to the `providers` array.

## Usage

You now have a new Artisan command that helps you to test and develop your chatbot locally:

```php
php artisan botman:tinker
```
