# HTML most used elements

There are a little bit more than 100 HTML tags in total but some of them used more often than others. Let's take a look at those once. 

## Text elements

Headings to use on the headings of the pages, sections or subsections:

```html
<h1>Heading of level 1</h1>
<h2>Heading of level 2</h2>
<h3>Heading of level 3</h3>
<h4>Heading of level 4</h4>
<h5>Heading of level 5</h5>
<h6>Heading of level 6</h6>
```

```html
<p>Paragraphs to wrap text paragraph inside.</p>
```

```html
<ul>
	<li>unordered list with the list items inside</li>
	<li>will be rendered with the bullets by default</li>
	<li>used to render content which is a list of items</li>
</ul>
```

```html
<ol>
	<li>this is an ordered list</li>
	<li>every element in it will have it's own number</li>
	<li>it could be a list of steps to follow or any other numbered items</li>
</ol>
```

## Images

To render an image with HTML we need to use "img" tag:

```html
<img src="https://raw.githubusercontent.com/gk3000/artsy_bananas/main/artsy_bananas_00.png" alt="Artsy banana" />
```

First thing you will notice about "img" element is that it is *self-closing*, there are no opening and closing tags but one tag which we open with `<` and close with `/>`.

Another thing we see here is that element has 2 *attributes* inside: `src` and `alt`. 

`src` attribute points to the URL or address of image we want to render and `alt` attribute contains the description of the image which is used if image file is not available or for the screen readers. For the reasons of accessibility it is obligatory to add `alt` attribute to the images we render. 

## Buttons 

To add a button we will use a "button" element like so:

```html
<button>Click me</button>
``` 

This snippet will render a button with the label "Click me"

> Take a look at [this CodePen](https://codepen.io/GK3000/pen/rNvMoWY) to see how those elements are rendering content.