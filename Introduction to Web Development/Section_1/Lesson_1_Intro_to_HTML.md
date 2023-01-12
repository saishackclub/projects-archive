# An introduction to HTML

## What's that?

HTML stands for **H**yper**T**ext **M**arkup **L**anguage (pronounced "H-T-M-L"). It's a language that web developers use to tell web browsers how to display content on a web page.

HTML is made up of a bunch of different elements, which are basically just tags that tell the browser how to display the content. For example, the following HTML code tells the browser to display the text "Hello, world!" as a heading:

```html
<h1>Hello, world!</h1>
```

## Let's break it down

HTML elements are made up of a **start tag**, some **content**, and an **end tag**. The start tag tells the browser where the element begins or starts to take effect, and the end tag tells the browser where the element ends. The content is the text or other HTML elements that are contained between the start and end tags.

For example,

```html
<h1>Hello, world!</h1>
```

is an HTML element that tells the browser to display the text "Hello, world!" as a heading. The `<h1>` is the start tag, the `</h1>` is the end tag, and the `Hello, world!` is the content.

## A small list of HTML elements

Here's a small list of some of the most common HTML elements:

| Element         | Description                                                                                                                              |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| `<h1>` - `<h6>` | These elements are used to display headings. The `<h1>` element is the most important heading and `<h6>` is the least important heading. |
| `<p>`           | This element is used to display a paragraph of text.                                                                                     |
| `<a>`           | This element is used to create a link to another page or to an *anchor* on the same page.                                                |
| `<img>`         | This element is used to display an image.                                                                                                |

Additionally, there are a bunch of other elements that you can use to format text, create lists, tables, and more. You can find a list of all of the HTML elements [here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

*P.S. If you want to work with something I didn't cover, feel free to go ahead and Google it. There are a lot of resources out there that can help you learn more about HTML.*

## Let's actually start coding

Let's return to our VS Code workspace and open up the `index.html` file. You should see something like this:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Build Your Own Website</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
  </body>
</html>
```

Let's break this down:

```html
<!DOCTYPE html>
```

This line tells the browser that the document is an HTML document.

```html
<head>
  <meta charset="utf-8">
  <title>Build Your Own Website</title>
</head>
```

The `<head>` element contains information about the document, but it is not displayed. The `<meta>` element specifies character set used, and the `<title>` element specifies a title for the document.

```html
<body>
  <h1>Hello, world!</h1>
</body>
```

The `<body>` element contains the visible page content, aka the stuff that you see when you open up the page.

## Let's make some changes

Now that we know a little bit about HTML, let's make some changes to the `index.html` file. First, let's change the title of the page. To do this, we can change the text between the `<title>` tags to whatever we want. For example, I could change it to "My Website".

```html
<title>My Website</title>
```

Next, let's change the text that is displayed on the page. To do this, we can change the text between the `<h1>` tags to whatever we want. For example, I could change it to "Hello, my name is [your name]".

```html
<h1>Hello, my name is [your name]</h1>
```

You can even add in an image! To do this, we can add the following code between the `<body>` tags:

```html
<img src="https://i.imgur.com/1Qy1Z9r.jpg" alt="A picture of a cat">
```

This code tells the browser to display an image with the source `https://i.imgur.com/1Qy1Z9r.jpg` and the alt text `A picture of a cat` (that link doesn't actually work lol).

Be creative! You can change the text to whatever you want; as your final project, you will be creating your own portfolio website, so you can use this as an opportunity to get some practice with HTML.

## Let's save our changes and view the page

Now that we've made some changes, let's save the file. To do this, we can go to File > Save or press `Command + S` on your keyboard.

Now, let's view the page. To do this, go to your Finder and open up the `build-your-own-website` folder. You should see a file called `index.html`. Double-click on it to open it up in your browser. You should see the changes that you made!

## A quick note about HTML

HTML is a very powerful language, but it can be a little bit confusing at first. Don't worry if you don't understand everything that we covered today - we'll be learning more about HTML in the next few lessons. If you want to learn more about HTML, I recommend checking out [this](https://www.w3schools.com/html/) website.

## Let's recap

We learned about HTML and how to use it to create a web page. We also learned how to use Visual Studio Code to edit HTML files.

Soon, we'll be learning about CSS, which is a language that we use to style our web pages, and how we can merge HTML and CSS to create a cool-looking website.

## A little task for you

Send a screenshot of your website to me via the support chat. I'd love to see what you've created! 🔥

Let's keep going by [looking at a bit more HTML.](Lesson_2_Extending_HTML.md)
