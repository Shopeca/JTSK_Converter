# JTSK coordinates converter

### Conversion example

```php
$converter = new JTSK\Converter();
$latlon = $converter->JTSKtoWGS84(1104335.13, 707849.38); // returns array ['lat', 'lon']
$jtsk = $converter->WGS84toJTSK(49.582556081943, 15.015852481984); // returns array ['x', 'y']
```


## Live demo
Check a [live demo](http://vast-brushlands-3412.herokuapp.com/jtsk/) for examples of conversion accuracy
