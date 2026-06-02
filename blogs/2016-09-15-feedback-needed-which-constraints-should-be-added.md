---
title: Feedback needed - Which constraints should be added?
url: http://beanvalidation.org/news/2016/09/15/which-constraints-to-add/
date: '2016-09-15'
author: Gunnar Morling
feed_url: https://beanvalidation.org/news/news.atom
---
The work on Bean Validation 2.0 is in full swing and there is an issue where we could benefit from your help.

Recently we have been discussing whether any new constraints should be added to the specification or not.
Traditionally, Bean Validation stayed on the conservative side of things in this regard.
It defined only some generically applicable and widely useful constraints in the specification itself, e.g. @NotNull, @Size or @Pattern.

Now Marco Molteni did a very interesting analysis on the constraints which are actually used in real world projects by running an analysis of open source projects hosted on GitHub.
Only a specific type...
