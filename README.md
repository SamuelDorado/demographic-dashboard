# \<demographic-dashboard\>



## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Install the Json Server

Install json-server through `npm i -g json-server` Then run `json-server db.json` to serve your mock data locally.

## Viewing Your Application

```
$ json-server db.json
```

then in another terminal `cd` to your application again and run  

```
$ polymer serve
```

## Running Tests

```
$ polymer test -l chrome
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test -l chrome` to run your application's test suite locally.
