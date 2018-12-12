fetch-some-proxies [![Python 2.6|2.7](https://img.shields.io/badge/python-2.6|2.7-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-Public_domain-red.svg)](https://wiki.creativecommons.org/wiki/Public_domain)
====

Simple Python script for fetching "some" (usable) proxies. It fetches (periodically updated) list of public proxies and automatically finds in a quick manner those usable in that same moment (Note: testing of SOCKS proxies is currently possible only on non-Windows platforms).

Why should you use it? Well, if you've ever used free proxy lists around you'll know the pain of finding actually working proxies. This tool will automatically do the list fetching and proxy testing for you. Also, only proxies that support HTTPS traffic will be returned, which guarantees access to majority of Internet sites.

![fetch](https://i.imgur.com/WLWRGcA.png)

Requirements
----

[Python](http://www.python.org/download/) version **3.6.x** is required for running this program.
