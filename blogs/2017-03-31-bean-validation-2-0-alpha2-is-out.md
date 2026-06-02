---
title: Bean Validation 2.0 Alpha2 is out
url: http://beanvalidation.org/news/2017/03/31/bean-validation-2-0-alpha2-is-out/
date: '2017-03-31'
author: Gunnar Morling
feed_url: https://beanvalidation.org/news/news.atom
---
I’m happy to announce the release of the Alpha2 release of the Bean Validation 2 API and specification.


This release contains several improvements and clarifications around the validation of container elements (think List<@Email String>):




Custom value extractors can now be passed in when bootstrapping a validator factory or validator (via API or XML)


Value extractors are detected via the Java service loader mechanism
(e.g. allowing libraries to ship their own extractors for custom collection types)


Property paths for constraint violations on container elements will now contain a node of the new type CONTAINER_ELEMENT


Container element constraints can be specified in XML mapping descriptors




There are also some...
