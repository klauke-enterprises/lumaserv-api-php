# lumaserv-api-php
PHP Client for the LUMASERV API

# Getting Started

```bash
composer require klauke-enterprises/lumaserv-api-php
```

# Usage
```php
use LUMASERV;

$client = new CoreClient("YOUR_API_TOKEN");
$res = $client->getServers();
```
