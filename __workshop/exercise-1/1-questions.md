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

ANSWER: A screen reader allows a person with severe visual impairments to use a computer by relaying the information through speech or braille.

source; "https://www.nomensa.com/blog/2005/what-screen-reader"

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation 

<img> - <ol>, </ol> OR <ul>, </ul> - <li>, </li>

b) You want to create a website that lists all the art gallery websites in your city and links to their website. 

<ol>, </ol> OR <ul>, </ul> - <li>, </li> - <a href="url">, </a>

c) You want to sell designer hats. You need to receive orders from the user.

<form>, </form> - <input type="checkbox">

## Q4 - Can a `button` be a child of a `button`? Explain your reasonin

No, because there must be no interactive content descendant.

## Q5 - What is the most generic tag you can use?

 <h#>

## Q6 - What do the following achronyms stand for?

a) `a` a hyperlink

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr` a row in an HTML table

f) `th` a header cell in an HTML table

g) `td` a standard data cell in an HTML table

## Q7 - Usually, `td` elements are children of what kind of elements? 

<tr>, </tr> OR <table>, </table>

## Q8 - What is the difference between td and th? 

The text in <td> elements are regular and left-aligned by default, as for <th>, they are bold and centered by default.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

 h1

## Q10 - In which situation can you use self closing tags?

Only when the element is defined as empty.

## Q11 - What is autofilling and why is it important?

If enable, it allows the browser to predict the value of the user's input. It helps the user to understand what kind of input the browser wants.

## Q12 - Which attributes are always present in an img element?

"src=" and "alt"

## Q13 - Which attribute is always present for an anchor tag?

"href="
