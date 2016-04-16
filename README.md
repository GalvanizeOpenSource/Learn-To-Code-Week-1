# Learn to Code HTML & CSS
Brought to you by Galvanize. Learn more about the way we teach code at <a href=//galvanize.com>galvanize.com</a>.

## Overview
The goal of this brief course is to provide you with a fun introduction to the world of web development, starting with HTML and CSS. 

#### Here's what we'll be doing:
* Setting up our computers for web development
* Overview of basic HTML concepts
* Overview of CSS concepts
* Playing around in the sandbox

#### Before you begin, a quick gut check:
* This course is for absolute beginners
* Feel free to move ahead
* Help others when you can
* Be patient and nice
* You will get through it!

### What web coding is (really)?
Recipes to give to your computer to “cook” up some awesome things for you online

## Setting up your computer
(Brace yourself...)

Please set up the following:
* A web browser to see what we're working on as others see it (Recommend Google Chrome: [chrome.google.com] (chrome.google.com))
* A text editor to modify your files (Recommend the Atom text editor: [atom.io](Atom.io))
* Download the tutorial files on this page within the zip file  

###### Download the files for this class:
1. Go to https://github.com/GalvanizeOpenSource/Learn-To-Code-HTML-CSS
2. Click on the button on the right-hand side that says "Download ZIP"
3. Go to your downloads folder and double click on the .zip file to unzip it
4. IMPORTANT! Leave all the individual files in the downloaded folder (if you would like to move it out of the downloads folder move the entire folder, not individual items)
5. From Atom: file > open, select the folder and then click "Open"
6. From Atom: if the file tree does not appear on the left hand View > Toggle Tree View -- this will show you the entire folder within Atom
7. *Now if you already know some of what we're talking about,* you're all set to poke around in the files -- index.html and CSS/style.css are the two files we will using.

Patience! Setting up your computer takes time and can be tricky, especially across platforms.

Once you're ready, you can move onto the next lesson.

## H.T.M.L. - "the building blocks of the internet"

Hyper Text Markup Language, or HTML, is the most elemental language of the internet. Everything you see within your web browser is an interpretation of HTML in some form of other, and it is essential to learn in all web development.

The syntax of most HTML is as follows:
* `<Tags>` - code that wraps around the content of HTML to designate a particular effect, sometimes inherent to the tag.
* `Attributes=""` - code inserted into tags to implement a particular effect that is external to the tag.
* Elements - the combined syntax of tags, attributes, and elements.

```
e.g. Element = <tag attribute=”blahblah”>content content</tag>
```

#### HTML Tags:
Tags are used to mark up the beginning and end of an HTML element.

Almost everything in HTML needs to start and end with a tag
Everything is wrapped like layers of an onion, `<opened>` and `</closed>`
- e.g. `<div>”Hello!”</div>`
- *Note: not every tag is like this!*

Common Tags:
- `<html></html>` designates document as HTML
- `<div></div>` notes a block element in the page
- `<a></a>` anchor, activates a link in the page
- `<head></head>` contains meta information
- `<body></body>` contains browser information
- `<span></span>` notes an inline element

Irregular Tags:
- `<img />` creates an image in the page
- `<br />` creates a big break in the page
- `<hr />` creates a horizontal line
- `<link />` connects this to related documents
- `<input />` creates an input field

#### HTML Attributes:
HTML attributes inform the browser on what to do with a tagged piece of content.
Attributes generally appear as name-value pairs. 
```
<p class="foo">This is the content of an element with class 'foo'.</p>
```
The most common attributes are:
- id="" - id is used on only a single element"
- class="" - class can be used on multiple elements"
- href=”” - hyperlink reference to an internal or external link
- src=”” - source file to an image, video, etc.
- style=”” - add some color, font, margins, etc.
- ^ *There’s a MUCH better way to do this via CSS - more on that later!*

How do we check elements for whether they're talking to the browser? Use the **inspect element** feature!

But... how do we make HTML... better?

## Overview of CSS

What Does CSS Stand for?
- Cascading - prioritizing certain values over others
- Style - focusing on layout, colors, fonts, etc.
- Sheet - another name for the file we use here

The internet used to be ugly. Enter CSS - a consolidated way to make it prettier.

Three primary objects:
- Elements: e.g. h1, div, body, a - default HTML (already reviewed)
- IDs: everything that starts with a “#”
- Classes: everything that starts with a “.”

Syntax of CSS:
```
h1 {  // this is either an element, class, or ID
	font-size: 24px; // syntax is name: value;
	font-weight: bold;
	color: #000000; // hexadecimal, RGB, etc.
}
```
Space doesn’t matter, but “onion” rules apply

#### What are IDs?
IDs are attributes that are used only on one element ONLY and noted with a “#” symbol in CSS
e.g.
```
HTML: <a id=”leesName”>Lee Ngo</a>
CSS: #leesName { color: white; }
```
IDs are used to direct functions to unique elements in the HTML so that there’s no confusion

ex: clicking to a specific part of page


#### Ids vs Classes
Classes are used when you need to style multiple elements in a document, while
id's are used to style specific elements on a page.

####Syntax
Lets look at how to style an element!

```html
<p class="coolThings">Cool Things</p>
```
Now lets look at the css!
```css
.coolThings {
  font-size: 24px;
}
```


##Change the Font to something from Google Fonts
- Navigate to google fonts: https://www.google.com/fonts
- Find a font you like and click "add to collection".
- On the bottom right side of your screen click "use".
- On the use page, scroll down to number three and copy the link tag provided.
- Paste that link tag in your index.html file with the new link tag you copied from google fonts.
- Copy the code under number four.
- Paste that code into your stylesheet!

##The User wants some changes
- Change the name of the site
- Change all the navigation links & Section Headers
- Replace my images with your own images

##Make some changes


#Question Time!
