# Gravity Forms ConnectWise Add-On

Integrates Gravity Forms with ConnectWise, allowing form submissions to be automatically sent to your ConnectWise account.

Developer Guide
---------------

To run, test, and develop the Multisite Login Logos plugin with Docker container, please simply follow these steps:

1. Build the container:

  `$ docker build -t wptest .`
 
2. Test running the PHPUnit on this plugin:

  `$ docker run -it -v $(pwd):/app wptest /bin/bash -c "service mysql start && phpunit"`

Changelog
----------

= 1.2.3 =
* Match contact and email before create company 

= 1.2.2 =
* Create Note in Contact and Company

= 1.2.1 =

* Add company_id when create new activity and new service ticket for version 2017_1 

= 1.2.0 =

* Add company_id when create new opportunity for version 2017_1 
* Strip HTML tags when add note to ConnectWise 

= 1.1.4 =

* Add page size = 200 when get data from connectwise

= 1.1.3 =

* Fix unsued version control path

= 1.1.2 =

* Add prefix for staging URL

= 1.1.1 =

* Retry with DefaultContact when DefaultContactId fail 

= 1.1.0 =

* Service ticket type, Service ticket subtype, Service ticket item
* Have better API version control

= 1.0.2 =

* Improved banner ads path in JS script (no hardcode).

= 1.0.1 =

* Fixed banner ads path in JS script.

= 1.0 =

* Launched!
