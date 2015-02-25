# Code Retreat PHP Skeleton

## Installation

First, install [Composer](https://getcomposer.org) and [git](http://git-scm.com) if you don’t have them, already.

Then clone this repository:


```
$ git clone https://github.com/nb/code-retreat-skeleton-php.git game-of-life
```

Then, run:

```
$ composer install
```

in the `game-of-life` directory.

You can confirm it’s working by running:

```
$ composer run-script test
```

## Writing Tests

This primer uses [PHPUnit](https://phpunit.de/). The project website has decent documentation about how it works.

The game of life code is short enough so that it’s fine if we write both the code and the tests in the same file.

## Running Tests

```
$ composer run-script test
```

## Starting a New Session

Deleting code is hard on the mind, but not hard on the console. Just run:

```
$ composer run-script reset
```

**WARNING:** This will **permanently** delete all modifications after the previous commit.
