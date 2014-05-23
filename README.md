Placehold IT for PHP v0.0.1
===========================

# Description

A simple PHP-class to generate transparent placeholder images in Data-URI format

# Usage

```php
<?php
    $width = 200;
    $height = 150;
    $placehold_it = new Placehold_it(array('cache_dir' => [CACHE DIR]));
?>
<img alt="" src="<?=$placehold_it->get($width, $height)?>" />
```

---

© 2014 [paha77](http://twitter.com/paha77)

Licensed under [GPL](https://gnu.org/licenses/gpl.html)
