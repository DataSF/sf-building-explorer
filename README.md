## SF Building Explorer

This is a quick and dirty demonstration project showcasing the [use of building footprints](https://data.sfgov.org/Housing-and-Buildings/Building-Footprints/72ai-zege) in an application to link various administrative data together. It is not built to production standards. It's just basic HTML, CSS and javascript with some minimal libraries to support mapping. Libraries include:

1. [Mapbox GL JS](https://github.com/mapbox/mapbox-gl-js)
2. [Turf.js](https://github.com/Turfjs/turf)
3. [Wellknown](https://github.com/mapbox/wellknown)

Read more in our [blog post about building footprints](http://clever-goat1.cloudvent.net/blog/new-sf-building-footprints-released-with-3d-characteristics/).

### Running locally

On the command line:
1. `git clone git@github.com:DataSF/sf-building-explorer.git`
2. `cd sf-building-explorer`
3. `python -m SimpleHTTPServer 9000`*

In your browser:
1. Go to http://localhost:9000

* [You must have python 2.7 installed to run SimpleHTTPServer](https://docs.python.org/2/library/simplehttpserver.html)

### Contributing

This is just a demonstration application, so no heavy development right now, but if you find any issues, please feel free open an issue and describe the problem clearly so we can fix it.

### Copyright and License

Code copyright 2017 the City and County of San Francisco. Code released under the [MIT License](https://github.com/DataSF/sf-building-explorer/blob/master/LICENSE).
