---
title: First Alpha of Bean Validation 2.0 Reference Implementation Available
url: http://beanvalidation.org/news/2017/02/16/first-alpha-of-bean-validation-2-0-reference-implementation/
date: '2017-02-16'
author: Gunnar Morling
feed_url: https://beanvalidation.org/news/news.atom
---
A few days after the release of the Bean Validation 2.0 Early Draft 1
there is now also a first version of the reference implementation available.


If you are using Apache Maven, add the following dependency to your pom.xml to give it a test ride: org.hibernate.validator hibernate-validator 6.0.0.Alpha1 The 6.0.0.Alpha1 release provides all the functionality of the Early Draft 1.
In addition there is support for




nested type argument constraints, e.g. Map > itemsByCategory;
this addresses open question #1 from the proposal for the validation of container elements


definition of constraints using Lambda expressions and method...
