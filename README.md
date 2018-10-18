# Random UserAgent
random user agent creator

test.php
```php
require 'vendor/autoload.php';
var_dump( UserAgent::random() );
```

output...
```sh
php -f test.php
string(65) "Mozilla/5.0 (X11; Linuxx86_64; rv:6.0) Gecko/20131117 Firefox/3.8"
```
