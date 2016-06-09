# BOOLAZY: Booleans, for lazy people

Let's say you work in fifteen different languages daily.

Python:

	lazy  = True
 	happy = False

Javascript:

	var lazy  = true;
	var happy = false;

C:

	boolean lazy  = true;
	boolean happy = false;

Objective-C:

	BOOL lazy  = YES;
	BOOL happy = NO;

PHP:
	lazy  = TRUE;
	happy = FALSE;

_(Etcetera)_

Wouldn't it be nice if you could just.. forget about the different keywords and choose just one? This Python library aims to cover all possible boolean keywords from any language, inside the Python runtime.

Install:

    $ pip install boolazy

And then just:

	from boolazy import *

	if true == True == YES == yes:
		print 'Hooray!'


Go forth and be lazy, you lazy asshole.

## More Truth?!

Do you have more boolean syntax from another language you'd like to port over? Open a pull request!
