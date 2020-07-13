- `<>` angle brackets indicate code
- `<h1>` angle brackets with specific characters inside are called tags
- `h1` is  a heading element indicating highest importance. This will likely go at the top of the page.
- `</h1>` closing tags are signified by a forward slash before the characters
- when `<h1></h1>` are used together they form an element. anything between those tags is part of the element.
- an attribute is a specific set of characters(usually providing something with a value: `lang=fr`) is place inside the opening tag, `<h1 lang=fr>`, where lang is the name of the attribute and fr is the value. here you can see us telling the computer that we intend to use french for this `h1`.
- there are style elements in html but it's best to save styling for css to avoid confusing anyone else who might work on the website
- html is adding and removing parts of its language so some older browsers may not be able to see some newer elements and it's important to try to account for that in your site
`<!DOCTYPE html>` is used to tell the browser you are using html5. different versions would have some info between the l and > such as: 
```
<!DOCTYPE html PUBLIC
    "-//W3C//DTD HTML 4.01 Transitional//EN"
    "http://www.w3.org/TR/html4/loose.dtd">
```
`<aside>` can be used to create a box next to the rest of the `<main>` (main being the content rich center of the article) [that does kinda seem like style so should really be using that?]