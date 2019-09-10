# lemongraphql-module

Pertama harus install module installer

```composer require joshbrw/laravel-module-installer```

Karena ini private package, edit composer.json, referal : https://getcomposer.org/doc/05-repositories.md#vcs
```
{
    ...
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/izorwebid/lemongraphql-module"
        }
    ],
    "require": {
        ...
        "izorwebid/lemongraphql-module": "dev-master"
    },
    ...
}
```

Bagian dibawah ini hanya untuk public package

```composer require izorwebid/lemongraphql-module```
