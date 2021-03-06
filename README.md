List prefix languajes https://cloud.google.com/translate/docs/languages

# PHP GoogleTranslate free [![Build Status](https://travis-ci.org/SiegSB/php-google-translate-free.svg?branch=master)](https://travis-ci.org/SiegSB/php-google-translate-free)
Simple PHP library for talking to Google's Translate API for free.

## Installation

Install this package via [Composer](https://getcomposer.org/).

```
composer require statickidz/php-google-translate-free
```

Or edit your project's `composer.json` to require `statickidz/php-google-translate-free` and then run `composer update`.

```json
"require": {
    "statickidz/php-google-translate-free": "^1.0"
}
```

## Usage

```php
require_once ('vendor/autoload.php');
use \Statickidz\GoogleTranslate;

$source = 'es';
$target = 'en';
$text = 'verdadero';

$trans = new GoogleTranslate();
$result = $trans->translate($source, $target, $text);

echo $result;
```

## Demo

Live example here: https://statickidz.com/proyectos/traductor-google-api-php-gratis/
