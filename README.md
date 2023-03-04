# idloom's PHP coding standard

This will install idloom's [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) coding standards in your project.

Based on [PSR-12](https://www.php-fig.org/psr/psr-12/).

## Installation

Add the following configuration to your `composer.json` file:

```json
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/idloom/phpcs.git"
    }
],
```

Next, add idloom/phpcs to the require section of your `composer.json` file:

```json
"require": {
    "idloom/phpcs": "^1.0"
},
```
