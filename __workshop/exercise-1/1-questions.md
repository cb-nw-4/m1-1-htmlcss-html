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

A screenreader is a tool used to consult web pages for people with visual impairment. 

More precisely, the tool finds the html tags and attributes in a file and procuces an output that can be comprehended by the users.

We should be conscious about it while programming because a website needs to be reachable by the biggest audience possible. We are also required to have a design that doesn't discriminate any group.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<img src=".." alt=".."></img>
b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<ul></ul>
<li></li>
<a href=".."></a>
c) You want to sell designer hats. You need to receive orders from the user.
<form></form>
<input></input>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

Per developper.mozilla.org:

1) A button can have, as a parent, any element that accepts phrasing content, which includes button tags. So a button can have a button as a parent.
2) A button cannot contain interactive content, which a button is. So a button cannot have a button as a child element.
In the end, it seems that a button cannot be a child of another button.

## Q5 - What is the most generic tag you can use?
<div>

## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr` table row

f) `th` table header

g) `td` table data

## Q7 - Usually, `td` elements are children of what kind of elements?
<table>

## Q8 - What is the difference between td and th?
Their default style is different. Td elements are regular et left-aligned. Th elements are bold and centered.

## Q9 - Which tag makes the text appear bigger: h1 or h3?
<h1>

## Q10 - In which situation can you use self closing tags?
In my admission challenge I created a rectangular container without any text for my background picture. The style and background was set in the css file.

## Q11 - What is autofilling and why is it important?
It is a functionality that fills a form based on past inputs by the user. It is an important feature because it saves time (less errors and repetitions).

## Q12 - Which attributes are always present in an img element?
src
alt should be there for good practice

## Q13 - Which attribute is always present for an anchor tag?
href