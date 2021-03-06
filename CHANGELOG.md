Changelog
=========

0.4.0
-----

* Use classes for scan modules instead of python modules
* Improve command line arguments (-c for config, -m for scan modules)
* Add redirect\_chain key to result (chromedevtools)
* Change data structure for requests and responses (chromedevtools)
* Make Debugger resumption more robust (chromedevtools)

0.3.2
-----

* Rebuild packages because 0.3.1 contained some uncomitted changes.

0.3.1
-----

* Bugfix: JavaScript got never resumed after being paused by the Debugger.

0.3.0
-----

* Fix --config argument
* Add RequestExtractor.save\_headers option to chromedevtools options.

  This will store all request and response headers for each individual request
  to the result JSON.

0.2.1
-----

* Fix Python 3.5 compatibility (ModuleNotFoundError is not available in 3.5)

0.2
---

* Initial public release
