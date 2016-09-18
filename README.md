#Slim skeleton

####About

Skeleton application for projects using Slim PHP framework

#### Includes
* Slim
* monolog
* php-view templating
* flash messages
* pdo connector
* bootstrap, jQuery and jQuery UI


####Usage

* clone
* download composer dependencies
* `php -S localhost:8080`
* Made for use in personal projects, and it will hopefully be updated with time

####Architecture

* Each controller should extend Base controller
  * Base controller provides gives you access to Helper class
  * It injects flash messages and provides some helper methods
* Custom models should extend Base model
  * if working with database (Sqlite atm)
  * Base provides helper methods to get data easier
*  Templates use `fetch` method to include other templates
  * `<?php echo $this->fetch('head.phtml'); ?>`


####License 
MIT
