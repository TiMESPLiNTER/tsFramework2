tsFramework2
============

The new tsFramework will fix some issues from the first version and brings the framework to up-to-date technologies.

The new framework will be

* requiring [PHP 5.4 or higher](http://php.net/manual/de/migration54.php)
* using decoupled components
* using [composer](https://getcomposer.org/) as dependency manager
* unit testable with [PHPUnit](http://phpunit.de/)
* using [Travis-CI](https://travis-ci.org/) for continuous integration

## Basic components
So the new framework is basically just a collection and combination of decoupled modules.

The following list shows all the components that the framework will need and if they are already implemented. The list
of components can be altered at any time so it is not concluding.

* **[tsfw-common](https://github.com/TiMESPLiNTER/tsfw-common)** *implemented*  
PHP library to abstract common operations with strings, arrays, etc
* **[tsfw-session](https://github.com/TiMESPLiNTER/tsfw-session)** *implemented*  
A library which maps most used native `session_*` functions of PHP to an OO interface. And provides some basic implementations of it.
* **tsfw-config** *in progress*
* **tsfw-routing**
* **tsfw-http**
* **tsfw-core**

## Additional components

There will be additional (optional) components which will be available for the framework but not needed to get it working.

* **[tsfw-db](https://github.com/TiMESPLiNTER/tsfw-db)** *in progress*
* **[tsfw-auth](https://github.com/TiMESPLiNTER/tsfw-auth)** *in progress*  
A library to authenticate with different methods from different data sources