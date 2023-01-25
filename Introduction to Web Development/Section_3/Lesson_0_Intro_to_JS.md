# A dive into Javascript

Let's add a button to our page that will change the text of the paragraph when clicked.

To get started, let's add a button to our page. To do this, we can add the following code between the `<body>` tags:

```html
<button>Click me!</button>
```

Now, let's add a paragraph to our page. To do this, we can add the following code between the `<body>` tags:

```html
<p>Click the button to change this text!</p>
```

Let's test the button out!

...and it doesn't work! Why is that?

Well, we haven't told the button what to do when it's clicked. Right now, we didn't specify any code to run when the button is clicked. Let's fix that.

## What is Javascript?

Javascript is a programming language that is used to make web pages interactive. It is used to add functionality to web pages, such as changing the text of a paragraph when a button is clicked. It is also used to add animations to web pages, such as making an image move across the screen when the page loads.

## Adding Javascript to our page

To add Javascript to our page, we can add the following code between the `<body>` tags:

```html
<script>
  // Javascript code goes here
</script>
```

This code tells the browser to run the Javascript code between the `<script>` tags when the page loads.

## Adding an event listener

Now that we have added Javascript to our page, let's add some code to make the button work. To do this, we can add the following code between the `<script>` tags:

```js
document.querySelector('button').addEventListener('click', function() {
  // Javascript code goes here
});
```

Let's break this down:

```js
document.querySelector('button')
```

This line of code tells the browser to select the button on the page.

```js
...addEventListener('click', function() {
  // Javascript code goes here
});
```

This line of code tells the browser to run the code between the curly braces when the button is clicked.

## Changing the text of a paragraph

Now that we have added an event listener to the button, let's add some code to change the text of the paragraph when the button is clicked. To do this, we can add the following code between the curly braces:

```js
document.querySelector('p').textContent = 'You clicked the button!';
```

Similar to the button:

```js
document.querySelector('p')
```

This line of code tells the browser to select the paragraph on the page.

```js
...textContent = 'You clicked the button!';
```

This line of code tells the browser to change the text of the paragraph to "You clicked the button!".

**Woah. Mind blown.**

Javascript is very powerful. We can do a lot of cool things with it. Let's try out some more examples.

## Form validation

Let's add a form to our page. To do this, we can add the following code between the `<body>` tags:

```html
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" />
  <input type="submit" value="Submit" />
</form>
```

Now, let's add some logic to the form so that it doesn't submit if the user doesn't enter a name. To do this, we can add the following code between the `<script>` tags:

```js
document.querySelector('form').addEventListener('submit', function(event) {
  event.preventDefault();
  if (document.querySelector('#name').value === '') {
    alert('Please enter a name!');
  }
});
```

Let's go further. Let's add a message at the end of the form that says "Thank you for submitting, NAME!". To do this, we can add the following code between the `<script>` tags:

```js
document.querySelector('form').addEventListener('submit', function(event) {
  event.preventDefault();
  if (document.querySelector('#name').value === '') {
    alert('Please enter a name!');
  } else {
    // NEW CODE
    document.querySelector('form').innerHTML =
      'Thank you for submitting, ' +
      document.querySelector('#name').value +
      '!';
  }
});
```

Try it out!

## A little task for you

Try adding a button to your page that changes the color of your site's background when clicked. If you get stuck, try to Google the problem. If you still can't figure it out, try asking someone in the support chat.

Hint: You can change the background color of an element using the `style` property. For example, `document.querySelector('body').style.backgroundColor = 'red';` will change the background color of the body to red.

## What's next?

We are not going to cover much more Javascript in this course. However, if you want to learn more, I recommend checking out [Codecademy's Javascript course](https://www.codecademy.com/learn/introduction-to-javascript).

Next up, we will [learn about the amazing world of Javascript-based frameworks.](Lesson_1_Intro_to_React.md) We will talk about React, a popular Javascript framework that is used to build web applications. We will also begin our v2 of the portfolio project.

## Resources

- [Codecademy's Javascript course](https://www.codecademy.com/learn/introduction-to-javascript)
- [MDN Web Docs - Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [W3Schools - Javascript](https://www.w3schools.com/js/)
