# Quizlit challenge 6

## Make the answers cards with different colors

By using classes and class-selectors

For examples of how to use classes and class-selectors to make cards look at: `toodoo-lit/v6/index.html`

## Challenge mode

[ ] Copy `index.html`, `wrong.html` and `correct.html` from `quizlit/v5` to `quizlit/v6`. 
[ ] Give each answer a different background color using classes  
[ ] Make the answers into cards  
[ ] Center the cards  
[ ] Give the content in the cards some space to 'breathe'

<hr>

## Easy mode

1. Copy `index.html`, `wrong.html` and `correct.html` from `quizlit/v5` to `quizlit/v6`.

2. Replace the first answer by the snippet below

```html
<a href="wrong.html"><h4 class="card yellow">A wrong answer</h4></a>
```
3. Inside your style tags at the bottom of the page add the following CSS:

( this should make the answer have a red background ) 

```css

.card {
    border-radius: 0px;
    box-shadow: 0px 0px 0px 0px black;
}

.yellow {
    background-color: red;
}

```

4. Change the values of the CSS you copied to make the answer a card and give it the background color yellow. For an example check `toodoo-lit/v6/index.html`.

5. Using this technique make cards out of all the answers and give them each a different color. You'll have to add a `class` attribute to each answer with the value `card` and the classname of the background-color like `yellow` from the example.

Here are some hex codes with different colors:  
    - Yellow: `#FEDC25`  
    - Blue: `#1E90FF`  
    - Green: `#80C683`   
    - Orange: `#F1662B`  

