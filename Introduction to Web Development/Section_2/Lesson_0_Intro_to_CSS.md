# What is CSS?

CSS stands for Cascading Style Sheets. It's a language that's used to style web pages. It's used to change the color of text, the style of fonts, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!

CSS is a lot of fun to work with, and it's used in pretty much every web page you visit. It's a really important part of web development, and it's a lot of fun to learn.

## How does CSS work?

Say, for example, you have a web page that looks like this:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My first web page</title>
  </head>
  <body>
    <h1>My first web page</h1>
    <p>I really want to turn this paragraph red.</p>
    </body>
</html>
```

You can see that the paragraph is black. You want to turn it red. How do you do that? You can't just change the color of the text in the HTML file, because the HTML file doesn't have any information about how the text should be displayed.

That's where CSS comes in. ✨

In your repository, you should see a file called `index.css` within the `assets/styles` folder. Open it up and take a look at the contents:

```css
/* Add your styling here! */
```

Hmm, that's not very helpful. Let's add some CSS to make the paragraph red.

```css
p {
  color: red;
}
```

Save the file, and then open up `index.html` in your browser. Bam! The paragraph is now red. 💥

## Q: How does CSS know which elements to style?

A: CSS uses something called **selectors** to select the elements that it should style. There are a lot of different types of selectors, but we'll only be using a few of them in this course.

### Element selector

The element selector is the most basic selector. It selects all elements of a certain type. For example, the following CSS will select all `<p>` elements on the page and make them red:

```css
p {
  color: red;
}
```

### Class selector

The class selector is used to select elements with a certain class. For example, the following CSS will select all elements with the class `red-text` and make them red:

```css
.red-text {
  color: red;
}
```

```html
<p class="red-text">I'm red!</p>
```

### ID selector

The ID selector is used to select elements with a certain ID. For example, the following CSS will select the element with the ID `red-text` and make it red:

```css
#red-text {
  color: red;
}
```

```html
<p id="red-text">I'm red!</p>
```

Ok, enough theory. [Let's get to work!](Lesson_1_Making_Your_Site_Fancy.md)
