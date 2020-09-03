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

a) `a`

b) `ol`

c) `ul`

d) `li`

e) `tr`

f) `th`

g) `td`

## Q7 - Usually, `td` elements are children of what kind of elements?

## Q8 - What is the difference between td and th?

## Q9 - Which tag makes the text appear bigger: h1 or h3?

## Q10 - In which situation can you use self closing tags?

## Q11 - What is autofilling and why is it important?

## Q12 - Which attributes are always present in an img element?

## Q13 - Which attribute is always present for an anchor tag?
