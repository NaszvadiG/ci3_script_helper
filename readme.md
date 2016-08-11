# Codeigniter 3 Script Helper

Simple script helper with similar functionality as the built in link_tag().

  - Only tested with CI3 maybe works with 2.x as well
  - Copy script_helper.php to your application/helpers directory
  - Load the helper in your controller or in config/autoload.php

### Version
1.0

### Usage

```php
echo script_tag('assets/js/myfile.js', true, false, true, false);
```
will generate

```html
<script src="http://mysite.com/assets/js/myfile.js" async defer></script>
```

### Params
- string script source
- bool async (bool false to skip)
- string charset (bool false to skip)
- bool defer (bool false to skip)
- string type (bool false to skip)