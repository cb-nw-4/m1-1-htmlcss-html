# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [false] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

A screen reader is a form of assistive technology (AT)[1] that renders text and image content as speech or braille output. Screen readers are essential to people who are blind,[2] and are useful to people who are visually impaired,[2] illiterate, or have a learning disability.[3]
https://en.wikipedia.org/wiki/Screen_reader

The Accessible Canada Act (Bill C-81)
https://siteimprove.com/en-ca/blog/a-complete-overview-of-canada-s-accessibility-laws/#:~:text=The%20Accessible%20Canada%20Act%20(Bill%20C%2D81)&text=One%20of%20the%20purposes%20of,accessibility%2C%20will%20likely%20follow%20WCAG. 

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation 

<img>

b) You want to create a website that lists all the art gallery websites in your city and links to their website. 

<ul> , <li> , <a>

c) You want to sell designer hats. You need to receive orders from the user. 

<form>
<label>
<input>
These tags to get information from the user such as name, last name, credit card info and etc. 

<button> 
For the user to submit an order. 

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning  

https://html.spec.whatwg.org/multipage/form-elements.html#the-button-element 
4.10.6 The button element 
Content model:
Phrasing content, but there must be no interactive content descendant and no descendant with the tabindex attribute specified.

The content model of the button tag says there should not be interactive content as the child of a button. Button is an interactive content itself thus this means that a button cannot be a child of a button. 

The button element represents a button labeled by its contents. 
A button as the child of a button would mean a button to be used as the label of another button. As such: 
<button>Parent button
<button>Child button</button> 
</button>

Having a button as a label of a button logically does not make sense as that is not the functionality of a button. 

## Q5 - What is the most generic tag you can use?

Probably p paragraph tag. 
<p>

## Q6 - What do the following achronyms stand for?

a) `a` : anchor 

b) `ol`: ordered list 

c) `ul` : unordered list 

d) `li`:list 

e) `tr`: table row 

f) `th`: table header 

g) `td`: table data 

## Q7 - Usually, `td` elements are children of what kind of elements? 
<table> and <tr>

## Q8 - What is the difference between td and th? 

td is the data cells in the table. 
th is the header of of the table. 
th will be the first row usually in the tables and is the description of the data that will come below them. It is not exactly a data but a description of the data that comes under it. 
So, if the data in the table is numeric for example the th will not be numeric but will just be a name. 

## Q9 - Which tag makes the text appear bigger: h1 or h3? 

h1. 
It has hiearchical priority. 

## Q10 - In which situation can you use self closing tags? 
https://dev.w3.org/html5/html-author/ 
A Self-closing tag is a special form of start tag with a slash immediately before the closing right angle bracket. These indicate that the element is to be closed immediately, and has no content. 

When the element has no content, we can use self-closing tag. 

## Q11 - What is autofilling and why is it important?

The HTML autocomplete attribute is available on <input> elements that take a text or numeric value as input, <textarea> elements, <select> elements, and <form> elements. autocomplete lets web developers specify what if any permission the user agent has to provide automated assistance in filling out form field values, as well as guidance to the browser as to the type of information expected in the field.
https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/autocomplete

## Q12 - Which attributes are always present in an img element? 

https://www.w3schools.com/tags/tag_img.asp 
The <img> tag has two required attributes:
src - Specifies the path to the image
alt - Specifies an alternate text for the image, if the image for some reason cannot be displayed

## Q13 - Which attribute is always present for an anchor tag? 
https://www.w3schools.com/tags/tag_a.asp
The most important attribute of the <a> element is the href attribute, which indicates the link's destination.
