# AdminLTE v3 Theme Sprinkle (UserFrosting 4.4)

# Installation

Edit UserFrosting `app/sprinkles.json` and add the following to the `require` list : `"userfrosting/admin-lte": "~4.1.1"`. Also add `admin-lte` to the `base` list. For example:

```
{
    "require": {
        "userfrosting/admin-lte": "~1.0.0"
    },
    "base": [
        "core",
        "account",
        "admin",
        "admin-lte"
    ]
}
```

### Update Composer

- Run `composer update` from the root project directory.

### Run Assets Build

- Run `php bakery build-assets` from the root project directory.
