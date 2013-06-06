totem
=====

sass structure for site building



includes normalize 

includes sticky footer for structure like:

html
	body
		.top
			.main
		.bottom
			.footer
/html

also includes bourbon mixin library which works when running through codekit, but might need a more explicit import in the style.scss file.

There are some starter variables and mixins as well.

The idea behind the library is to pull in from different places.  Style.scss imports each file that has the same name as its parent folder which imports sibling files (ie. _globals-header).  There are flags at the top of each file.  Files that do importing have a larger flag to deliniate a new section/folder.  Smaller flags is the actual name of the file.  This makes using the browser to code more simply.  Inspecting the sheet in the browser gives the user a good hint as to where styles are in the sass folder structure.


Ask any questions.  Feel free to use it, I know I will be.

-ian phipps