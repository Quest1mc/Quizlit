# CSS Vocabulary 1 

- Inline styles 
- Style rule syntax
- Colors
- Font size 
- Height / Width
- Aligning text
- Tips on learning style rules

<hr>

## Inline styles

The easiest way to start styling HTML is by using `inline styles`. You simply give a `style` attribute to a HTML element with a couple of style rules like this:

```html
<h1 style="color: red;">Hello</h1>
```

## Style rule syntax

Like attributes, each style rule has a `type` followed by a colon `:` and a `value` followed by a semi-colon `;`. In the above example the `type` of style rule applied is `color` and the `value` is `red`. If you forget a colon or a semicolon, the browser will not be able to interpret your CSS.

## Colors:

```css
/* to apply color to text use: */
color: red;

/* to apply color to a an element */
background-color: blue;

/* 

Rules to do with colors will accept values like:

- names of pre-programmed colors like: red
- hexcodes of colors like: #F10230
- rgb values of colors like: rgb(255, 99, 71)

*/
```

## Sizes

```css
/* to make font a certain size use: */
font-size: 24px;

/* to set the height or width of an element use: */
width: 200px;
height: 400px;

/* 

Rules to do with size will accept values like:

- Amount of pixels like: 200px;
- Percentage of the width of a screen like: 10vw (10% of screen width)
- Percentage of the height of a screen like: 20vh (20% of screen height)

The above are easiest to understand but there are more. Like %, em an rem.

*/
```

## Aligning text

```css
/* To align text use: */

text-align: center;

/* 

Text align will accept values like: 

- center, left, right
- justify (stretches lines to equal length like a newspaper)

*/
```

## How to know what style rule you need?

- **Examples** - Looking at examples is often the best way of learning what style rules to use to accomplish a certain look.  
- **Study what each rule does in isolation** - Most styling consists of many different rules applied together. If you take a few rules out and see the changes you'll gain a deeper understanding of what each rule is doing.
- **Documentation** - There is good documentation with worked examples for different style rules.

