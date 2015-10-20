# JSONProxy [![Build Status](https://travis-ci.org/afeld/jsonp.png?branch=master)](https://travis-ci.org/afeld/jsonp)

Simple HTTP proxy that enables cross-domain requests to any JSON API.  See https://jsonp.afeld.me for documentation.  See the [releases](https://github.com/afeld/jsonp/releases) page for the [client library](jsonp.js) changelog.

## Running Locally

See [`.travis.yml`](.travis.yml) for compatible Node versions.

```
npm install
npm start
```

and do requests to `http://localhost:8000/?url=...`

## See Also

* https://github.com/jpillora/xdomain
* https://github.com/mapbox/corslite
* http://enable-cors.org
