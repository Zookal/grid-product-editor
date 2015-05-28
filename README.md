Grid Product Editor for Magento 1
==========

Edit product attributes in the back end grid.

Features
--------

* F1
* F2
* F3

Installation Instructions
-------------------------

### Via modman

- Install [modman](https://github.com/colinmollenhour/modman)
- Use the command from your Magento installation folder: `modman clone https://github.com/Zookal/grid-product-editor/`

### Via composer

- Install [composer](http://getcomposer.org/download/)
- Install [Magento Composer](https://github.com/magento-hackathon/magento-composer-installer)
- Create a composer.json into your project like the following sample:

```json
{
    ...
    "require": {
        "zookal/grid-product-editor":"*"
    },
    "repositories": [
	    {
            "type": "composer",
            "url": "http://packages.firegento.com"
        }
    ],
    "extra":{
        "magento-root-dir": "./"
    }
}
```

- Then from your `composer.json` folder: `php composer.phar install` or `composer install`

### Manually

- You can copy the files from the folders of this repository to the same folders of your installation


### Installation in ALL CASES

* Clear the cache, logout from the admin panel and then login again.

Uninstallation
--------------

* Remove all extension files from your Magento installation
* Via modman: `modman remove grid-product-editor`
* Via composer, remove the line of your composer.json related to `Zookal/grid-product-editor`

License
-------

[Open Software License (OSL 3.0)](http://opensource.org/licenses/osl-3.0.php)


Author
------

Cyrill at Schumacher dot fm or cyrill at zookal dot com

[My pgp public key](http://www.schumacher.fm/cyrill.asc) / on [keybase.io](https://keybase.io/cyrill)

[@SchumacherFM](https://github.com/SchumacherFM)
