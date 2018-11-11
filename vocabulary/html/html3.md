# HTML Vocabulary 3 

- Indentation 
- Semantic HTML
- lists 
- default styling & behaviour

<hr>

## Indentation (best practice)

When your webpages become more complex you might have multiple `nested` html elements. In order to quickly see how deep an element is nested we can `indent` the html element with on 1 tab for each level of nesting. 

The browser does not care about indented code but your fellow developers (and you who is reading your code next week) do.

**Without indentation:**

```html
<!DOCTYPE html>
<html>
<head>
<title>Toodoo 🔥 Lit 🔥</title>
</head>
<body>

<!-- Header -->
<div>
<h1>Toodoo 🔥 Lit 🔥 </h1>
<h3>A todo app that's on fire</h3>
</div>

<!-- Todo list -->
<div>
<h2>Todo's:</h2>
<p>- 🔨 Learn HTML 🔨</p>
<p>- 🎨 Learn CSS 🎨</p>
<p>- ⚡ Learn JavaScript ⚡</p>
<p>- 🚧 Finish todo app 🚧</p>
</div>

<!-- Footer -->
<div>
<h5>Made by me with ❤️ in Amsterdam</h5>
</div>

</body>
</html>
```

**With indentation**
```html
<!DOCTYPE html>
<html>
<head>
    <title>Toodoo 🔥 Lit 🔥</title>
</head>
<body>

    <!-- Header -->
    <div>
        <h1>Toodoo 🔥 Lit 🔥 </h1>
        <h3>A todo app that's on fire</h3>
    </div>
    
    <!-- Todo list -->
    <div>
        <h2>Todo's:</h2>
        <p>- 🔨 Learn HTML 🔨</p>
        <p>- 🎨 Learn CSS 🎨</p>
        <p>- ⚡ Learn JavaScript ⚡</p>
        <p>- 🚧 Finish todo app 🚧</p>
    </div>

    <!-- Footer -->
    <div>
        <h5>Made by me with ❤️ in Amsterdam</h5>
    </div>
    
</body>
</html>
```

## Semantic HTML (best practice)

A lot of the structuring of your website can be done using `<div>` tags. But a developer or a search engine might find it hard to quickly understand how your site is structured. 

You can make it easier by using more descriptive elements like the ones below. This is called using `Semantic HTML`. This also explains why there are a lot of different HTML elements you can use to accomplish the same goal.

**header tag:**
```html
<header>
    <!-- The header section of your page -->
</header>
```

**footer tag:**
```html
<footer>
    <!-- The footer section of your page -->
</footer>
```

**nav tag**
```html
<nav>
    <!-- A navigation bar containing different links -->
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
</nav>
```

**section tag**
```html
<section>
    <!-- Different sections of your site -->
    <!-- Also not really that descriptive -->
</section>
```

## Default behaviour of HTML elements

While some elements like div, header, footer are purely descriptive, some HTML elements have certain default behaviour and/or styling. A good example are unordered or ordered lists below.

**unordered list tag:**

```html
<ul>
    <!-- Default styling: -->
    <!-- Nested list items are display with a bullet point -->
</ul>
```

**ordered list tag :**

```html
<ol>
    <!-- Default styling: -->
    <!-- Nested list items are display with incrementing numbers -->
</ol>
```

**list items:**
```html
<!-- Item used in ordered or unordered lists -->
<li>List item</li>
```

Example:

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

Will result in:

- HTML
- CSS
- JavaScript

```html
<ol>
    <li>Chop vegtables</li>
    <li>Put oil in the pan and apply heat</li>
    <li>Stir fry vegtables</li>
    <li>Serve</li>
</ol>
```

Will result in:

1. Chop vegtables
1. Put oil in the pan and apply heat
1. Stir fry vegtables
1. Serve

## How to know what element to use

- With practice you will learn the default behaviour and styling of elements. Don't try to memorize it all.
- Default styling and behaviour can be found in online documentation like MDN.
- Look for and emulate examples until you understand the right choice.
- As a beginner using semantic HTML is not that important yet.