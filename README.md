## sup_emacs_tmTheme
=================

A colorful TextMate theme base on Emacs with jade, coffee, python support.

### Usage
======

1. Finder go folder '~/Library/Application Support/TextMate/Managed/Bundles'
2. Right click Themes.tmbundle, select 'Show package contents'
3. Copy supEmacs.tmTheme intro 'Themes' folder.
4. Make sure the file type is .tmTheme just like anyone else in this folder.
5. Select supEmacs theme from the theme list

If you don't have Themes.tmbundle, you have to find it first, or you can made by your self.

There is not easy way to install it yet. Maybe next year when I got free.

#####  Jinja2 template support bundle
===============
orginal is from https://github.com/ozan/textmate-jinja-templates

sup-jinja-templates.tmbundle is made modifed.

the different is I remove the 'No automatic complate {' from Marcos.
It's sucks, eat the next line space while you type { begging of the line.


#### /.tm_properties
=========================

softWrap = true
tabSize = 2
softTabs = true

[ *.py ]
tabSize = 4
wrapColumn = 79

[ *.html ]
tabSize = 4
softWrap = false