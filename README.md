# HTMLAndCSSFundamentals

Lexicon Assignment 5: Basic HTML Fundamentals and Introduction to CSS

## Basic HTML Fundamentals

Your assignment is to build two basic HTML structured pages.

First is Index page that will greet the visitors and present some articles and a bit of statistics on the side.
Second is a Login page that gives the user a form to fil in to sign in with (fake, no login service).

Only make the HTML elements and their contents, you are not allowed to use styling in this assignment (only exception is setting the size of images).
Refer to resources for information on how to implement the required features.

This assignment will work as base for the next assignment.

### Required Features for Index page:

* The page should be encoded using the UTF-8 character set.

* A page titledefined in the head element.

* Header element that is containing the following
    * Headline element of biggest size with the page name or a logo image.
    * Navigation element containing following
        * Unordered listelement with at least 3 list items.
        * One hyperlink element per list item.
    * Hyperlink element to the Login page.
  
* A container element for the main content of the page that is containing the following 
    * Headline element.
    * Paragraph with text.
    * Two article elements that is containing the following
        * One headline element.
        * Each should have text in at least 2 paragraphs.
        * One should have an image.

* Aside element that is containing the following
    * Headline element.
    * Unordered list of 3 list items, each that is containing the following
        * Headline with a nation name
        * Ordered list with 3 list items, each that is containing the following
            * Paragraph with name of city according to size.

* A footer element that is containing the following
    * Span element with html code for a copyright glyph and your name.
    
### Required Features for Login page:

* The page should be encoded using the UTF-8 character set.

* A page title defined in the head element.

* Header element that is containing the following 
    * Headline element of biggest size with the page name or alogo image.
    * Navigation element containing following
        * Unordered list element with at least 3 list items.
            * One hyperlink element per list item.
    * Hyperlink element to a page with a back to index page.

* A container element for the main content of the page that is containing the following
    * Headline element with text Login.
    * Form element.
        * Element appropriate fortyping in the username.
        * Element appropriate fortyping in the password.
        * Element appropriate for resetting the form.
        * Element appropriate for signing in with the formdata.

* A footer element that is containing the following
    * Span element with html code for a copyright glyph and your name.

## CSS Introduction

In this assignment, you will take a complete HTML page (the one you made in the HTML fundamentals assignment), and style it using CSS. You are to avoid modifying html elements of the page(s)as much as possible, apart from adding classes or ids to elements. 

### Required Features:

* All text on the pages should use a sans-serif font family.

* The pages should be 1024 pixels wide, and be centered on the page, with equal margins to the left and right.

* Give the Index page the following element positional appearance.
      * The boxes show where elements should be positioned, you do not need them to have the same color/border appearance on your page.

* Give the Login page the following element positional appearance.
      * The boxes show where elements should be positioned, you do not need them to have the same color/border appearance on your page.

* Make the text in the header on the login page show as upper-case letters.

* Use a border with rounded corners on the from.

* Give the reset & sign in elements on the form nicer shapes and colors that hint at their functionality.

#### Optional:
* The second paragraph of the first article element should be written in boldtext, with a blue text color.

* In the unordered list in the side content, items should appear in alternating colors (green and red, as a suggestion).

### Code Requirements:
* All the CSS code should come from the same file and be linked into the HTML files through a link tag – there should be no style tags or style attributes in the HTML file at all.
