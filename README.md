# garantibankasi
Garanti Bankası Banka Entegrasyonu Hesap Hareketleri

composer require phpdev/garantibankasi

```php

use Phpdev\Garantibankasi;

$entegrasyon = new Garantibankasi('kullanıcı adı','parola',"bankadan verilen key");

$response = $entegrasyon->hesap_hareketleri('2021-03-02','IBAN');

print_r(json_encode($response));

}
```
