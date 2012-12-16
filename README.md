This is an evaluation repository about internationalisation (i18n) in javascript. 
It should show a example how you translate strings in diffrent javascript i18n frameworks.

This is done to help to make an dession which framework the Openstreemap Editor id should use. 

See:

https://github.com/systemed/iD/issues/17

# Wishlist for i18n

* open source, free license
* the framwork should support any language (utf8)
* should support singular, plural
* should support something like placeholdes: "Your way is %d nodes long"
* should be easy to translated by the crowed (translatewiki)
* loading languages on demand
* get default language from browser
* switch language without restart

# How to write code
There are different aproches for writing code with i18n stacks (Example code showDialog("Server "+hostname+" is not reachable.") ):
1. showDialog(l("Server %s is not reachable.",hostname))
2. showDialog(l("%error.server-failed"))


I prefer the 1. solution.

# Solutions I found:
* Dojo: http://dojotoolkit.org/reference-guide/1.8/dojo/i18n.html
* i18next.js http://i18next.com/
* jsperanto.js https://github.com/jpjoyal/jsperanto
* jed.js http://slexaxton.github.com/Jed/
* messageformat.js https://github.com/SlexAxton/messageformat.js
* jquery.i18n plugin http://recursive-design.com/projects/jquery-i18n/
 * wikimedia fork https://github.com/wikimedia/jquery.i18n
* l10n.js http://eligrey.com/blog/post/passive-localization-in-javascript

