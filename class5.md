# What I Learned in My Readings

## Class Five Notes

### Cascading Style Sheets (CSS)

* Allows you to make your web pages much nicer.
* It is a language for specifying how documents are presented to users - how they are styled, laid out, etc.
* A document is usually a text file structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML.
* CSS is a rule-based languag.
* h1 is a selector. It selects the HTML element that we are going to style. In this case it is the h1.
* Inside the curly braces will be one or more declarations, which take the form of property and value pairs.
* You specify the property before the colon, and the value of the property after the colon.
* This includes two declarations, one for color and the other for font-size.
* All web standards technologies (HTML, CSS, JavaScript, etc.) are defined in giant documents called specifications (or "specs"), which are published by standards organizations (such as the W3C, WHATWG, ECMA, or Khronos) and define precisely how those technologies are supposed to behave.
* CSS - developed by a group within the W3C called the CSS Working Group.
* CSS is constantly developing, with new features becoming available. 
* It is unusual for all browsers to implement a feature at the same time, and so there is usually a gap where you can use some part of CSS in some browsers and not in others.
* The browser support status is shown on every MDN CSS property page in a table named "Browser compatibility". 

### How to Add CSS

* There are three ways of inserting a style sheet: External CSS, Internal CSS, and Inline CSS.
* With an ***external style sheet***, you can change the look of an entire website by changing just one file!
* Each HTML page must include a reference to the external style sheet file inside the link element, inside the head section.
* An external style sheet can be written in any text editor, and must be saved with a .css extension.
* The external .css file should not contain any HTML tags.
* An ***internal style sheet*** may be used if one single HTML page has a unique style.
* The internal style is defined inside the style element, inside the head section.
* An ***inline style*** may be used to apply a unique style for a single element.
* To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property. 
* All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority: Inline style (inside an HTML element), External and internal style sheets (in the head section)
* So, an inline style has the highest priority, and will override external and internal styles and browser defaults.

### CSS Syntax

* color is the color of the text
* HEX value starts with number sign
* RGB has three values
* RGBA value has 4 values.