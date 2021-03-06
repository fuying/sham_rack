## 1-May-2012 [mdub@dogbiscuit.org]

* Validate arguments to `ShamRack#mount`.
* Update for compatibility with patron-0.4.x.

## 18-Oct-2010 [mdub@dogbiscuit.org]

* Add support for Patron.

## 02-Sep-2010 [mdub@dogbiscuit.org]

* Fixes to support Ruby-1.9.x.

## 08-Jul-2010 [jyurek@thoughtbot.com]

* Add support for Mechanize.

## 11-Mar-2010 [mdub@dogbiscuit.org]

* Added generic `StubWebService`.

## 15-Jan-2010 [jeremy.burks@gmail.com]

* Fix an incompatibility with rest-client 1.2.0.

## 27-Nov-2009 [mdub@dogbiscuit.org]

* Change of approach: extend rather than reimplement `Net:HTTP`.  This should improve coverage of all the weird and wonderful ways of using the `Net:HTTP` API.

## 5-Jun-2009 [mdub@dogbiscuit.org]

* Add support for `Net::HTTP.get_response`.
* Pass back headers provided by Rack app in the `HTTPResponse`.

## 3-Jun-2009 [mdub@dogbiscuit.org]

* Introduced `ShamRack#at` to simplify registration of apps.

## 13-May-2009 [mdub@dogbiscuit.org]

* Added accessors on HTTP object for address, port and rack_app.
* Added accessors to imitate "net/https".
