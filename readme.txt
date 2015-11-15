ECS Library API Documentation
=============================

Credits
-------

Code highlighting was done by a JavaScript library called Highlight.js
	Copyright (c) 2006, Ivan Sagalaev
	See common/highlight.hs-LICENSE.txt

Header image and ECS logo:
	Copyright (c) University of Southampton

The font is Roboto, by Google
	Apache License, version 2 [http://www.apache.org/licenses/LICENSE-2.0.html]


Note on the Font
----------------

The font, Roboto is not included in this pack - the relavent CSS file
is hosted on fonts.googleapis.com. If you view the files offline, it will
default your browser's default sans-serif font.
	

File Structure
--------------

/
|- readme.txt				: This file
|- common/					: Folder containing CSS, JS & images for
|  |                          Part1 and 2 docs
|  |- ecs_logo.gif
|  |- header_bg.gif
|  |- style.css
|  |- highlight.pack.js
|  |- highlight.js-LICENSE.txt
|
|- Part1/					: Part1 folder, as asked for by the spec
|  |- book_creation.txt		: cURL Output - Evidence of book creation
|  |- docs/					: API Documentation
|     |- root.html			: Documentation for /
|     |- publishers.html	: Documentation for /publishers
|     |- publisher.html		: Documentation for /publishers/<id>
|     |- authors.html		: Documentation for /authors
|     |- author.html		: Documentation for /authors/<id>
|     |- books.html			: Documentation for /books
|     |- book.html			: Documentation for /books/<id>
|
|- Part2/					: Part2 folder, as asked for by the spec
   |- state_diagram.png
   |- docs/
      |- 