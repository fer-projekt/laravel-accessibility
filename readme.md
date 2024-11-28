#### Under Development

## Laravel Accessibility

This package helps with a variety of common accessibility problems.
The package adds a number of helpful accessibility features with a minimum amount of setup or expert knowledge.

## Installation

Require this package with composer.

```shell
composer require fer-projekt/laravel-accessibility dev-master
```

Laravel 5.5 uses Package Auto-Discovery, so doesn't require you to manually add the ServiceProvider.

The Accessibility will be enabled by default, to change that update your .env file.
See more options in `config/accessibility.php`
```text
ACCESSIBILITY_ENABLED=true
``` 

Copy the package config and translation files to your local with the publish command:

```shell
php artisan vendor:publish --provider="Oh4d\Accessibility\ServiceProvider"
```
