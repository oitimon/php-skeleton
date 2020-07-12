# php-skeleton

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status](https://travis-ci.org/oitimon/php-skeleton.svg?branch=002-naming)](https://travis-ci.org/oitimon/php-skeleton)
[![Coverage Status](https://scrutinizer-ci.com/g/oitimon/php-skeleton/badges/coverage.png?b=002-naming)][link-scrutinizer]
[![Quality Score](https://scrutinizer-ci.com/g/oitimon/php-skeleton/badges/quality-score.png?b=002-naming)][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

**Note:** Replace ```Oleksandr``` ```oitimon``` ```https://github.com/oitimon``` ```yeremeyev.alexander@gmail.com``` ```oitimon``` ```php-skeleton``` `````` with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line. You can run `$ php prefill.php` in the command line to make all replacements at once. Delete the file prefill.php as well.

This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Structure

If any of the following are applicable to your project, then the directory structure should follow industry best practices by being named the following.

```
bin/        
build/
docs/
config/
src/
tests/
vendor/
```


## Install

Via Composer

``` bash
$ composer require oitimon/php-skeleton
```

## Usage

``` php
$skeleton = new Oitimon\PhpSkeleton();
echo $skeleton->echoPhrase('Hello, League!');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email yeremeyev.alexander@gmail.com instead of using the issue tracker.

## Credits

- [Oleksandr][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/oitimon/php-skeleton.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/oitimon/php-skeleton/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/oitimon/php-skeleton.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/oitimon/php-skeleton.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/oitimon/php-skeleton.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/oitimon/php-skeleton
[link-travis]: https://travis-ci.org/oitimon/php-skeleton
[link-scrutinizer]: https://scrutinizer-ci.com/g/oitimon/php-skeleton/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/oitimon/php-skeleton
[link-downloads]: https://packagist.org/packages/oitimon/php-skeleton
[link-author]: https://github.com/oitimon
[link-contributors]: ../../contributors
