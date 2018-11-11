# HTML Vocabulary 1 

- Basic structure, 
- Text
- Nesting

<hr>

## Basic HTML structure:

**DOCTYPE declaration:**  

```html
<!DOCTYPE html> 
```

Tells the browser know what version html is being used. Should be at the top of every HTML file.

**html tag:**  

```html
<html></html>
```

The html tag is a container for all other html elements.

**head tag:**
```html
<head></head>
```
The head tag contains information about the website like title, location of stylesheets or scripts and other meta information.

**title tag:**

```html
<title></title>
```

Tells the browser what text to display on the browser tab.

**body tag:**

```html
<body></body>
```

The body tag is a container for all the html elements visable on the page.

**HTML comment:**

```html
<!-- My comment  -->
```

A HTML comment lets the developer write text which is ignored by the browser. This way you can leave notes for other people who will read your code.

**HTML skeleton**

```html
<!DOCTYPE html>
<html>
<head>
    <title> My awesome app</title>
    <!-- Other stylesheets, scripts and metadata here -->
</head>
<body>
    <!-- Visible page content here -->
</body>
</html>

```

## Basic text

**h1 - h6 tags:**

```html
<h1>A big heading</h1> 
<h6>A small heading</h6>
```

h1, h2, h3, h4, h5, h6 are heading tags in different sizes. h1 being the largest and h6 being the smallest heading. 

**p tag:**

```html
<p>Some interesting text</p> 
```

A p tag is a paragraph tag which wraps around the page

**div tag:**

```html
<div>
    <!-- A seperate group of elements here -->
</div>
<div>
    <!-- Another group of elements here -->
</div>
```

A div tag allows you to divide your page into different pieces. 

## Nesting

HTML elements can be positioned **inside** other html elements. This is called `nesting`. 

```html
<div>
    <h1>This heading element is nested inside a div element</h1>
</div>
```