1.2.0
=====

* Adds Django 1.9 compatibility.
* Adds Python 3.5 support.
* Drops Django 1.4, 1.5, & 1.6 support.
* Drops Python 2.6 & 3.2 support.

1.1.3
=====

* Fixes an issue occurring when parsing paragraphs with attributes.

1.1.2
=====

* Adds a reliable Django 1.7 support.
* Adds Django 1.8a1 compatibility.

1.1.1
=====

* Fixes an exception occurring when an empty string is passed to the parser.

1.1.0
=====

* Rewrites django-terms using lxml; more than a 300% speedup!
* Tested with Django 1.7; migrations still need to be rewrote without South.

1.0.7
=====

* Supports Django 1.6 and Python 3.4.

1.0.6
=====

* Adds a ``TERMS_ENABLED`` setting.
* Improves CMS menu nodes building.

1.0.5
=====

* Adds django-haystack 2.x.x compatibility.

1.0.4
=====

* Adds Portuguese (Brazil) translation.

1.0.3
=====

* Removes a useless database hit.
* Separates docs and put them on ReadTheDocs.

1.0.0
=====

* Allows for per-object case-sensitiveness.
* Fixes all known bugs.
* Rewrites django-terms to use beautifulsoup4.  It eases development.
* Adds lots of tests.
* Adds Travis Continuous Integration.
* Adds Django 1.5 compatibility.
* Adds Python 3 compatibiliy.
