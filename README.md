Django Testapp
==============

I forked this repository because I wanted a ready-to-use 
new project template of a Django Appengine project.

Unfortunately, I noticed that this project is not
ready-to-use and probably never will be, because
the directory structure of the django-nonrel and 
django-dbindexer projects don't allow me to clone
the right stuff into the right place. Too bad.

If you want to use this template, you may do so but
you have to fix the `django` and the `dbindexer`
subdirectories such that the `django` directory
inside the `django` directory becomes the new
`django` directory. Got it?  
In other words the files in `django/django` and
`dbindexer/dbindexer` have to be moved one level
upwards.

That surely breaks the update mechanism of the 
subrepositories but to be honest, I didn't have
a clue that this wouldn't work.

Anyway, have fun  
hflicka@GitHub