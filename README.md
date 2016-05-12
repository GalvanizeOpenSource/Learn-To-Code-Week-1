# Learn to Code HTML & CSS
Brought to you by Galvanize. Learn more about the way we teach code at (galvanize.com)[galvanize.com].

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

#### What web coding is (really)?
Recipes to give to your computer to “cook” up some awesome things for you online

## Setting up your computer
(Brace yourself...)

#### Please set up the following:
* A web browser to see what we're working on as others see it (Recommend Google Chrome: [chrome.google.com] (chrome.google.com))
* A text editor to modify your files (Recommend the Atom text editor: [Atom.io](atom.io))
* Download the tutorial files on this page within the zip file  

#### Download the files for this class:
1. Go to https://github.com/GalvanizeOpenSource/Learn-To-Code-HTML-CSS
2. Click on the button on the right-hand side that says "Download ZIP"
3. Go to your downloads folder and double click on the .zip file to unzip it
4. IMPORTANT! Leave all the individual files in the downloaded folder (if you would like to move it out of the downloads folder move the entire folder, not individual items)
5. From Atom: 
- File > open, select the folder and then click "Open"
- If the file tree does not appear on the left hand View > Toggle Tree View -- this will show you the entire folder within Atom
6. *Now if you already know some of what we're talking about,* you're all set to poke around in the files -- index.html and CSS/style.css are the two files we will using.

Patience! Setting up your computer takes time and can be tricky, especially across platforms.

Once you're ready, you can move onto the next lesson.

## H.T.M.L. - "the building blocks of the internet"

Hyper Text Markup Language, or HTML, is the most elemental language of the internet. Everything you see within your web browser is an interpretation of HTML in some form of other, and it is essential to learn in all web development.

###### The syntax of most HTML is as follows:
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

###### Common Tags:
- `<html></html>` designates document as HTML
- `<div></div>` notes a block element in the page
- `<a></a>` anchor, activates a link in the page
- `<head></head>` contains meta information
- `<body></body>` contains browser information
- `<span></span>` notes an inline element

###### Irregular Tags:
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
###### The most common attributes are:
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

#### Three primary objects:
- Elements: e.g. h1, div, body, a - default HTML (already reviewed)
- IDs: everything that starts with a “#”
- Classes: everything that starts with a “.”

#### Syntax of CSS:
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
HTML: 
<a id=”leesName”>Lee Ngo</a>

CSS: 
#leesName { 
	color: white; 
}
```
IDs are used to direct functions to unique elements in the HTML so that there’s no confusion

*e.g clicking to a specific part of page*

#### What are Classes?

Classes are attributes something to multiple elements on a page noted with a “.” symbol in CSS.
```
HTML: 
<a class=”ninja”>Lee Ngo</a>

CSS: 
.ninja { 
	color: black; margin: 10px; 
}
```
Classes are used to change or affect multiple items in an HTML document at once

*e.g. everything with class=”ninja” should have the same attributes*

In tandem, you can do a lot with HTML & CSS! Let's give it a shot!

## LET'S CODE!

###### Remember:
- Coding can be hard - be patient!
- Work in pairs! Even the pros do it
- Ask for help - we’re in a school!

#### Let's get started!
1. Open up your text editor
2. Navigate to your repo
3. Open up the following files
- index.html
- CSS/style.css

#### Let's change the font!
1. Navigate to Google Fonts: https://www.google.com/fonts
2. Find a font you like and click "Add to Collection".
3. On the bottom right side of your screen click "Use".
4. On the "Use" page, scroll down to "Number 3" and copy the link tag provided.
5. Paste that link tag in your index.html file with the new link tag you copied from Google Fonts.
6. Copy the CSS code under “Number Four.”
7. Paste that code into your CSS under the body tag.
8. Save and refresh!

Did it work! Great! If not open up **Inspect Element** and see what happened.

## Play around in the sandbox!

Try one of the following:
- Change the name of the site to...whatever!
- Change all the navigation links & section headers
- Replacing the images with your own images - locally, online, etc.
- Show what you did with the others! 

# YOU DID IT! YOU'RE NOW A CODER!

Welcome to the cool kids club.

<<<<<<< HEAD
##The User wants some changes
- Change the name of the site
- Change all the navigation links & Section Headers
- Replace my images with your own images
- Add a video to your page
- Push changes to github
=======
#### Want to code more? Check out Galvanize's Full Stack Immersive Program!
>>>>>>> 222d0db4c115293bf2ea9337213063f2486749d6

- 24 Week Full-Time Program
- 97% Job Placement Rate within six months
- Average starting salary: $77,000 per annum
- Scholarships available for those who qualify
- Learn more at http://galvanize.com/courses/fullstack/

#### Looking for something more flexible? Check out our Evening Workshops!

- Zero to Web Designer
- Foundations of JavaScript
- Learn more at http://www.galvanize.com/workshops/

#### About the Authors

[Graham McBain](http://linkedin.com/in/grahammcbain) is a graduate of the 3rd cohort of the Galvanzie Full Stack Program and now Evangelist for Galvanize based in the Colorado area. Graham believes that programming is more accessible than people think and is passionate about showing people the path to becoming a developer.

[Lee Ngo](http://linkedin.com/in/leengo) is an evangelist for Galvanize based in Seattle. Previously he worked for UP Global (now Techstars) and founded his own ed-tech company in Pittsburgh, PA. Lee believes in learning by doing, engaging and sharing, and he teaches code through a combination of visual communication, teamwork, and project-oriented learning.

You can email him at lee.ngo@galvanize.com for any further questions.
