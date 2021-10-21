Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content modifications copyright Diego Becerra (C) 2021 under CC BY-SA 4.0.

This repo was forked from https://github.com/abramhindle/CMPUT404-assignment-css-hell.git licensed by Abram Hindle.

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

Steps to Modify Gutenberg Files
=================
1. Created a CSS file `styles.css` and placed it in `gutenberg/`
2. Added the line `<link rel="stylesheet" href="styles.css">` at the end of the `<head>` section in each of the gutenberg HTML files. This needed to go after the other CSS styling so that it would override the existing styles applied by gutenberg.
3. Modified the CSS file and created rules for different elements in the gutenberg HTML files. Created style rules for basic HTML elemenets such as `<body>`, `<h1>`, `<h2>`, `<p>`, `<img>` and `<figcaption>`. I also created style rules for classes which were already present in the gutenberg webpages. For some of the gutenberg webpages, the existing CSS styles used selectors that were more specific than what was present in my custom CSS file, so my new files were not overriding the old styles. For these cases, I had to create more specific CSS rules by combining HTML tag and a CSS class in a single rule (e.g. div.c2).