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

c) [true] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_
A Screen reader is software that allows blind or visually impaired people to read text in a computer, in a web page or a web application. It can read the text on a screen with a computerize voice. Most screen reader can also convert a text in braille. 
Source: https://cnib.ca/en/sight-loss-info/living-with-blindness/technology/screen-readers?region=qc

Only in Canada, 1.5 million Canadians say they are blind or partially sighted. 
source: https://cnib.ca/en/sight-loss-info/blindness/blindness-canada?region=qc
This is why it is important that we adapt our web page so they can be easily readable for a screen reader, for example by using semantic tag and write good html.
Our web application or web page also needs to fits the requirement of the The Accessible Canada Act.


## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
You will use <figure> tag. In the figure tag you will use <img> and <figcaption>.

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
Main answer: to make the hyperlink use <a>
You can also use <ul><li> to list all the link to the gallery.

c) You want to sell designer hats. You need to receive orders from the user.
Main answer: <form> 
In the form tag you use others tags like <label>, <input>.
You will probably have to add a <button> tag as well. 

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
It is not valid to put a button tag inside a button tag. You can add phrasing content inside a button tag but not an interactive content and a button is an interactive content. So a button can't be a child of a button. And having a button inside a button would be a little weird :-). 

## Q5 - What is the most generic tag you can use?
<div>

## Q6 - What do the following achronyms stand for?

a) `a` HTML element that creates a hyperlink to a web page, file or email. It is used with the href attribute.

b) `ol` HTML element that created an ordered list of item. Each item are preceded by a number.

c) `ul` HTML element that created an unordered list of item, a bulleted list. 

d) `li` HTML element that represented an item in a list. Each element of the list must be inside an li tag. We must use li tag inside a ul or ol tag.

e) `tr` The tr HTML element is a row of cell in a table. We then use th and td inside tr tag to define the cell in that row.

f) `th` The th HTML element defines a cell as a header in a table

g) `td` The td HTML element is a cell in a table that contain data

## Q7 - Usually, `td` elements are children of what kind of elements?
A td elements are children of a tr element. Then a tr element is usually a child of a table element or  thead, tbody or tfoot.

## Q8 - What is the difference between td and th?
The td element is a cell in a table that contain data and a th element is a header cell in a table.

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1

## Q10 - In which situation can you use self closing tags?
A self closing tag are HTML element that doesn't have a closing tag, they are called void-element. For exemple the <img> tag is a self closing tag. We only put the image in there and nothing else, the image have no other content then itself. There is many self closing tag, like <link>, <input> ...

## Q11 - What is autofilling and why is it important?
There is an autocompleted attribute that we can use in input, select, textarea and form element. It can facilitate the life of the user by giving assistance in filling a form. It can for exemple gives the previous value a user put in the form, or some pre-configure value like usual name and addresse, so he doesnt need to type it all over again. 

## Q12 - Which attributes are always present in an img element?
alt and src

## Q13 - Which attribute is always present for an anchor tag?
 href attribute
