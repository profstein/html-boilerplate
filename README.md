# html-boilerplate
A boilerplate template that draws from existing templates with modifications to fit an educational, learning environment.

This template owes a debt to work done by:

- HTML5 Boilerplate: https://html5boilerplate.com/
- Sitepoint's _HTML5 Template: A Basic Boilerplate for Any Project_ https://www.sitepoint.com/a-basic-html5-template/


## Breakdown of what is included

### HTML
The standard HTML5 doctype and HTML elements are included. The language has been specified as English (lang="en") as I use this in an English-speaking classroom. Please update as needed.

### Head: Standard elements
The __title__ element and the __link__ to a CSS file are standard. You are able to change the folder and file name for the CSS file, add additional link elements to additional CSS files or not included it if you're not using CSS (not recommended).

### Head: META elements
A number of meta tags are included.

#### These you can use unchanged
- __charset="utf-8"__. This works for the alphabets needed to display most languages.
- __name="viewport"__ This is needed for responsive design to work properly

#### These you should change the values

__name="description"__: add text inside the quotes for __content__ to a description of your site (this is optional)

__name="author"__: add text inside the quotes for __content__ to the author of the site. (this is optional)

__Meta | Property Elements__
These are used by social media when people post a link to your site. What is added in these elements is what will be seen in the social media post in addition to your site's URL.

Change only the values inside of the __content__ attributes. For example you would change 
```
<meta property="og:title" content="">
```
to
```
<meta property="og:title" content="The title for your site">
```

#### These were not included

- __property="og:image"__: this would be added after the other meta|property elements and lets you control the preview image shown on social media 
- __Favicon link elements__: You can add these if you want to set a favicon for the page.


### BODY
A standard HTML page setup is included. This is something that is not required and assumes the following page structure

1. HEADER: that includes site title and navigation. Usually this is the same on every page.
2. MAIN: where the main content of the page will be. Usually this changes from page to page
3. FOOTER: the site footer. The content here varies but often includes copyright info, help/contact and other similar information and possibly a version of the main site navigation. Usually this is the same on every page of the site.

#### BODY: JavaScript
For this template there is no link to a JavaScript file(s). Typically links to external scripts usually go right before the closing /body tag.