# This is my package panel-settings

[![Latest Version on Packagist](https://img.shields.io/packagist/v/smartcms/panel-settings.svg?style=flat-square)](https://packagist.org/packages/smartcms/panel-settings)
[![GitHub Tests Action Status](https://img.shields.io/github/actions/workflow/status/smartcms/panel-settings/run-tests.yml?branch=main&label=tests&style=flat-square)](https://github.com/smartcms/panel-settings/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/actions/workflow/status/smartcms/panel-settings/fix-php-code-style-issues.yml?branch=main&label=code%20style&style=flat-square)](https://github.com/smartcms/panel-settings/actions?query=workflow%3A"Fix+PHP+code+styling"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/smartcms/panel-settings.svg?style=flat-square)](https://packagist.org/packages/smartcms/panel-settings)



This is where your description should go. Limit it to a paragraph or two. Consider adding a small example.

## Installation

You can install the package via composer:

```bash
composer require smartcms/panel-settings
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag="panel-settings-migrations"
php artisan migrate
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag="panel-settings-config"
```

Optionally, you can publish the views using

```bash
php artisan vendor:publish --tag="panel-settings-views"
```

This is the contents of the published config file:

```php
return [
];
```

## Usage

```php
$panelSettings = new SmartCms\PanelSettings();
echo $panelSettings->echoPhrase('Hello, SmartCms!');
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [maxboyko](https://github.com/SmartCms)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
