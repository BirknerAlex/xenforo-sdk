xenforo-sdk for PHP
===================

This is a PHP SDK for the XenForo software. Tested with XenForo 1.4.5.

Usage
-----

### Composer install

You can install via composer:
- visit http://getcomposer.org to install composer on your system;
- create a composer.json file in your project root:

```json
{
  "require": {
      "tyrola/xenforo-sdk": "1.0.*@dev"
  }
}
```

- download and install the package with `composer install`;
- add this lines to your application's `index.php` file:

```php
<?php

require 'vendor/autoload.php';
$sdk = new XenForoSDK;
```

For usage samples take a look into the sample.php file.

Notes
-----

This is forked from VinceG and maintained by BirknerAlex.