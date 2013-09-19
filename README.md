ErrorHandler
=======

Kryptos/ErrorHandler servers is an easy to use composer package that serves as a beautiful error handler.


Usage
-----
```php
//Instantiate class
new \Kryptos\Handler\Error;

//Code!
if (1===1) {
    trigger_error('1 is equal to 1!');
}

trigger_error('1 is not equal to 1!', E_USER_ERROR);
```
