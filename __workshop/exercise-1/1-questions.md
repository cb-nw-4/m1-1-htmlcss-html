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

c) [ture] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

"Screen readers are software programs that allow blind or visually impaired users to read the text that is displayed on the computer screen with a speech synthesizer or braille display. A screen reader is the interface between the computer's operating system, its applications, and the user."
https://www.afb.org/blindness-and-low-vision/using-technology/assistive-technology-products/screen-readers

When coding, it is essential to use Semantic HTML so that we can ensure the accessiblity by the visually impared who are using a screenreader to read the text of the websites.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
        <img>
        <img>
        <img>
    </body>
</html>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
        <a></a>
        <a></a>
        <a></a>
    </body>
</html>

c) You want to sell designer hats. You need to receive orders from the user.
<!DOCTYPE html>
<html>
    <head>
    </head>
    <body>
        <image> <!-- This is to show the image of the hat I want to sell -->
        <p></p> <!-- Description of the hat, prices etc. -->
        <form>
            <input></input> <!-- Customer info, which hat to buy etc. -->
            <input></input> 
            <input></input> 
            <button></button> <!-- To submit the order -->
        </form>
    </body>
</html>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No, it is not valid to put a <button> inside a <button> element. <button> tab should contain phrasing content. There must be no interactive content descendant and no descendant with the tabindex attribute specified.


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
'table' element and 'tr' element

## Q8 - What is the difference between td and th?
The <td> tag, or "table data" tag, creates table cells within a table row in an HTML table. This is the HTML tag that contains the content (any text and images) of the HTML table.

The <th> tag, or "table header," is similar to the <td> in many ways. It can contain the same kind of information (although we wouldn't put an image in a <th>), but it defines that specific cell as a table header.
The <th> tag should be used when we want to designate the content in the cell as a header for that column or row.
https://www.lifewire.com/difference-between-th-and-td-html-table-tags-3469866

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1

## Q10 - In which situation can you use self closing tags?
A self-closing tag is a special kind of HTML tag that does not have a closing tag counterpart. It means that the tag has no content. Some examples of self closing tags are: <meta>, <input>, <image>

## Q11 - What is autocomplete and why is it important?
Autocomplete allows the browser to predict the value. When a user starts to type in a field, the browser should display options to fill in the field, based on earlier typed values. 

While this means that users don’t have to repeatedly enter their personal information, the autocomplete feature can become a liability once attackers gain access to our computers or the browsers in use. The HTML autocomplete attribute becomes important because it allows web developers to turn on/off the autocomplete feature and control whether sensitive data entered in the form and input elements will be stored in the user’s browser cache.


## Q12 - Which attributes are always present in an img element?
'src' attribute and 'alt' attribute

## Q13 - Which attribute is always present for an anchor tag?
'href' attribute
