# Laravel Token Session

## Installation

Require this package, with [Composer](https://getcomposer.org/), in the root directory of your project.

``` bash
$ composer require faustbrian/laravel-token-session
```

And then, if using Laravel 5, include the service provider within `app/config/app.php`.

``` php
BrianFaust\TokenSession\TokenSessionServiceProvider::class
```

And, for convenience, add a facade alias to this same file at the bottom:

``` php
'TokenSession' => BrianFaust\TokenSession\Facades\TokenSession
```

## Usage

``` php
...
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ phpunit
```

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security

If you discover a security vulnerability within this package, please send an e-mail to Brian Faust at hello@brianfaust.de. All security vulnerabilities will be promptly addressed.

## Credits

- [Brian Faust](https://github.com/faustbrian)
- [All Contributors](../../contributors)

## License

[MIT](LICENSE) © [Brian Faust](https://brianfaust.de)
