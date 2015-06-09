# PHP-CSS-Parser-

A PHP Class that can parse CSS and return the results in a PHP array.

NOTE: **PHP CSS Parser** utilizes [Loco Parser Library](http://qntm.org/loco).

#Support
The following were currently not yet added to **PHP CSS Parser**'s grammar:
- Comments ( /**/ )
- Media Queries ( @cond etc and etc { block {} } )
- At-rules ( @rule )

usage:
```php

	// include css parser class
	require_once "CSS-Parser.php";

	// use the parser
	$result = CSSParser::parse($str);

	// show result
	print_r($result);


```

