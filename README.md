[![Build Status](https://scrutinizer-ci.com/g/rmcdaniel/angular-codeigniter-seed/badges/build.png?b=master)](https://scrutinizer-ci.com/g/rmcdaniel/angular-codeigniter-seed/build-status/master) [![Code Coverage](https://scrutinizer-ci.com/g/rmcdaniel/angular-codeigniter-seed/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/rmcdaniel/angular-codeigniter-seed/?branch=master)
# angular-codeigniter-seed

## Features

- Single-page application (AngularJS)
- Responsive (Bootstrap 3)
- Multi-language
- User manager
- Role-based ACL

## Demo

https://bitlab.co/acs

User: foo@bar.com  
Pass: password123

The demo resets every hour.

## Requires

mcrypt

````
sudo apt-get install php5-mcrypt
sudo php5enmod mcrypt
sudo service apache2 restart
````

## Installation

````
php api/index.php cli install
php api/index.php cli add administrator foo@bar.com password123
````
