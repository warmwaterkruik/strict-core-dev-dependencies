[![Packagist](https://img.shields.io/packagist/v/alexpott/strict-core-dev-dependencies.svg)](https://packagist.org/packages/alexpott/strict-core-dev-dependencies)
 [![Packagist](https://img.shields.io/packagist/dt/alexpott/strict-core-dev-dependencies.svg)](https://packagist.org/packages/alexpott/strict-core-dev-dependencies)

---

To fix to dependencies tested on Drupal 8.4.0 add ```"alexpott/strict-core-dev-dependencies": "8.4.0"``` to the require-dev section of your composer.json and run ```composer update``` from the command line.

In other words: this is a _virtual_ package, that causes you to get exactly the versions of Drupal core's dev dependencies as they are specified in Drupal core's `composer.lock` file.

Using ```composer require``` is problematic on an existing site.
