# CSS Vocabulary 3 

- Reusing stylesheets for multiple pages
- External CSS
- `<link>` Element
- Custom fonts

<hr>

## Reusing stylesheets for multiple pages

We've been ignoring our poor `wrong.html` and `correct.html` which are still completely unstyled. 

We could make an internal stylesheet for each seperate page. But we'll have to write the same style rules multiple times for different pages. 

## External CSS

Luckily we can make a single stylesheet that we can use on many different pages. This is called `External CSS`. Now that we have an internal stylesheet it won't be that much work.

**How to make your internal stylesheet an `external stylesheet`:**

1. Make a file called `main.css`
2. Copy/Paste the selectors and stylerules from your internal stylesheet into `main.css` WARNING: don't copy the `<style>` tags as they will create a syntax error.
3. In the head of `index.html`, `wrong.html` and `correct.html` paste the following HTML tag:

```html
<link href="css/main.css" rel="stylesheet">
```

4. Delete your internal stylesheet 

## The `<link>` tag

The `<link>` tag can be used to load in external files like stylesheet to your page. This allows us to make external stylesheet.

But it also allows us to load stylesheets from 3rd parties. 

## Custom fonts

One common usage for the `<link>` element is to load a custom font! 

The link below loads 2 fonts: Athiti and Pattaya from google-fonts

```html
<link href="https://fonts.googleapis.com/css?family=Athiti|Pattaya" rel="stylesheet">
```

They can be used in your CSS using the `font-family` style rule. 

The first value is the custom font 'Athiti', the second value is a `fallback font`,   `sans-serif` in this case, which is always available. This is in case Athiti won't load or hasn't loaded yet. 

```css
body {
    font-family: 'Athiti', sans-serif;
}
```