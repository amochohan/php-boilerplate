# PHP Project Boilerplate

I found myself writing the same project boilerplate time and time again, so decided to create this boilerplate project 
to help reduce the time required when starting a new piece of code.

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/drawmyattention/phpaddressr/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/drawmyattention/phpaddressr/?branch=master) 
[![Build Status](https://travis-ci.org/drawmyattention/php-boilerplate.svg?branch=master)](https://travis-ci.org/drawmyattention/php-boilerplate)
[![License](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](http://www.opensource.org/licenses/MIT)


## What it includes

- Basic Composer project
- PSR-4 autoloading of src files
- PSR-0 autoloading of tests
- PHPUnit development dependency
- (Optional) config.php autoloaded file
- Travis-ci.org configuration file

## Using this boilerplate

Simply clone using one of the following methods:

**SSH**

    git clone git@github.com:drawmyattention/php-boilerplate.git YourProjectName
    
**HTTPS**

    git clone https://github.com/drawmyattention/php-boilerplate.git YourProjectName
    
Then edit the composer.json file to set your own project meta information and define your dependencies as normal. An 
example class and test exists, which you can use as a starting point or feel free to delete them and start from scratch.
Just remember to set your namespace accordingly.

## Notes

The .gitignore file lists composer.lock, which you may wish to commit to source control for your own project. Placeholders are 
provided for status badges from Travis and Scrutinizer, remember to update the paths to these accordingly.