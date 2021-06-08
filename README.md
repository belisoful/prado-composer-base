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

Once the extension is installed, load the extension in your Prado application config by specifying the extension name as a module id.  

Add the module to the application configuration without the class.  For example, like this:

```xml
<modules>
	<module id="belisoful/prado-composer-base" PropertyA='value1' />
</module>
```


Usage
-----

Add the following Application Parameter to your application configuration: PluginContentId

Set PluginContentId to the name of the main TPlaceholderContent ID of your layout so the plugins can be loaded properly.

Follow the panel link to http://application/web/index.php?page=Example
On the index page you'll see extension specific content.

