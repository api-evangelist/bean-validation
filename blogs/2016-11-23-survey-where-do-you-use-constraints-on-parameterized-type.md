---
title: Survey - Where do you use constraints on parameterized type?
url: http://beanvalidation.org/news/2016/11/23/survey-constraints-and-parameterized-type/
date: '2016-11-23'
author: Emmanuel Bernard
feed_url: https://beanvalidation.org/news/news.atom
---
For Bean Validation 2, we are working on the support for Collection<@Email String>, Optional<@Min(3) Integer> etc.
This has been a very common request and with Java 8 type use support, we can how achieve this.
However, we need your feedback on how you would use such feature.




Some context


We have support not only for collections, Optional, Java FX properties but also for what we call custom parameterized containers.
We are wondering a few things about custom parameterized containers, namely how common they are.
This will affect the trade-offs we want to make on the design of that feature.


What is a container?

A container is a type...
