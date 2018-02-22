# About this repository

# Best practices
_Bron https://www.catswhocode.com/blog/top-10-best-practices-for-front-end-web-developers_

## use a css reset

Unless you’re a beginner or if you were on vacation on a desert island for the last 6 years, you might already know how useful a CSS reset it. Because by default, browsers don’t apply the same default styling to HTML elements, a CSS reset will ensure that all element have no particular style so you can define your own without the risk of many cross-browser rendering issues.

``` html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, font, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td {
	margin: 0;
	padding: 0;
	border: 0;
	outline: 0;
	font-size: 100%;
	vertical-align: baseline;
	background: transparent;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}

/* remember to define focus styles! */
:focus {
	outline: 0;
}

/* remember to highlight inserts somehow! */
ins {
	text-decoration: none;
}
del {
	text-decoration: line-through;
}

/* tables still need 'cellspacing="0"' in the markup */
table {
	border-collapse: collapse;
	border-spacing: 0;
}
```
## Don’t mix CSS with HTML

## Don’t mix Javascript with HTML

## Use conditional comments

```height: 200px; /* normal browsers */
_height: 300px; /* IE6 */
.height: 250px; /* IE7 */
*height: 350px; /* All IEs */
```

## Place Javascript file at the bottom 

# “Smush” your images



# Image Gallery

# Async API Data
