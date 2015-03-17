# is-type
I had founded JavaScript library call [is-type](https://github.com/juliangruber/is-type) and I am thinking to create something like that in PHP also. Let's roll ...

##Installation

##Usage

Create `index.php` and put the following code and run `$ php -S localhost:8000`

	<?php

	// Display Errors On
	ini_set('display_errors', 'On');

	$autoload = __DIR__.'/vendor/autoload.php';

	if ( ! file_exists($autoload))
	{
	  exit("Need to run \"composer install\"!");
	}

	require $autoload;

	use SetKyar\IsType\IsType;
	 
	echo IsType::initialize();

##Contributing
- Fork it ( https://github.com/setkyar/is-type)
- Create your feature branch (git checkout -b my-new-feature)
- Commit your changes (git commit -am 'Add some feature')
- Push to the branch (git push origin my-new-feature)
- Create a new Pull Request
- Stars are welcome too :smile:

## License
[WTFPL](http://www.wtfpl.net/)