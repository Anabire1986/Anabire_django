django-url-shortener
--------------------

This is URL shortening application written using the Django framework. It began
as a fork of https://github.com/Anabire1986/Anabire_django.git, but now includes
functionality for creating custom shortened URLs.

The project has also been updated for Django 1.4 and now includes an extensive
tests.py.

Features
--------

* base62 values of the URL's database id. base62 is: `[a-zA-Z0-9]`. `(26 + 26 +
  10 = 62)`

* Keeps count of how many time each URL is followed.
