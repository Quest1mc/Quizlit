# HTML Vocabulary 2 

- Attributes
- Images
- Links

<hr>

## Attributes

Some html elements need additional information to function properly. We can provide this information using `attributes`. 

**Syntax:**  
An attribute usually has a `type` followed by a `=` and a `value` between quotes (`""`)

```html
<img src="images/html_logo.png">
```

An image with an attribute of the `type`: `src` with the `value`: `images/html_logo.png`

Sometimes attributes are used to be able to configure HTML with extra style using css or functionality using javascript. We will go into this later.

## Self closing tags

Not all HTML elements need opening and closing tags. Element which do not need a closing tag are called `self-closing` tags. An exmaple of a self closing tag is an `<img>` tag.

## Images and Links

**img tag:**

```html
<img src="images/html_logo.png">
```

An image tag lets you display an image on your page. It needs an `src` attribute where you provide the location of the image using an imageURL and the image extension like .png or.jpg etc. An image tag is `self-closing`.

**a (anchor / hyperlink) tag:**

```html
<a href="todo.html">My link to another page on my site</a>

<a href="https://www.google.com/">My link to another website</a>

<a href="todo.html">
    <h1>A heading wrapped in an anchor tag</h1>
</a>
```

An anchor tags lets you create a hyperlink to a page on your website or another website entirely. It needs an `href` attribute where you provide a destination using a URL. You can make any html element link somewhere by wrapping it in an anchor tag.




## Loading external files

**link tag:** 

```html
<link rel="stylesheet" type="text/css" href="theme.css">
```

A link tag is used to load external files from a file. It needs a `rel` attribute and `type` attribute to know what kind of file is being loaded and a `href` attribute with the location of the file as an URL. Link tags are most commonly used to load external CSS files. 

**script tag**

