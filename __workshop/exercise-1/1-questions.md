# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false ] `<div><span>hello</div></span>`

b) [ true ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ false ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

Generally, screen readers are separate apps that run on the host operating system and can read not only web pages, but text in other apps as well. This is not always the case (ChromeVox is a browser extension), but usually. Screenreaders tend to act in slightly different ways and have different controls, so you'll have to consult the documentation for your chosen screen reader to get all of the details — saying that, they all work in basically the same sort of way.

We should care about them as they allow those with visual impairements to still "read" the content on the web. It is a Accessibility tool. 

https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Accessibility 

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

<img class = "image"
     src = "image.jpg"
     alt = "description of image">

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

<a href="URL">clickable text</a> 

c) You want to sell designer hats. You need to receive orders from the user.

<input type="number" name=?>
 Sets a single-line textbox for a number 

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

No, because you wouldn't be able to contain a button within another button. The button would have to be the child of another parent tag ie. <body> tags

## Q5 - What is the most generic tag you can use?

<p>...</p>

## Q6 - What do the following achronyms stand for?

a) `a` : The HTML <a> element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address. Content within each <a> should indicate the link's destination.

b) `ol` : The HTML <ol> element represents an ordered list of items — typically rendered as a numbered list.

c) `ul`: The HTML <ul> element represents an unordered list of items, typically rendered as a bulleted list.

d) `li`: The HTML <li> element is used to represent an item in a list. It must be contained in a parent element: an ordered list (<ol>), an unordered list (<ul>), or a menu (<menu>). In menus and unordered lists, list items are usually displayed using bullet points. In ordered lists, they are usually displayed with an ascending counter on the left, such as a number or letter.

e) `tr`: The HTML <tr> element defines a row of cells in a table. The row's cells can then be established using a mix of <td> (data cell) and <th> (header cell) elements.

f) `th`: The HTML <th> element defines a cell as header of a group of table cells. The exact nature of this group is defined by the scope and headers attributes.

g) `td`: The HTML <td> element defines a cell of a table that contains data. It participates in the table model.

## Q7 - Usually, `td` elements are children of what kind of elements? 

Usually children of of the <tr> tag

## Q8 - What is the difference between td and th?

<td> and <th> are both children of the <tr> tag. <td> relates to the data cell and <th> to the header cell elements.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

<h1>

## Q10 - In which situation can you use self closing tags?

It's used to communicate lack of content in between the opening and closing tags. So, rather than typing <p></p> (with no space at all in between), you'd be able write <p/> .


## Q11 - What is autofilling and why is it important?

(autocomplete)

The HTML autocomplete attribute allows web developers to control the autocomplete feature to prevent these sorts of scenarios. It works by allowing the websites to control whether sensitive data entered in the form and input elements will be stored in the user’s browser cache.

https://www.netsparker.com/blog/web-security/impact-autocomplete-feature-web-security/#:~:text=The%20HTML%20autocomplete%20attribute%20allows,in%20the%20user's%20browser%20cache 

## Q12 - Which attributes are always present in an img element?

The src and alt attributes are required for the document to be valid

## Q13 - Which attribute is always present for an anchor tag?

 The <a> element isn't a link (:link) unless it has an [href] attribute. A side-effect of this is that an <a> element without [href] won't be in the tabbing order by default. 

 https://stackoverflow.com/questions/10510191/valid-to-use-a-anchor-tag-without-href-attribute 

