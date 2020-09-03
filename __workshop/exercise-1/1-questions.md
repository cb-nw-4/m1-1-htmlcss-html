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

A screenreader is a device used by those who are blind or have visual impairments to use the internet and a computer. It's important for a website to be designed such that the screenreader can read out the contents to its user. A website not designed for that not only violates Canadian law, but also makes the website and its content inaccessible to people who are blind or have visual impairments.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<h1> My Latest Vacation </h1>
<img src="image link" alt="image description">
<figcaption>Image Description</figcaption>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<h1>Art Galleries in Montreal</h1>
<ul>
    <li><a href = "art gallery website 1"> Art Gallery 1 Name</a></li>
</ul>

c) You want to sell designer hats. You need to receive orders from the user.
<h1>Designer Hat Website</h1>
<img src="designer hat 1" alt="designer hat 1">
<button type="button">Add to Cart</button>

/* Order Form */
<form action="www.designerhat.com/thanks-for-order" method="post">
    <label for="name">Customer Name:</label>
    <input type="text" id="name" name="Customer Name">
    <label for="mail">Customer Email:</label>
    <input type="text" id="email" name="Customer Email">
    <label for="address">Customer Address:</label>
    <input type="text" id="address" name="Customer Address">
    <label for="creditCard">Credit Card Information:</label>
    <input type="number" id="creditCard" name="Credit Card Information">
    <button type="submit">Submit Order</button>
</form>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
Since <button> is an inline element, it cannot be a parent. This is because the code is contained within the <button> line and don't break or interfere with the flow of the rest of the elements. 

## Q5 - What is the most generic tag you can use?
<div> because it defines just a section of the HTML document.

## Q6 - What do the following achronyms stand for?

a) `a` is an anchor element, used for creating hyperlinks to other websites

b) `ol` is an ordered list, which creates a numbered list

c) `ul` is an unordered list, which creates a bullet point list

d) `li` is a list item and defines each item contained in an ordered or unordered list

e) `tr` is a row in an HTML table

f) `th` is a header in an HTML table

g) `td` is a standard cell element specified within a <tr> in an HTML table (not a header or footer of the table but just a regular cell)

## Q7 - Usually, `td` elements are children of what kind of elements?
'td' elements are usually the children of <tr> elements

## Q8 - What is the difference between td and th?
'td' element is a standard cell, so just the regular contents of a cell in a table while 'th' specifies the header of the table

## Q9 - Which tag makes the text appear bigger: h1 or h3?

## Q10 - In which situation can you use self closing tags?

## Q11 - What is autofilling and why is it important?

## Q12 - Which attributes are always present in an img element?

## Q13 - Which attribute is always present for an anchor tag?
