Gists
-----

A simple PHP class that provides an easy interface for gists GitHub.

Usage
-----

```php

    require_once('src/gists.class.php');

    $obj = new Gist();

    $user = 'thinkphp'; 

    $resp = json_decode( $obj->all( $user ), true );

    print_r( $resp );
```
