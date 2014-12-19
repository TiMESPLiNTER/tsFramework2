tsFramework2
============

The new tsFramework will fix some issues from the first version and brings the framework to up-to-date technologies.

The new framework version 2 will be

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
A simple configuration module which can read YAML, JSON, XML and plain PHP config files but can also be extended to understand other formats.
* **[tsfw-routing](https://github.com/TiMESPLiNTER/tsfw-routing)** *in progress*  
For matching URIs to controllers and fetching potential parameters out of them.
* **[tsfw-http](https://github.com/TiMESPLiNTER/tsfw-http)** *implemented*    
Dealing with HTTP requests and responses in a very simple OO manner.
* **[tsfw-i18n](https://github.com/TiMESPLiNTER/tsfw-i18n)**
Dealing with different languages and other locale conventions.
* **tsfw-core**  
The flow of the framework and the place where all the components get linked to each other.

## Additional components

There will be additional (optional) components which will be available for the framework but not needed to get it working.

* **[tsfw-db](https://github.com/TiMESPLiNTER/tsfw-db)** *in progress*  
A very easy to use database library which extends PDO with some nice and straight-ahead methods.
* **[tsfw-auth](https://github.com/TiMESPLiNTER/tsfw-auth)** *in progress*  
A library to authenticate with different methods from different data sources