Caregory card
=============
Creates a category simple card layout.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
composer require tdot/yii2-categorycard:dev-master
```

or add

```
        "tdot/yii2-categorycard": "dev-master"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \app\components\tdotcard\Categorycard::widget(['name' => 'something', 'image' => 'image URL', 'description' => 'something']); ?>
```
