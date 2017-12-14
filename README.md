# Usage

```php
use Cevin\Cardbin\Cardbin;

$cardNo = '6228480402564890018';

// validate china debit bank card
$info = Cardbin::valid($cardNo);
// $info['bank'] Bank name
// $info['card'] Card name


// @todo: validate global credit card
```
