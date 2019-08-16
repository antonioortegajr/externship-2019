# Techincal Recomendations

## About

This document is technical recommendations for the website. This is meant for the person or persons who will be developing the webstite.

### DNS

The SSL certificate expires October 12, 2019 (59 days from today, Aug 14th)

All http traffic should also be redirected to https automaticly.

### Caching

This website appears to not have a caching layer. Inculstion of a caching plugin for WP like w3 total cache could help performence. Another layer like clouldflare could help with caching and provide SSL as well.

### Images

While a department with experiance manipulating images can resize/adjust images for the web, a website that has amny users can get large images uploaded hurting performance.

WP plugin "smush it" can auto adjust images for the web with a single click interface.

### Anyaluytics

Google analytics is not present on the site and while traffic and bounce rate may not be metrics important now, it is good to have a benchmark. Additionaly claiming the site ig google web masters tools will help highlight pages that return 404.

### Security

It is unknonw to me the version of php, wordpress, the wordpress theme, or the plugins are at. These could be larege security concerns if out of date.
