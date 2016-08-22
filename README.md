Friendly MIME PHP
======

This package allows you to convert a MIME type into a human readable description.

Descriptions thanks to [http://www.freeformatter.com/mime-types-list.html](freeformatter.com).

## Installation

You can install this package through Composer. Add the following line to your composer.json `require` object:

```
"jcoded/friendly-mime": "^1.0"

```
## Usage

There is a simple static function to use:

```php
$friendlyName = \JCoded\FriendlyMime\FriendlyMime::getFriendlyName($mimeType);
```

