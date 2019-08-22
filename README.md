emmet-vaild

使用方法

1.验证码生成

```php
        $valid = new \Emmetltd\valid\lib\EmmetValid;

        $valid->make();
```

2.验证

```php
        $valid= new \Emmetltd\valid\lib\EmmetValid;
        if($valid->check()){
            $_SESSION['tncode_check'] = 'ok';
            echo "ok";
        }else{
            $_SESSION['tncode_check'] = 'error';
            echo "error";
        }
```
