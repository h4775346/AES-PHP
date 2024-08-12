# AES-PHP
AES Encryption In Php
Example usage

```
$data = ["name"=>"abanoub"];
$encSecret = "abcdefg112233445566";
AES::encrypt(json_encode($data), $encSecret);
```
