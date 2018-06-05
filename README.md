# phpunit-pretty-print
> Forked from sempro/phpunit-pretty-print:1.0.3

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![eslint](https://img.shields.io/badge/code_style-PSR_2-blue.svg?style=flat-square)](http://www.php-fig.org/psr/psr-2/)

<img src="https://raw.githubusercontent.com/webberwu/phpunit-pretty-print/master/preview.png" alt="phpunit-pretty-print">

### Installation
```bash
composer require webberwu/phpunit-pretty-print --dev
```

### Usage
You can specify the printer to use on the phpunit command line:

```bash
php vendor/bin/phpunit --printer 'Webber\PHPUnitPrettyPrinter\PrettyPrinter' tests/
```

Optionally, you can add it to your project's `phpunit.xml` file instead:

```xml
<phpunit
    bootstrap="bootstrap.php"
    colors="true"
    printerClass="Webber\PHPUnitPrettyPrinter\PrettyPrinter">
```
