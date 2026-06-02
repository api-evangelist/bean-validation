---
title: First milestone release of Jakarta Validation 4.0
url: http://beanvalidation.org/news/2025/11/12/bean-validation-4-0-M1/
date: '2025-11-12'
author: Marko Bekhta
feed_url: https://beanvalidation.org/news/news.atom
---
Recently, we published the first milestone release of the upcoming  Jakarta Validation 4.0.
Jakarta Validation 4.0 will be a part of the Jakarta EE 12 platform, to be released later.




What has been done so far?


The 4.0 update of the specification, compared to 3.1, brings the following changes:




Easier Custom Constraint Validator Integration:
developers of custom constraints can now declare their ConstraintValidator implementations using the Java Service Loader mechanism.
This decouples the constraint definition and the constraint validator implementation details.
It especially simplifies the process for external libraries to add support for more types to constraints
existing in other libraries, including the default, Jakarta Validation ones.


Optional...
