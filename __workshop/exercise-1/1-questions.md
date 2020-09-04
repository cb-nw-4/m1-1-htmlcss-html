# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [true] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [false] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

It's an assistive technology to help the visually imparaied and other disabled people (American Foundation for the Blind).

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<div> <img> closing each with </>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<div> <section> <ul> <li> <a href> closing each with </>

c) You want to sell designer hats. You need to receive orders from the user.
<div> <section> <ul> <li> <img> <form> <button>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No. You cannot nest a button inside of a button. I believe it's wrong pratice.

## Q5 - What is the most generic tag you can use?
<div>

## Q6 - What do the following achronyms stand for?

a) `a` -> anchor

b) `ol`-> ordered list 

c) `ul` -> unordered list

d) `li` -> list item

e) `tr` -> table row

f) `th` -> table header

g) `td` -> table data

## Q7 - Usually, `td` elements are children of what kind of elements?
<tr> & <table>

## Q8 - What is the difference between td and th?
Although the <th> is also a <td> (table data) it is also centered and bolded by default since it's the header. 
<td> are regular and and left-aligned by default.

## Q9 - Which tag makes the text appear bigger: h1 or h3?
H1 should be bigger by default but can definitely be changed using CSS

## Q10 - In which situation can you use self closing tags?
When the tag itself have no content. Eg: <br> or <input>

## Q11 - What is autofilling and why is it important?
It's an attribute that's available on input elements that basically takes either words or numbers and it lets the user's computer/phone provide automated assistance in filling out the form. 

## Q12 - Which attributes are always present in an img element?
<src> which contains the paths and <alt> an alternate text if the image cannot be displayed

## Q13 - Which attribute is always present for an anchor tag?
<href> which is the link destination