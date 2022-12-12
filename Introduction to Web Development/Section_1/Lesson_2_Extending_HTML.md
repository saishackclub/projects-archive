# Extending our HTML capabilities

Now that we know a little bit about HTML, let's look at a couple of (optional) ways to add some extra functionality to our website. We'll be using a couple of new tags, so let's take a look at them.

## Adding a table: `<table>` and `<tr>`

The `<table>` tag is used to create a table. The `<tr>` tag is used to create a table row. Let's take a look at an example:

```html
<table>
  <tr>
    <td>First Name</td>
    <td>Last Name</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
  </tr>
</table>
```

This will create a table that looks like this:

First Name | Last Name
---------- | ---------
John       | Doe

## Adding a list: `<ul>`/`<ol>` and `<li>`

The `<ul>` tag is used to create an unordered list. The `<li>` tag is used to create a list item. Let's take a look at an example:

```html
<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ul>
```

This will create a list that looks like this:

* First item
* Second item
* Third item

On the other hand, the `<ol>` tag is used to create an ordered list. Let's take a look at an example:

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
```

This will create another list that looks like this:

1. First item
2. Second item
3. Third item

## Adding a video: `<video>`

The `<video>` tag is used to embed a video. Let's take a look at an example:

```html
<video src="https://www.youtube.com/watch?v=dQw4w9WgXcQ" controls></video>
```

This will embed a video that looks like this:

[![Rick Astley - Never Gonna Give You Up (Video)](https://img.youtube.com/vi/dQw4w9WgXcQ/0.jpg)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

## Adding an audio file: `<audio>`

Similarly, the `<audio>` tag is used to embed an audio file. Let's take a look at an example:

```html
<audio src="https://www.youtube.com/watch?v=dQw4w9WgXcQ" controls></audio>
```

## A little task for you

Add a couple of new stuff to your site and show them off on the community chat! You now know the basics of HTML, so you can do anything you want with it. Good job - you're now officially a web developer! 🎉

## What's next?

Now that you know the basics of HTML, you can [start learning about CSS.](../Section_2/Lesson_1_Intro_to_CSS.md) CSS is used to style your website, and it's a lot of fun to play around with. 🌈

If you want to look at what we have so far, you can [check out the final code here.](Wrapup.md)
