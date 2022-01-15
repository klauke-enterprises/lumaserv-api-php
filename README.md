# lumaserv-api-php
PHP Client for the LUMASERV API
# Usage
```php
use LUMASERV;

$client = new CoreClient("YOUR_API_TOKEN");
$res = $client->getServers();
```