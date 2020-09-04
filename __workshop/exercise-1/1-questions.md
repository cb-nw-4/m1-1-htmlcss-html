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

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<img src="https://img.playbuzz.com/image/upload/ar_1.5,c_crop/q_auto:good,f_auto,fl_lossy,w_640,c_limit/v1567206236/bcvzij30tunopiqxnfok.jpg" alt="image test"/>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<ul> 
    <li><a href="http://www.google.ca">Galery 1</a></li> 
    <li><a href="http://www.google.ca">Galery 2</a></li> 
</ul>

c) You want to sell designer hats. You need to receive orders from the user.
<form>
    <label for="user">username</label>
    <input type= "text" id="username">
    <label>Quantite</label>
    <input type="number" id="quantite">
</form>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No it can't, the button is inline element with attributes, when we click, an event happen but we can't have a click of click.

## Q5 - What is the most generic tag you can use?
<p>

## Q6 - What do the following achronyms stand for?

a) `a` anchor : hyperlink

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr`  table row

f) `th` table header cell

g) `td` table data cell 

## Q7 - Usually, `td` elements are children of what kind of elements?
<tr>

## Q8 - What is the difference between td and th?
we use <th> in the begining of table that contain title of each row and it came bold. Exemple <th> Name </th>
we use  <td> that contain all data for each row of title.  Exemple <td> Alex</td>

## Q9 - Which tag makes the text appear bigger: h1 or h3?
<h1>

## Q10 - In which situation can you use self closing tags?
for an image we have self closing tag <img src="" />

## Q11 - What is autofilling and why is it important?

## Q12 - Which attributes are always present in an img element? 
src: source of image , alt: description of the image

## Q13 - Which attribute is always present for an anchor tag?
href : link for the destination address 
