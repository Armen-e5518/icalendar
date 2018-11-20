iCalendar Widget for Yii2
========================

Installation
------------
The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
composer require armen-e5518/icalendar "@dev"
```
or add

```json
"armen-e5518/icalendar" : "@dev"
```

to the require section of your application's `composer.json` file.



Usage
-----

Using a model with a basic preset:

```

use icalendar\iCalendar;


$ical = new iCalendar(); 
$lines = $ical->load( file_get_contents( 'example.ics' ) ); 

var_dump( $lines ); 
```
