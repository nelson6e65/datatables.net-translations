# DataTables Internationalization
[![License](https://img.shields.io/bower/l/datatables.net-translations.svg)](LICENSE)
[![Bower](https://img.shields.io/bower/v/datatables.net-translations.svg)](http://bower.io/search/?q=datatables.net-translations)
[![GitHub commits](https://img.shields.io/github/commits-since/nelson6e65/datatables.net-translations/v0.2.0.svg)]()


## Description
Language files for [DataTables](http://datatables.net) jQuery Plugin, based on [DataTables/Plugins](https://github.com/DataTables/Plugins), powered by [Transifex](https://www.transifex.com/nelson6e65/datatables-translations/) Translation Platform.

## Installing

### Bower
You can install translations for your project with [Bower](http://bower.io):

```bash
bower install --save datatables.net-translations
```

>You can use a build tool, like [Gulp](http://gulpjs.com/) to publish `locale` directory in your public directory, like other assets.

### Manual
- Download the latest [release](https://github.com/nelson6e65/datatables.net-translations/releases).
- Unzip that download.
- Rename the resulting folder to `datatables.net-translations`.
- Then move this folder into your assets directory.


## Usage
Just follow instructions in [DataTables manual](http://datatables.net/manual/i18n).

Translations files named following [ISO 639-1 code namming standard](http://www.loc.gov/standards/iso639-2/php/code_list.php) and using `.json` extension.
So, for example, default Spanish language file is `locale/es/default.json`.

That is the file you will use in the `language.url` option:

```js
$('#example').DataTable( {
    language: {
        url: '/assets/datatables.net-translations/locale/es/default.json'
    }
} );
```

There is another alternative, using mostly icons, but requires [Font Awesome](http://fortawesome.github.io/Font-Awesome/). Usage:

```js
$('#example').DataTable( {
    language: {
        url: '/assets/datatables.net-translations/locale/es/iconic.json'
    }
} );
```

## Contributing

### Translate
In order to translate this project, you should join the project in [Transifex](https://www.transifex.com/nelson6e65/datatables-translations/). More info in [TRANSLATORS.md](TRANSLATORS.md) file.

>Note: If you are not registered yet, you can easily register via GitHub.
