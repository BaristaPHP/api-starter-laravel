# :package_description

## Installation

You can install the package via composer:

```bash
composer require :vendor/:package
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag=":package-migrations"
php artisan migrate
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag=":package-config"
```

## Testing

```bash
php artisan test
```

## Credits

- [:author_name](https://github.com/:author_username)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
