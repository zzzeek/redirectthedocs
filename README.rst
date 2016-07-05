=================
Redirect The Docs
=================

A Sphinx project that builds a simple redirect to the
"canonical url" on `readthedocs <https://readthedocs.org>`_.

Since readthedocs has no ability to redirect to a new server, 
there's no way for any established project that used the
readthedocs.io domain to ever move anywhere else without 
frustrated users.   

Therefore, this project fixes that!  Simply go to whatever
readthedocs project you have which you'd like to redirect,
point it at this github repo (or a fork you make yourself
in case you're worried I'm going to change something! >:) )
then enter the desired base redirect into the "Domains" 
page, click the "canonical" checkbox and save.  Then build!
You're welcome.

What works
==========

When people hit the root of your docs, it will redirect 
to the canonical URL.

What doesn't Work Yet
=====================

RTD doesn't yet allow us to set up a 404 page, but when they
do, we can then work on getting all the other pages to redirect
cleanly to the target URL.


