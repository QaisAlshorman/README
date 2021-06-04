## [What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

CSS (Cascading Style Sheets) allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.

## What is CSS for?
 CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.

A document is usually a text file structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML.

Presenting a document to a user means converting it into a form usable by your audience. Browsers, like Firefox, Chrome, or Edge , are designed to present documents visually, for example, on a computer screen, projector or printer.

## CSS syntax
CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page. For example "I want the main heading on my page to be shown as large red text."
The rule opens with a selector . This selects the HTML element that we are going to style. In this case we are styling level one headings (<h1>).

We then have a set of curly braces { }. Inside those will be one or more declarations, which take the form of property and value pairs. Each pair specifies a property of the element(s) we are selecting, then a value that we'd like to give the property.

Before the colon, we have the property, and after the colon, the value. CSS properties have different allowable values, depending on which property is being specified. In our example, we have the color property, which can take various color values. We also have the font-size property. This property can take various size units as a value.

A CSS stylesheet will contain many such rules, written one after the other.
## CSS Modules
As there are so many things that you could style using CSS, the language is broken down into modules. You'll see reference to these modules as you explore MDN and many of the documentation pages are organized around a particular module. For example, you could take a look at the MDN reference to the Backgrounds and Borders module to find out what its purpose is, and what different properties and other features it contains. You will also find links to the CSS Specification that defines the technology (see below).

At this stage you don't need to worry too much about how CSS is structured, however it can make it easier to find information if, for example, you are aware that a certain property is likely to be found among other similar things and are therefore probably in the same specification. 

For a specific example, let's go back to the Backgrounds and Borders module — you might think that it makes logical sense for the background-color and border-color properties to be defined in this module. And you'd be right.
## [How To Add CSS](https://www.w3schools.com/css/css_howto.asp)
### Three Ways to Insert CSS
There are three ways of inserting a style sheet:

1. External CSS
2. Internal CSS
3.Inline CSS
## [CSS color Property](https://www.w3schools.com/cssref/pr_text_color.asp)
## Definition and Usage

The color property specifies the color of text.

Tip: Use a background color combined with a text color that makes the text easy to read.