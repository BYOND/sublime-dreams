sublime-dreams
==============

A Sublime Text 2 Theme/Build System for Dream Maker (http://byond.com)


Highlighting
============
Currently correctly highlighting:
* All language keywords
* Pre-processor macros
* Strings (single and double quote)
* Proc names
* Numeric variables
* Built-in functions
* Language constants
* Embedded expressions

Build System
============
There is currently no build system in place.

Snippet Autocompletion
======================

Currently supported are:

def\<tab> 
expands to:

```
#ifndef SYMBOL
#define SYMBOL value
#endif
```

do\<tab>
expands to:
```
do

	/* code */
while (/* condition */);
```

for\<tab>
expands to:
```
for (var i = 0; i < count; ++i)
	/* code */
```

forin\<tab>
expands to:
```
for (var i in 1 to count)
	/* code */
```

forinstep\<tab>
expands to:
```
for (var i in 1 to count step 2)
	/* code */
```