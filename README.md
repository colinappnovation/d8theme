#My Theme

##Introduction

This theme was result of taking the Appno learning course.

##Features

* Base theme set to _classy_
* Usage of kint override in local.settings.php


## Special Notes

Special mention has to be made for making kint work on this project. Review the
the link for more information.

http://drupal.stackexchange.com/questions/211928/how-can-i-make-kint-load-faster-when-debugging-twig-templates

### Configuration change

```
require_once DRUPAL_ROOT . '/modules/contrib/devel/kint/kint/Kint.class.php';
Kint::$maxLevels = 3;
```
