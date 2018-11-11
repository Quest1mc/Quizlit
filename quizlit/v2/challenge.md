# Quizlit challenge 2

## Make the quiz app work 

By using hyperlinks

For examples of how to make hyperlinks and add images check out `toodoo-lit/v2`. 

**Challenge mode:**

[ ] Copy your index.html from the previous exercise to `quizlit/v2`    
[ ] Create 2 new files in `quizlit/v2`: `correct.html` and `wrong.html`  
[ ] Add a basic html structure to both  
[ ] Add the text: "Wrong answer - Sorry!" to `wrong.html`  
[ ] Add the text: "Correct answer - Awesome!" to `correct.html`  
[ ] Change the text elements with the 4 answers on `index.html` to 4 hyperlinks  
[ ] The hyperlink destination for the correct answer will be `correct.html`  
[ ] The hyperlink destination for the wrong answers will be `wrong.html`  
[ ] Add a "back" hyperlink to `correct.html` and `wrong.html`

Bonus:  

[ ] Make an `images` folder  
[ ] Add an image to your index.html  

Bonus 2: 

[ ] Using links make the quiz have multiple questions

<hr>

**Easy mode:**

0. Copy your index.html from the previous exercise to `quizlit/v2`
1. In `quizlit/v2` make a file `wrong.html` and copy/paste the 
following code into it:


```html
<!DOCTYPE html>
<html>
<head>
    <title>Quizlit</title>
</head>
<body>
    <h1>Wrong answer - Sorry!</h1>
    <a href="index.html">back</a>
</body>
</html>
```

2. Make a similar page called `correct.html` but change the text to "Correct answer - Awesome!"

3. On `index.html` change h4 element with a wrong answer to a hyperlink like this:

```html
<!-- Change this -->
<h4>Some wrong answer</h4>

<!-- To this: -->
<a href="wrong.html"><h4>Some wrong answer</h4></a>
```

4. Do the same for the other wrong answers
5. Do the same for the correct answer but the value of `href` attribute should be: `correct.html`
