wkhtmltoimage
================

This repository contains the static compiled binaries from the [wkhtmltopdf project](http://wkhtmltopdf.org/).
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

## Installation

_Hint_:
The version of the binary is equal to the git tag.
To install the latest version, use '0.12.5'.

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package with:

    composer require zxp86021/wkhtmltoimage-amd64

The binary will then be located at:

    vendor/zxp86021/wkhtmltoimage-amd64/bin/wkhtmltoimage-amd64

Also a symlink will be created in your configured bin/ folder, for example:

    vendor/bin/wkhtmltoimage-amd64
