cpanel UAPI PHP class
=====================

PHP class to provide an easy to use interface with cpanels UAPI.

Usage
=====

See the example files, but typical useage takes the form of:

```
//load class
$cpuapi = new cpaneluapi();

//Set the scope to the module we want to use. in this case, Mysql
$cpuapi->scope = 'Mysql';

//call the function we want like this. Any arguments are passed into the function as an array, in the form of param => value.
$cpuapi->get_restrictions(); 
```