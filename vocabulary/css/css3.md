# CSS Vocabulary 3 

- Downside of element selectors
- Making custom elements
    - Classes
    - Class selectors
- Simple positioning
- Margin
- Centering using margin: auto
- Padding
- Smooth border using border radius
- Box shadow

<hr>

## The downside of elements selectors

Using element selectors in internal stylesheets is a big improvement over using inline styles because you avoid a lot repetition.

But the problem with element selectors is that `they style all html elements of a certain type`. On small pages that might be fine, but if your page contains lots of headings, images and the like we will need to be more specific. 

Going back to using inline styles for exceptions is possible, but not very appealing.

## Making Custom elements

Luckily HTML & CSS have got us covered. We can make out own custom elements using classes. 

## Classes

We can add a `class` attribute to a HTML element to start customizing it.

```html
<h1>I am a normal heading</h1>
<h1 class="mySpecialHeading">I am a custom one!</h1>
```

## Class Selectors

To customize our special heading we can use a `class selector` in our CSS. The syntax is a dot `.` followed by the name of the class. 

In our example it would be `.mySpecialHeading`

```html
<h1>I am a normal heading</h1>
<h1 class="mySpecialHeading">I am a custom one!</h1>

<style>
    /* Style all h1 elements using the element selector */
    h1 {
        color: blue;
    }

    /* Add addtional styling or override styling with a class selector */
    .mySpecialHeading {
        color: pink;
        font-size: '50px';
    }
</style>
```

## Simple positioning

We know how to center our text using text-align. But it seems that text-align does not have a lot of options. It's either left, right or center!

There are many ways to position elements in CSS but we're going to start wioth the most straightforward way: `margin` and `padding`.

## Margin

Every element can have `margin` - `space between itself and other elements`. You can have margin left, right, top and bottom. 

```css
h1 { 
    margin-top: 500px;
    margin-bottom: 300px;
    margin-right: 200px;
    margin-left: 100px;
}

h2 {
    /* This way we apply margin top, bottom, right and left each will be 50px */
    margin: 50px;
}
```

## Centering with margin: auto

You can center elements instead of text using `margin: auto`. This will apply equal amount of margin left as right - centering the element.

WARNING: if you element has no defined width, it will not get centered.

```css
section {
    /* This should center all sections */
    /* Define the width of the element */
    width: 50vw;
    /* Have equal margin on each side */
    margin: auto;
}
```

## Positioning element's content using padding

To position element's content we can use padding. This can give the content of elements a little space to "breathe".

```css
h4 {
    padding: 10px;
}
```

## Rounded corners using border-radius

In unstyled HTML almost everything is a box. To add rounded corners you can use the `border-radius` style rule.

```css
h4 {
    border-radius: 20px;
}
```

## Box shadow

To give a floating appearance to your elements you can use the cool `box-shadow` style rule

```css
h4 {
    box-shadow: 2px 4px 0px 0px #888888
}
```




