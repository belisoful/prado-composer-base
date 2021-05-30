PRADO Composer Base extension example
=====================================

Minimal base composer extension for PRADO Framework


Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist belisoful/prado-composer-base "*"
```

or add

```
"belisoful/prado-composer-base": "*"
```

to the require section of your `composer.json` file.


Setup
-----

Once the extension is installed, load the module in your Prado application config
with the TComposerManager Module.  All packages with an extra/bootstrap class are
loaded regardless of being specified:

```xml
<module class="TComposerManager">
</module>
```

To give the extension properties and module load order load the module like this:

```xml
<module class="TComposerManager">
	<package id="belisoful/prado-composer-base" PropertyA='value1' />
</module>
```


Usage
-----

Follow the panel link to http://application/web/index.php?page=Example
On the index page you'll see extension specific content.

