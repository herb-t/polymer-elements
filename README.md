## Polymer Calendar

A custom calendar widget that works with the google calendar API and utilizes the google client loader Polymer element.
<calendar-data> brings in the data and <calendar-main> acts as the view.  

### Setup

Both elements were built using the [Polymer CLI](https://www.npmjs.com/package/polymer-cli)

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
