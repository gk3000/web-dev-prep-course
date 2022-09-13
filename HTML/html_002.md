# HTML tags

Any content item to be displayed in the page should be concluded inside a HTML element so that the browser will understand what kind of content it is. 

For example we can have paragraphs, headings, images, lists, etc...

The syntax for the most tags is that we have an opening and closing tag with the content inbetween, like so:

```html
<p>I am just a paragraph of text. I have to be inside the <p> tag </p>
```

If in the content we have several paragraphs we can put them into several "p" tags:

```html
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

<p>Ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

<p>Consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
```

Apart from paragraphs we also have headings to display well... headings. They can be of 6 level of importance, from `h1` to `h6`. 

Imagine we have this passage of text where headings are nested based on the structure of the content:

```html
<h1>How to learn HTML</h1>
<h2>Part 1</h2>
<p>First, understand that HTML is used to describe the structure of our content. Even though you will see, that content in different elements is rendered differently in the browser inside different tags, the goal of HTML is not to affect the visual design of your elements, but to describe them on a structural level only.</p>
<h2>Part 2</h2>
<p>As you can see in this snippet, we have the main heading of level 1 and subheadings of level 2. Below we will create a subheading of level 3 which will be part of this current section of content you are reading through.</p>
<h3>Part 2 section A</h3>
<p>With h3 above we show to the browser that this heading is just a subheading of Part 2. A bit similar to books where we can have chapters, subchapters, and so on.</p>
<h2>Part 3</h2>
<p>Remember, that there are 6 levels of headings we can use: h1, h2, h3, h4, h5, h6.</p>
```

> Check out this [CodePen](https://codepen.io/GK3000/pen/gOzwaKE) to see how those elements are rendered.

<iframe height="300" style="width: 100%;" scrolling="no" title="html_002" src="https://codepen.io/GK3000/embed/gOzwaKE?default-tab=html%2Cresult" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/GK3000/pen/gOzwaKE">
  html_002</a> by George K (<a href="https://codepen.io/GK3000">@GK3000</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

