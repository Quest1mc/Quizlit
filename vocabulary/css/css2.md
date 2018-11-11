# CSS Vocabulary 3 

- Downsides of inline styles
- Internal CSS
- Style tags
- CSS Comments
- CSS Element Selectors

<hr>

## Downsides of inline styles 

- **Applying style rules to every individual element will take lots of time.** 
- **It makes changing style rules that are applied to multiple elements hard** because you have to change it in many different places.

## Internal CSS

Internal CSS allows us to style multiple elements at once. This takes care of a lot of problems with inline styles.

## Style tags

We have to tell the browser that we want to create an internal stylesheet so that it can read the CSS syntax. We do that using `style tags`. 

`style tags` can be put anywhere on the page. 

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
<style>
    /* Our internal stylesheet */
</style>
</html>
```

## CSS comments 

Like HTML, CSS also has comments so you can leave notes for yourself and others. The syntax for a CSS comment is `/* your comment here! */`

## CSS Element Selectors

Selecting the element to style with inline styles was easy; you just added a style attribute to a HTML tag.

In internal stylesheets selecting the element works using `selectors`. The first ones we will be using will be `element selectors`. 

An `element selector` is simply the `type of HTML tag you want to style`, followed by a set of curly braces `{}` that contain the style rules.

```html
<style>
/* We want to style the body, so we use the body element selector */

body {
    /* style rules should go here */
    background-color: 'pink';
    /* you can apply multiple rules in one selector */
    font-size: '50px';
}

/* We want to style all list elements on the page, so we use the li element selector */
li {
    /* style rules should go here */
}
</style>
```



