Loader tags and modifiers for Fenom from FS
=======

Just like Smarty.

# Install

Use composer:
```json
{  
    "require": {
        "fenom/fs-entity-loader": "1.*"
    }
}
```

# Setup

Add traits into your Fenom class:

```php

class MyFenom extends Fenom {
    use Fenom\EntityLoaderTrait;
    use Fenom\FSEntityLoaderTrait;
}
```

# Use

```php

$fenom->addPluginDir('./plugins');
```

# Format
