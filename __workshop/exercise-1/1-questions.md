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

"A screen reader is a form of assistive technology (AT)[1] that renders text and image content as speech or braille output."
https://en.wikipedia.org/wiki/Screen_reader 

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
    img

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
    ul and a

c) You want to sell designer hats. You need to receive orders from the user.
    form

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
    No, the buttom is an interactive content which can not be parent of other elements like a, img...

## Q5 - What is the most generic tag you can use?
    <div>

## Q6 - What do the following achronyms stand for?

a) `a` Link to a page or a page portion

b) `ol` Ordered list (1.2.3.4...)

c) `ul` Unordered list (bullet points)

d) `li` Elements in a list

e) `tr` Rows in a table

f) `th` Table header cells

g) `td` Data cells

## Q7 - Usually, `td` elements are children of what kind of elements?
    <tr>

## Q8 - What is the difference between td and th?
    td is a data entry and th is the header of the type of data:
    Exemple in a table listing revenue per month we will have Month and Revenu in a th and the data per month in the td.

## Q9 - Which tag makes the text appear bigger: h1 or h3?
    h1

## Q10 - In which situation can you use self closing tags?
    area, base, br, embed, hr. iframe, img, input, link, meta, param, source, track.

## Q11 - What is autofilling and why is it important?
    Autofilling is he feature that helps the browser predict the input in a field. Example auto complete the address in an order form. This makes the user experience less tedious where he just needs to review the entry instead of typing the address.

## Q12 - Which attributes are always present in an img element?
    src to specify the path of the image but it is higly recommended to add the alt that specifies a description of the photo for the screenreaders and in case the image is not displayed.

## Q13 - Which attribute is always present for an anchor tag?
    href