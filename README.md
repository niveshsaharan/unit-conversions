# Unit conversion in PHP

[![Latest Version on Packagist](https://img.shields.io/packagist/v/niveshsaharan/unit-conversions.svg?style=flat-square)](https://packagist.org/packages/niveshsaharan/unit-conversions)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/niveshsaharan/unit-conversions/run-tests?label=tests)](https://github.com/niveshsaharan/unit-conversions/actions?query=workflow%3Arun-tests+branch%3Amaster)
[![Total Downloads](https://img.shields.io/packagist/dt/niveshsaharan/unit-conversions.svg?style=flat-square)](https://packagist.org/packages/niveshsaharan/unit-conversions)


A wonderful package for unit conversions in PHP

## Installation

You can install the package via composer:

```bash
composer require niveshsaharan/unit-conversions
```

## Usage

``` php
$lbs = Weight::fromKilograms(100)->toLbs();
```

## Testing

``` bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email hey@nive.sh instead of using the issue tracker.

## Credits

- [Nivesh Saharan](https://github.com/niveshsaharan)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
