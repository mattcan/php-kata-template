# PHP Kata Template

This project is meant to be used as a template for doing Kata in PHP. The goal
is to get setup very quickly so that you can get straight to practicing.

## Requirements

* Composer - [https://getcomposer.org/download/](https://getcomposer.org/download/)
* PHP Unit - [https://phpunit.de](https://phpunit.de)
* Unixy environment (only tested with [Windows Subsystem for Linux][1] so should work
	with Ubuntu 14.04 as well)

[1]: https://msdn.microsoft.com/en-us/commandline/wsl/faq

## Getting Started

1. Pick Kata from [http://codekata.com](http://codekata.com)
1. Clone repository to your kata folder of choice:

	```sh
	git clone https://github.com/mattcan/php-kata-base.git TheKataName_todaysdate
	```

1. Run Composer install:

	```sh
	composer install
	```

You can now go ahead and start doing your Kata!

## Namespaces

Your `src/` folder is namespaced to `Kata\`.

Your `tests/` folder is namespaced to `Kata\Tests\`.

## Available Commands

The `composer.json` file comes with a few commands:

* **test:** Will run PHPUnit. Best to run this from your apps root directory
* **test-coverage:** Will run PHPUnit with HTML test coverage which is dumped
	into a `coverage` folder

## Code Of Conduct

I'm a big fan of making things more open to others which is why I've got a [Code
of Conduct](CODE_OF_CONDUCT.md) up for you to check out.

## Contributing

This repository is open for pull requests! If you're up for contributing, please
checkout the [contribution guidelines](CONTRIBUTING.md) as well as take a look
through the [issue
log][2].

[2]: https://github.com/mattcan/php-kata-template/issues?utf8=%E2%9C%93&q=is%3Aopen%20is%3Aissue
