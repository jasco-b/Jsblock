Jsblock
=======
JsBlock is helps working with js. 

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist jasurbek94/jsblock "*"
```

or add

```
"jasurbek94/jsblock": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?php \jasurbek94\jsblock\JsBlock::begin(); ?>
    <script>
        your script goes here
    </script>
<?php  \jasurbek94\jsblock\JsBlock::begin(); ?>
