# anty-lapacz-eventow PHP client

Klient PHP umożliwiający NIE łapanie eventów:


Przykład wywołania:

```php
<?php

require '../vendor/autoload.php';

use AntyLapaczEventow\Client;

$event = [];

$client = new Client();
$client->execute($event);
```

## Wymagania

* PHP >= 5.6

## Instalacja

W projekcie dodaj do `composer.json` pakiet:

```json
{
    "require": {
        "jarekkowol/AntyLapaczEventow": "^1.*"
    }
}
```

lub wykonaj polecenie

```bash
composer require jarekkowol/AntyLapaczEventow:1.*
```
