#Installation:

1. **Copy** `phalcon.so` to `/Applications/MAMP/bin/php/php5.5.x/lib/php/extensions/no-debug-non-zts-20121212`
2. Add `extension=phalcon.so` to the end of `php.ini` (Open MAMP click on File → Edit Template → PHP → PHP 5.5.x php.ini)
3. **Restart** MAMP.

>It's only compiled against the PHP 5.5.18 and PHP 5.4.34 (MAMP 3.0.x).

Older [releases](https://github.com/majksner/php-phalcon-mamp/releases)

##Dependencies:
N/A

##Change Log:
* 0.13 - Phalcon 2.0.3 build for new MAMP 3.3 and PHP 5.6.10
* 0.12 - Phalcon 2.0.1 build for new MAMP 3.2.1 and PHP 5.6.7
* 0.11 - Phalcon 1.3.4 build for new MAMP 3.0.7.3, PHP 5.5.18 and PHP 5.4.34
* 0.10 - Phalcon 1.3.3 build for new MAMP 3.0.7.3, PHP 5.5.18 and PHP 5.4.34
* 0.9 - Phalcon 1.3.2 build for new MAMP 3.0.5, PHP 5.5.10 and PHP 5.4.26
* 0.8 - Phalcon 1.3.1 build for new MAMP 3.0.4, PHP 5.5.10 and PHP 5.4.26
* 0.7 - Phalcon 1.3.0 build for new MAMP 3.0.3, PHP 5.5.10 and PHP 5.4.25
* 0.6 - Phalcon 1.2.6 build for new MAMP 3.0.1 and PHP 5.5.9
* 0.5 - Updated to Phalcon 1.2.6
* 0.4 - Updated to Phalcon 1.2.5
* 0.3 - Updated to Phalcon 1.2.4
* 0.2 - Updated to phalcon 1.2.3
* 0.1 - Initial Release

## Proof

If everything is fine `phpinfo();` should look like this.

* Phalcon 2.0.3 + MAMP 3.3 + PHP 5.6.10
![ScreenShot](http://i.imgur.com/Ku58HJa.jpg)

* Phalcon 2.0.1 + MAMP 3.2.1 + PHP 5.6.7
![ScreenShot](http://i.imgur.com/hJ8MDhh.png)
