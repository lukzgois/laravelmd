# Custom rulesets to check Laravel projects with PHP Mess Detector

This rules will check a Laravel project with PHPMD.  
The custom rules are:

* Allow variables with 2 characters (because $id in some files is very acceptable);
* Allow "static" access to the Laravel Facades
* Doesn't force you to name variables and properties in camelCase.
