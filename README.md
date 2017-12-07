Jasper.php
======
Flowl Jasper project clone. https://github.com/flowl/jasper

PHP library providing smooth access to JasperReports server via REST / REST v2 API

Like Flowl, we did not like the original JasperSoft PHP library. Some additions:

* Added a fourth parameter to Jasper class contructor to enable SSL when required. By default it is set to false.
* Added URL encoding for all parameters value in getReport() method. It comes in handy if you assume you could pass parameters values containing special characters