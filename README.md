Colorbox Widget for Yii2
========================

A customizable lightbox jQuery plugin for Yii2.

Installation
------------
The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require "himiklab/yii2-colorbox-widget" "*"
```
or add

```json
"himiklab/yii2-colorbox-widget" : "*"
```

to the require section of your application's `composer.json` file.

Usage
-----
Using as field in ActiveForm:

```php
use himiklab\colorbox\Colorbox;

<?= Colorbox::widget([
    'targets' => [
        '.colorbox' => [
            'maxWidth' => 800,
            'maxHeight' => 600,
        ],
    ]
]) ?>
```
