# _BlizzCMS Plus_
**_BlizzCMS Plus_** is a complete refactored version of BlizzCMS. This version developed is constantly updated by the Team members of **WoW-CMS** and **Contributors**.

* [Website](https://wow-cms.com)
* [Discord Chat](https://discord.gg/vZG9vpS)

> This CMS **will not support PHP 8** due to the old structure of its framework.

[![Project Status](https://img.shields.io/badge/Status-Refactoring-red.svg?style=flat-square)](#)
[![Project Version](https://img.shields.io/badge/Version-1.1.0-green.svg?style=flat-square)](#)

| Requirements | Description |
| :----------- | :---------- |
| **PHP Version** | **7.3 or 7.4** is recommended |
| **Apache Modules** | mod_rewrite |
| **PHP Extensions** | curl - gd - gmp - mbstring - mysqli - openssl - soap |

## In linux (Apache Modules)

```sh
a2enmod headers
a2enmod rewrite
a2enmod expires
```

### Edit Sites Available
/etc/apache2/sites-available/000-default.conf

```
<Directory "/var/www/html">
	AllowOverride All
</Directory>
```

### Restarting the service

```sh
/etc/init.d/apache2 restart or service apache2 restart
```

## Copyright

Copyright © 2020 [WoW-CMS](https://wow-cms.com).
