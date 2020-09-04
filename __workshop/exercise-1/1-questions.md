# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false ] `<div><span>hello</div></span>`

b) [ false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ true ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

A screen reader is a type of assistive technology that renders web content in alternate forms, including speech output. This is an accessibility tool that enables people with impaired vision, blindness, and certain learning disabilities to absorb online content.

(Source: https://en.wikipedia.org/wiki/Screen_reader)

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
`img`

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
`ul` OR `ol`
`li`
`a`

c) You want to sell designer hats. You need to receive orders from the user.
`form`
`input`

And maybe some combination of `textarea`, `label`, and `button` to improve design and user experience. 

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

No, because you cannot nest interactive content descendant from a `button` tag.

## Q5 - What is the most generic tag you can use?

`div`. It's generic in the sense that it's not semantic, and because it can be used to group any content together. 

## Q6 - What do the following achronyms stand for?

a) `a`
Anchor

b) `ol`
Ordered list

c) `ul`
Unordered list

d) `li`
List item

e) `tr`
Table row

f) `th`
Table header

g) `td`
Table data (or data cell)

## Q7 - Usually, `td` elements are children of what kind of elements?
`table` –> your table structure
`tr` –> your table row

## Q8 - What is the difference between td and th?
`th` indicates a header, while `td` is used for table data cells. Because they are distinct, this allows users the ability to edit each one individually – ie. displaying the header text in a larger, coloured font.

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1

## Q10 - In which situation can you use self closing tags?
Self-closing tags represent void elements. In other words, they do not contain any content. ie. `img`

## Q11 - What is autofilling and why is it important?
The autocomplete attribute is available on `input` elements that take a text or numeric input. It indicates whether input elements can by default have their values automatically completed by the browser. It is useful because it can provide guidance to the browser about the type of information that's expected, and the browser may allow a user to save specific data (ie. their name, address, etc) for autocomplete purposes. 

## Q12 - Which attributes are always present in an img element?
The src attribute is required. The alt attribute is not technically mandatory, but it is highly recommended for use with any `img` element.

## Q13 - Which attribute is always present for an anchor tag?
The href attribute.