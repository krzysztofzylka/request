# Install
```bash
composer require krzysztofzylka/request
```

# Method
## Is post request
```php
\Krzysztofzylka\Request\Request::isPost()
```
## Is get request
```php
\Krzysztofzylka\Request\Request::isGet()
```
## Checks if the current request is an AJAX request
```php
\Krzysztofzylka\Request\Request::isAjaxRequest()
```
## Get php://input content
```php
\Krzysztofzylka\Request\Request::getInputContents()
```
## Get POST data
```php
\Krzysztofzylka\Request\Request::getPostData()
```
## Get GET data
```php
\Krzysztofzylka\Request\Request::getGetData()
```