---
layout: news
title: OSGi R7 Highlights - The Converter
author: David Bosschaert
published_at: 2018-04-10
link: https://blog.osgi.org/2018/04/osgi-r7-highlights-converter.html
---
OSGi enRoute is an ongoing project that normally increments in minor version changes. However, OSGi enRoute is this time a major version because we made a lot of changes to the underlying machinery.
For the use of OSGi enRoute there is not much difference. However, under the cover we’ve made it possible to share repositories between Maven and Bndtools and we phased out the use of JPM in favor of defining external dependencies in a Maven POM.
OSGi enRoute requires Bndtools 3.3.0 or later.
The tutorials have been adapted to the new release and an app note was created to describe the release of OSGi enRoute to Maven.
From the OSGi enRoute bundles there have not been major changes. The biggest change has been in the web server support (static resource, web resources, caching) that now also supports the concept of a conditional servlet. A servlet that allows to reply with a false when called and when it cannot handle the URI. The REST support has also undergone a number of changes and supports an experimental implementation of the draft 3.0 OpenAPI.