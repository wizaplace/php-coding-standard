**DEPRECATED**: use instead [wizaplace/phpcs](https://github.com/wizaplace/phpcs)

Wizaplace's pragmatic PHP standard based on the [Symfony coding standards](http://symfony.com/doc/current/contributing/code/standards.html).

## Installation

Install dependencies :

```
$ composer require --dev wizaplace/php-coding-standard
```

To use it with [Coke](https://github.com/M6Web/Coke), just add this line to your `.coke` :

```
standard=vendor/wizaplace/php-coding-standard/Wizaplace
```

If you are using PHP CodeSniffer, you can set it up with a `phpcs.xml` file:

```xml
<?xml version="1.0"?>
<ruleset>
    <rule ref="vendor/wizaplace/php-coding-standard/Wizaplace/ruleset.xml"/>
</ruleset>
```

## Credits

Developped by [Wizaplace](http://tech.wizaplace.com/) using [djoos/Symfony2-coding-standard](https://github.com/djoos/Symfony2-coding-standard).

## License

This project is licensed under the [MIT license](LICENSE).
