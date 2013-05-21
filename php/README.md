
# PHP Best Practices

## Basis of Standards

### PSR  
All PSR guidelines **MUST** be followed as this is becoming community best practice.  These standards **SHOULD** provide the foundation for all other standards in PHP.  **Note:** All other sections proceeding this one are either not defined in PSR or are special cases.

* [PSR 0](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md)
* [PSR 1](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md)
* [PSR 2](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md)
* [PSR 3](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-3-logger-interface.md)

## Coding standards

### Class Properties
1. Properties **MUST** be camelCase

## Linter
* **Linter:** Sublime Linter (php -l) and Sublime Code Sniffer (PHPCS)

## Documentation
See [Universal standards](https://github.com/joshmfrankel/Standards#universal-standards)

### PHPDocumentor2
1. All files **MUST** be phpdocumentor compliant
2. All applications **SHOULD** have dedicated directory for containing all generated documentation.

## Unit Testing (phpunit)
1. Applications and plugins **SHOULD** include an accurate suite of tests for their given
functionality.  
2. Applications and plugins **SHOULD** adopt a TDD approach to development which
will reduce future bugs.

### Class Properties
1. Properties **MUST** be camelCase
