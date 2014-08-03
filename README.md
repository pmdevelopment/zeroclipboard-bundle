zeroclipboard-bundle
====================

Symfony2 Bundle for [ZeroClipboard](https://github.com/zeroclipboard/zeroclipboard) to create "Copy to Clipboard" Buttons.


Installation
------------

Add by composer:

``` bash
composer require pmdevelopment/zeroclipboard-bundle:dev-master
``` 


Add to AppKernel to enable bundle:

``` php
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new PM\Bundle\ZeroClipboardBundle\PMZeroClipboardBundle(),
    );
}
```

Add JavaScripts to use ZeroClipboard:

``` html
  <script type="text/javascript" src="{{ asset("/bundles/pmzeroclipboard/js/ZeroClipboard.min.js") }}"></script>
  <script type="text/javascript" src="{{ asset("/bundles/pmzeroclipboard/js/config.js") }}"></script>
```


Documentation
-------------

For examples and documentation visit the [ZeroClipboard](https://github.com/zeroclipboard/zeroclipboard) repository.
